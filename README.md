
## Django Requires Python

To check if your system has Python installed, run this command in the command prompt:

```bash
  python --version
```
If Python is installed, you will get a result with the version number, like this:    

```bash
  Python 3.11.1
```

## PIP

To check if your system has PIP installed, run this command in the command prompt:

```bash
  pip --version
```
For me, on a windows machine, the result looks like this:    

```bash
  pip 22.3.1 from F:\Download all Folder\WINDOWS FILE\Python\Lib\site-packages\pip (python 3.11)
```
## Create Virtual Environment

Type the following in the command prompt, remember to navigate to where you want to create your project:

Windows:

```bash
  py -m venv myworld
```

Unix/MacOS:

```bash
  python -m venv myworld
```

Then you have to activate the environment, by typing this command:

Windows:

```bash
  ProjectName\Scripts\activate.bat
```

Unix/MacOS:

```bash
  source ProjectName/bin/activate
```


Once the environment is activated, you will see this result in the command prompt:

Windows:

```bash
  (ProjectName) C:\Users\Your Name>
```

Unix/MacOS:

```bash
  (ProjectName) ... $
```

## Install Django

Django is installed using pip, with this command:


 Windows:

```bash
  py -m pip install Django
```

Unix/MacOS:

```bash
  python -m pip install Django
```


## Check Django Version

You can check if Django is installed by asking for its version number like this:


```bash
  django-admin --version
```


```bash
  4.1.6
```

## Django Create Project

First Project :


```bash
  django-admin startproject my_tennis_club
```

Run the Django Project :

```bash
  py manage.py runserver
```
