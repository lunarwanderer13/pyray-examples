# Pyray example features

## What is pyray?
[Pyray](https://github.com/electronstudio/raylib-python-cffi)
is a Python library containing bindings for the C
[Raylib](https://github.com/raysan5/raylib) library.

## Why pyray?
Pyray is one of the easiest to use Python raylib bindings library, and Python is way easier to use than C for new developers.  
Of course, one can use the original raylib with C, and it won't look much different, but new developers might face more difficulties.

## How to test/run/see the examples?

Make sure you have Python 3.14.5 (or newer) installed!  

Clone the GitHub repo:  
`https://github.com/lunarwanderer13/pyray-examples.git`  

`cd` into the project:  
`cd pyray-examples`  

Create a Python virtual environment:  
`python -m venv .venv`

Activate the Python virtual environment:  

Linux/macOS:  
`source .venv/bin/activate`  

Windows:  
`.venv\Scripts\activate`  

(one can later exit out of the virtual environment using the `deactivate` command)  

Install the required libraries:  
`pip install -r requirements.txt`

Run the chosen example:  
`python examples/<example>/main.py`, where &lt;example&gt; is the chosen example name.  