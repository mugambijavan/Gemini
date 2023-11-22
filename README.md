 Updating a WordPress Site with a Custom Theme (Non-Child Theme)

 Introduction

 Updating can be challenging, especially if the theme was not developed as a child theme. Child themes allow you to make changes to the theme without affecting the original code.

 Solution

1]  Create a Child Theme:

Create a new folder in the wp-content/themes directory.
Name the folder the same name as the parent theme, with "-child" appended to the end.
Inside the child theme folder, create a stylesheet file called style.css.
Add the necessary comments to the style.css file.
Save the style.css file.

2] Copy the Parent Theme's functions.php File (if applicable):

Copy the functions.php file from the parent theme to the child theme folder.
This allows you to override functions without modifying the original code.

 3] Update the Child Theme's Stylesheet:

Make any desired changes to the stylesheet (colors, fonts, layout, etc.).

4]  Update the Parent Theme:

Navigate to Appearance > Themes in the WordPress admin dashboard.
Click the "Update Now" button next to the parent theme.
WordPress will download and install the latest version of the theme.

5]  Activate the Child Theme:

Navigate to Appearance > Themes in the WordPress admin dashboard.
Click the "Activate" button next to the child theme.
