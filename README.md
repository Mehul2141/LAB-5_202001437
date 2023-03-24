# LAB-5_202001437
Static Analysis Tool : pylint
<br>
Git repository used : https://github.com/Snivyc/flask-books-management-system
<br>
Language : python
<br>
<h2>1. config.py</h2>
<br>
<img src="https://user-images.githubusercontent.com/91714235/227482964-af89b2b7-1237-474e-82e9-754fb0c6e518.png"></img>
<br>
<br>
<strong>ERROR EXPLANATION</strong> : 
final newline missing,This particular error is common if you forget to append a newline character to the end of your python script.there is no class docstring in this computer so it shows error missing class docstring.
<br>
<br>

<h2>2. manage.py</h2>
<br>

<img src="https://user-images.githubusercontent.com/91714235/227483042-8d6bd859-fabf-453f-82b2-0ff7382d585f.png"></img>
<br>
<br>
<strong>ERROR EXPLANATION</strong> : 
unable to import 'flask_script' ,The imported class is unavailable.
<br>
<br>

<h2>3. print.py</h2>
<br>

<img src="https://user-images.githubusercontent.com/91714235/227483097-13efa6ae-f497-4f0f-87f0-d9adad7152dd.png"></img>
<br>
<br>
<strong>ERROR EXPLANATION</strong> : 
same as 1.
<br>
<br>

<h2>4. resettingsql.py</h2>
<br>
<img src="https://user-images.githubusercontent.com/91714235/227483157-4c45917e-c9d5-4fbd-bf06-7bd1ef370549.png"></img>
<br>
<br>
<strong>ERROR EXPLANATION</strong> : 
it shows line too long because line is longer than 80 chars.it shows constant name doesn't conform to upper_case Because of Python's PEP rules, you must use capital letters in variable names.
<br>
