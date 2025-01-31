# Hang In There

A boilerplate repo.

## Set Up

1. One teammate: fork this repository
2. Clone down your new, forked repo
3. cd into the repository
4. Open it in your text editor
5. Add all project partners and your assigned instructor as collaborators on the repository

Project spec & rubric can be found [here](https://frontend.turing.io/projects/module-1/hang-in-there.html)

## Consultants:

* William Phelps
* Joana Brito
* Samantha Brown

## Consultants:

* Alex Kio
* Steven Mancine
* Lauren Kessell
* Demaceo Vincent

## Project Manager:

* Heather Faerber


## Technologies used:

* *HTML*
* *CSS*
* *JavaScript*

## Instructions for running and viewing:

* When the page loads, we should see a poster with a randomly selected image, title, and quote
* Every time the user clicks the Show Random Poster button, a new random poster is displayed.
* When a user clicks the **“Make Your Own Poster”** button, we should see the form, and the main poster should be hidden
* When a user clicks the **“View Saved Posters”** button, we should see the saved posters area, and the main poster should be hidden
* When a user clicks the **“Nevermind, take me back!”** or **“Back to Main”** buttons, we should only see the main poster section
* On the new poster form view, users should be able to fill out the three input fields and then hit the save button
* When the save button is clicked, several things will happen:
      * Save the submitted data into the respective arrays (image URL into the images array, etc) so that future random posters can use the user-created data
      * Use the values from the inputs to create a new instance of our Poster class
      * Change back to the main poster view (hiding the form view again)
      * Display the newly created poster image, title, and quote in the main view
* When a user clicks the **“Save This Poster”** button, the current main poster will be added to the savedPosters array.
* If a user clicks the **“Save This Poster”** more than once on a single poster, it will still only be saved once (no duplicates)
* When a user clicks the **“Show Saved Posters”** button, we should see the saved posters section
* All the posters in the savedPosters array should be displayed in the saved posters grid section
* From the saved posters view, if a user double clicks a saved poster, it will be deleted.


## Deploy link:

[Hang in there group project](https://joanafbrito.github.io/hang-in-there-boilerplate/)

## Images:
![Main page poster](https://user-images.githubusercontent.com/79541611/119277866-0ed02800-bbf0-11eb-9d2a-a6ced8910c68.png)

![Create your own poster main page](https://user-images.githubusercontent.com/79541611/119277866-0ed02800-bbf0-11eb-9d2a-a6ced8910c68.png)

![Your created poster](https://user-images.githubusercontent.com/79541611/119277912-48089800-bbf0-11eb-9013-e8025d85d4a4.png)

![Saved posters grid view](https://user-images.githubusercontent.com/79541611/119277957-75eddc80-bbf0-11eb-8771-07500dead766.png)

![Shows what you deleted from saved](https://user-images.githubusercontent.com/79541611/119277986-a2095d80-bbf0-11eb-84e1-e53ec4cf7630.png)


## Future Additions:

* Implement data validation and error handling into the form (such as provide error messages if data entered is not correct).
* In the main poster view, allow users to click each piece of the poster (image, title, quote) to update just that piece with another random item from the appropriate array.
* When a user single clicks a saved poster, create a modal to view it larger.
* Allow users to drag and drop saved posters into whatever order they want them to appear.
