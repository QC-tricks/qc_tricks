# qc_tricks
A collection of mathematical tricks within quantum chemistry

Have you ever come across "trivial manipulations" or "side notes" that are
essential in a derivation but don't look trivial the first time you see them?
Here we collect tricks used in quantum chemistry and why they work for
our own future reference and courses taught.

You are welcome to contribute!

What to contribute: Everything you stumbled over and spent time on solving.

How to contribute:
 - Fork the repository and work in your own fork
 - For each trick make a new file which holds all the information
   about the trick. It should look like this:
   
   ```
   \subsection{title}
   methods: {list methods in which the trick is used separated by commas}\\
   courses: {list of courses the trick is used in}\\
   
   Explanation when and why this trick is relevant

   \begin{align}
    equations explaining the trick in detail
   \end{align}
   
   Explanation why it works

   \vspace{0.5cm}
   used in: {DOI1 (equation number(s)), DOI2 (equation number(s))}
   ```
   
 - If you want to use pictures, make them locally and add the pdf, jpg
   or png to a reasonable place in the pics folder.
 - \input the file in the main file master.tex in a fitting section
 - commit your changes 
 - merge the main repository into your fork
 - file a pull request to get your changes incorporated in the main branch
 
 Enjoy the collection :-)
 
 The plan is to move the tricks into a database at a later time, but for the moment the project
 going to be a single latex file.
  
