# windowsAutoCloser
IMPORTANT TO DO FIRST:

Download, install and add Python to environnment variables:

    here's a quick 2min video on how to do that:
    https://www.youtube.com/watch?v=6mP1bf03xz0&t=63s&ab_channel=TheTechFlow


SECOND IMPORTANT TO DO:
1. Install tesseract using Windows installer available at: https://github.com/UB-Mannheim/tesseract/wiki

2. add the installation folder path to the environment variable:

    here's a 3min video on how to do that:
    https://www.youtube.com/watch?v=RewxjHw8310&t=147s&ab_channel=AdityaPaiThon\

3. open cmd and run "pip install pytesseract"

# run the project
1. open cmd then go to your script folder with "cd path/to/the/script/folder"


2. set up your virtual environement:

    run "python -m venv venv"


3. activate it :

    (for Windows) run: ".\venv\Scripts\activate"

    (for Linux) run:  "source venv/bin/activate" 


4. pip install -r requirements.txt


5. run "python windowsAutoCloser.py"

   (you should be able to just double click the 2nd time you want to run it without the need for cmd)

NOTE: by default, the name of windows to be scanned must start with "Roblox", the scan will automatically be done
after every 15min (900 seconds), and the windows to be closed need to have these error codes 
["277", "268", "264", "529", "279", "266", "267", "279"] preceded by the string "Error Code: ":
there's a process time of 0.5 seconds for each window.

if you wish to have a different setting, then open the windowsAutoCloser.py file with Notepad, and at the top you will find the parameters, update accordingly.
save the file and rerun.

dm green.beret (discord) for issues 
