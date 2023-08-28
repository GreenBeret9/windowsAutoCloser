# windowsAutoCloser\
IMPORTANT TO DO FIRST:\
Download, install and add Python to environnment variables:\
here's a quick 2min video on how to do that:\
https://www.youtube.com/watch?v=6mP1bf03xz0&t=63s&ab_channel=TheTechFlow


for tesseract do the following:\
1. Install tesseract using windows installer available at: https://github.com/UB-Mannheim/tesseract/wiki\
2. add the installation folder path to the environment variable:\
here's a 3min video on how to do that:\
https://www.youtube.com/watch?v=RewxjHw8310&t=147s&ab_channel=AdityaPaiThon\

3. open cmd and run "pip install pytesseract"

to run the project, first open cmd then go to your script folder with "cd path/to/the/script/folder"

set up your virtual environement:
python -m venv venv

then activate it:
For Windows run ".\venv\Scripts\activate"
run "source venv/bin/activate" (not for windows)


4. pip install -r requirements.txt

run "python windowsAutoCloser.py"

NOTE: by default, the name of windows to be scanned must start with "Roblox", the scan will automatically be done
after every 15min (900 seconds), and the windows to be closed need to have these error codes 
["277", "268", "264", "529", "279", "266", "267", "279"] preceded by the string "Error Code: ":
there's a process time of 0.5 seconds for each window.

if you wish to have a different setting, then open the main.py file, and at the top you will find the parameters, update accordingly.

dm green.beret (discord) for issues 



