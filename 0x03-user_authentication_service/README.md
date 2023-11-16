# 0x03-user_authentication_service

In the industry, you should not implement your own authentication system and use a module or framework that doing it for you (like in Python-Flask: [Flask-User](https://flask-user.readthedocs.io/en/latest/)). Here, for the learning purpose, we will walk through each step of this mechanism to understand it by doing.

# Resources

## Read or watch:

1. [Flask documentation](https://flask.palletsprojects.com/en/1.1.x/quickstart/)
2. [Requests module](https://requests.kennethreitz.org/en/latest/user/quickstart/)
3. [HTTP status codes](https://www.w3.org/Protocols/rfc2616/rfc2616-sec10.html)

## Learning Objectives

At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

1. How to declare API routes in a Flask app
2. How to get and set cookies
3. How to retrieve request form data
4. How to return various HTTP status codes

## Requirements

1. Allowed editors: `vi`, `vim`, `emacs`
2. All your files will be interpreted/compiled on Ubuntu 18.04 LTS using `python3` (version 3.7)
3. All your files should end with a new line
4. The first line of all your files should be exactly `#!/usr/bin/env python3`
5. A `README.md` file, at the root of the folder of the project, is mandatory
6. Your code should use the `pycodestyle` style (version 2.5)
7. You should use `SQLAlchemy` 1.3.x
8. All your files must be executable
9. The length of your files will be tested using `wc`
10. All your modules should have a documentation (`python3 -c 'print(__import__("my_module").__doc__)'`)
11. All your classes should have a documentation (`python3 -c 'print(__import__("my_module").MyClass.__doc__)'`)
12. All your functions (inside and outside a class) should have a documentation (`python3 -c 'print(__import__("my_module").my_function.__doc__)'` and `python3 -c 'print(__import__("my_module").MyClass.my_function.__doc__)'`)
13. A documentation is not a simple word, it’s a real sentence explaining what’s the purpose of the module, class or method (the length of it will be verified)
14. All your functions should be type annotated
15. The flask app should only interact with `Auth` and never with `DB` directly.
16. Only public methods of `Auth` and `DB` should be used outside these classes

## Setup

You will need to install `bcrypt`

```pip3 install bcrypt```
