Download Link: https://assignmentchef.com/product/solved-movie-collection-program
<br>
5/5 - (2 votes)

In this lab, you will create a movie collection program. You will only be collecting information about a single movie in this lab.



SolutionYour program should display a menu with a list of options for the user.

1.       List Movies

2.       Add Movie

3.       Remove Movie

4.       Quit

Keep displaying the menu until the user elects to quit the program. Note, you may use numeric or letter keys to provide your menu. If you use letters, make it case insensitive.

Movie InformationA movie will consist of the following information

NameTypeRequiredCommentsTitleTextYUnique title of the movie.DescriptionTextNOptional description of the movie.LengthIntegerNLength of the movie in minutes (default to 0). If specified then it must be = 0.OwnedBooleanYTrue if the movie is owned or false if it is on the wishlist.

AddPrompt the user for each piece of information about the movie. This lab accepts a single movie. If the user selects to add another movie, overwrite the original movie.

For each value check that the value is correct based upon the rules given earlier and keep prompting the user until the data is valid (i.e. until the length is = 0).

Note: Validating the title is unique is not necessary for this lab since there is only one movie.

ListDisplay the movie information.  Each value should be displayed on its own line with a label indicating what it represents.

If there are no movies then display “No movies available”.

RemovePrompt the user to confirm they want to delete the movie. If they confirm the deletion then clear the movie information.

QuitExit the program.

RequirementsYour program must meet all the following requirements.

·         Compile cleanly with no warnings or errors.

·         Meet all the points mentioned in the solution.

·         Ensure each file has a file header indicating the course, your name and date.

·         Solution, project and code should be uploaded to Github