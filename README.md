# Lecture 01: MVC Introduction

## Installation Instructions

For this course, we will use Visual Studio Code.

- https://code.visualstudio.com/

Then, we will use XAMPP. You can download it here:

- https://sourceforge.net/projects/xampp/files/XAMPP%20Windows/7.4.33/xampp-windows-x64-7.4.33-0-VC15-installer.exe/download

## Recap

Recap on basic knowledge of Web Application

![Alt text](/images/image.png)

## How MVC works

- `Model` - manages data and application logic
- `View` - presentation layer
- `Controller` - converts the input into commands ans send them to the View or Model

![Alt text](/images/image-1.png)

## How to use XAMPP

To launch the website with XAMPP, you will need to create a folder in the directory below. Make sure to locate the directory in your computer

```bash
C:\xampp\htdocs
```

In this case, I will create the folder `mvc-introduction`

![Alt text](/images/image-2.png)

Then, I will put the source code to this folder

![Alt text](/images/image-3.png)

After that, launch `XAMPP` and start the `Apache` server and `MySQL` server

![Alt text](/images/image-4.png)

After that, go to the URL `http://localhost/phpmyadmin/` to launch `phpMyadmin`

![Alt text](/images/image-5.png)

Then, we will create the database `php_mvc_demo` for the web application

![Alt text](/images/image-6.png)

![Alt text](/images/image-7.png)

Then, we will create the table to store the data

![Alt text](/images/image-8.png)

![Alt text](/images/image-11.png)

After that, go to the URL `http://localhost/mvc-introduction/` to see the web application

![Alt text](/images/image-10.png)
