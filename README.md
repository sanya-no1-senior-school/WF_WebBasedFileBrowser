
# WF FileBrowser
![python](https://img.shields.io/badge/Python-3.5+-green.svg)
![build](https://img.shields.io/badge/build-passed-green.svg)
![FrameWork](https://img.shields.io/badge/Django-2.0+-green.svg)   
A user-friendly install easily WebBased File Browser programed with Python Django with Material Design Interface.   
English | [中文文档](./README/README_CN.md)
--------

Contact me | 
--------- |
DaiQiang: daiqianghaha@foxmail.com | 


## Login
![login](./README/login.png "Login") 
## File Preview
![preview](./README/login.png "File Preview")
## Drag to move or copy files
![drag](./README/login.png "Drag to move or copy files")
## Quickly rename files
![rename](./README/login.png "quickly rename")


# Advantage
* Quick configuration, one-click deployment, start the project immediately, python interpret runs without compiling.
* CSRF token authentication technology to prevent cross-site request forgery (CSRF) attacks.
* Asynchronous dynamic loading technology, can instantly render tens of thousands of files.
* File preview function Quickly view text files, project codes, and image files in various formats.
* Multi-file fast compression to zip for downloading.
* Customizable background image and other styles you love.

# Installation Guide
1. Download all files of the project
2. Run command in shell(Linux) cmd or powershell(windows)
  `pip install Django`
  If both python3 and python2 are installed in your PC, please run
     `pip3 install Django`

3. Modify `userdata.conf` in the app directory to configure the username and password.
Modify  `rootpath.conf` configuration in the app directory to configure your path which you want to manage files with WF file Browser.
4. Run command in shell(Linux) cmd or powershell(windows) to start the server
`python3 manage.py runserver 0.0.0.0:5210`

0.0.0.0 and 5210 can be replaced with custom IPs and ports when you needed

5. Web Browser access to 0.0.0.0:5201 to manage files