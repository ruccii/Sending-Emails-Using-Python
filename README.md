# Sending-Emails-Using-Python

A Python Script which we can use to send emails to our friends.

## Install the Email package: from [pypi](https://pypi.org/project/emails/)
- !pip install emails
- Import emails 

## Temp Mails:
- For real time reference purpose we have used temporary mails available to test our email sender [temp mail](https://temp-mail.org/en/)

## HTML text:
- we have used [link](https://wordtohtml.net/) to convert our normal to html for email message writing with required fonts,alignmnt and size etc.

## Setting up path:
### How to install and write python codes?
- Go to www.python.org
- Choose the latest python version suitable for your user interface  machine (mac,windows,liinux etc).
- It will be installed and in your machines as either terminal or command line or python.
- To check python is installed or not , Type print command in command line & check the output. While other easier way of checking is using anaconda as described below.
- Other way of using python is using google colab (Go to Google colab in google) and run python using your machine (including mobile phones).

### Anaconda:  
- Go to  www.anacond.com  & download.
- It is like a  bundle that is downloaded with python and along with famous libraries. It is preferred by most data scientists.
- Find anaconda navigator in your machine and open it. You will find different visualizing tools like jupyter lab, jupyter notebook, spyder, orange3, vs code, rstudio, vs code. We need this bundle for jupyter notebook.

### Jupyter NoteBook: 
- It is a web-based interactive portal that allows us to give input and see the output then and there in a clean and clear manner.
- How to start programming in Jupyter NoteBook:-
   - Step1: Open Anaconda navigator and select Jupyter NoteBook & click launch.
   - Step2: Create a new folder and rename it.
   - Step3: Go inside the folder and go into new options and select python 3.
   - Step4: Name the python notebook.
   - Step5: Type the code in the cell. And to run the code press shift+enter
 
 ## Modules & Packages:
- Modules are nothing but a file (with .py extension) which we can import into a particular program
- Group of modules(python files) is known as package 
### Pypi.org :
- pypi.org is a website where we all can get different libraries which we can use for a different purpose.
- How to install a library from pypi.org
   - Go to pypi.org.
   - Search for a library according to your need.
   - Copy the text which says “pip install library name”.
   - In Jupyter notebook type “!” and paste the content and run the cell.
   - The library is installed on the local machine
### How to create our module:
   - Modules are created using a special keyword which is only for Jupyter notebook and Google Colab.
   - Create a module by
       - %%writefile ModuleName.py
       - #And write a python code
   - Import the module in another program and use the functions inside the module
      - import ModuleName
      - ModuleName.FunctionName()
### How to create Package:
- Make a folder and rename it(That is your package name)
- Now we can import a module through the package, like
   - from packageName import moduleName
## Reference:
- [Emails](https://www.tutorialspoint.com/python/python_sending_email.htm)
- [Letsupgrade python essentials](https://community.letsupgrade.in/group/python)
