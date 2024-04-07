# RandomRecipePicker

display random recipe using a GUI Tkinter application, SQLite3 and RecipeDB
<br>
<br>

<br>
<b>author:</b> Saksham Tomar
<br>
<br>
<b> dependencies: </b>

- Tkinter
- Pillow (PIL)
- NumPy
- Pyglet (optional: used for Windows custom fonts)

<b>database webscraped from:</b>
<br>
https://cosylab.iiitd.edu.in/recipedb/
<br>
using MechanicalSoup and SQLite
<br>
<br>

<h2>Project Directories</h2>
the following directories require a detailed overview:

<h3>starter_files</h3>

this directory contains the starter files required to follow my YouTube tutorial.

- 2 logos inside the <b>assets</b> folder
- 2 .ttf fonts inside the <b>fonts</b> folder (downloaded from Google Fonts)
- 1 database file inside the <b>data</b> folder
- 1 .png wireframe inside the root folder.
- 1 .py file inside the root folder containing the most basic commands to run a Tkinter window.

<h3>complete_project_WINDOWS</h3>
<h3>relationalDB_complete_project_WINDOWS</h3>

this directory contains the updated application (January, 2023)
<br>
designed with a relational database rather than the database that was shown in the YouTube tutorial.
<br>
recipes.db now contains 2 tables:

- recipes (includes a primary_key column)
- ingredients (foreign key: recipe_key)

as a result, 2 functions were slightly modified:

- fetch_db()
- pre_process(recipe_name, table_records)

![app](https://user-images.githubusercontent.com/32107652/173865003-09df9a23-6c5e-44f5-9a9e-9b95b93a237c.png)
