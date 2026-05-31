This requires Python 3.8 or higher and pip.

1. Install dependencies by running this in your terminal:
```bash
pip install python-pptx
```


The template[.pptx] is important for the script to work. The template has a custom layout (set as the very first layout) that is the name on the left and picture on the right (sized properly). 


Officer notes:

You will find the fall induction slides fairly easy- they will be a low amount of slides you can do by hand. However, the spring induction slides are ~200+ slides, and can be a pain to do by hand. Here are some details for using code instead;


I believe you've used Python before- in any case, it is simple to get started with. You'll need PowerPoint, Python, and a python package (python-pptx). If you run this on your school laptop, you'll need something like VSCode to install dependencies (no terminal access otherwise). (Python is also on company portal if you choose to do this on your school laptop)


The yearbook photos are in a folder, numbered, with a separate txt file to match each photo to a name. Mrs. Tallerico will also explain this to you the first time you meet her. The folder looks like this on google drive:

11/

---11.TXT

---0001.JPG

---0002.JPG

---...

You want to download this folder specifically (and not the entire folder she shares with you). 


Next, download the project files from this repository and place the "11" folder in the same directory as these files, so...


some folder/

---11/

---main.py

---template.pptx


In the same folder, create a file "names.txt". By the time you create the spring induction slides, you will have access to the 27-28 hours tracker. Copy and paste the names (and only the names) from column A in the hours tracker into the names.txt file.


Run the main.py python file (python main.py). The program will create a new presentation "out.pptx" with the completed slides. Pay attention to the console while it is running: it may ask you to manually input some photo file paths. Once you double check the output presentation, you can upload it to Google Slides and share it with the rest of the team and Mr. Tozier.

