 #  Inta-clone
---------------------------------------------------------------------------
## Developed by [Mishael Ndegwa](https://github.com/mishael254)
---------------------------------------------------------------------------
## DESCRIPTION
This is a web application built using django framework that allows users to view images; the images are filtered using title,categories and tagged location. The app also allows the users to like and comment on the uploaded photos .

#### [Link to live site]()

## USER STORIES
A user is able to :

* Sign in to the application to start using.
* Upload my pictures to the application.
* See my profile with all my pictures.
* Follow other users and see their pictures on my timeline.
* Like a picture and leave a comment on it.

The web application is accessible to users of both desktop and mobile formats: reponsivity for different screens is therefore enabled

The application is thoroughly tested and has implemented various error handlers to prevent the application from crashing.

The link to the images posted on the application can be gotten by clicking the COPY IMAGE LINK in the modal displayed on clicking an image.

## PROJECT SPECIFICATIONS
| Behaviour | Input | Output |
| :---------------- | :---------------: | ------------------: |
| Admin Authentication | **On demand** | Access Admin dashboard |
| Display all images | **Home page** | Clickable links to open any images in a modal |
| Display single images on click | **On  click** | All details should be viewed|
| To add an image  | **Through Admin dashboard** | Add image and add categories and tag location of Image|
| To edit image  | **Through Admin dashboard** | Redirected to the  image form details and editing happens|
| To delete an image  | **Through Admin dashboard ** | click on image object and confirm by delete button|
| To search  | **Enter text in search bar** | Users can search by category|
| To filter by Location  | **Click drop-down on navbar** | Users can view images by Location|
| To like an image |  | Users can like various photos|
| To comment on a photo  |  | Users can comment on images by Location|
| To follow other users  |  | Users can view other users and follow them |

--------------------------------------------------------------------------
## SETUP / INSTALLATION

### PREREQUISITES
* Python 3.8
* Virtualenv
* Good code editor
* Bash / Terminal
* Programming knowledge (any level)
* Internet connection

--------------------------------------------------------------------------
### ACQUIRING PROJECT
> CLONING

> DOWNLOAD ZIP
---------------------------------------------------------------------------
#### CLONING PROJECT
* Open terminal and type:

         $ git clone https://github.com/mishael254/insta-clone

        $ cd insta-clone

* OR download zip file to your laptop / computer
    
         $ Clone Or Download button (green)

## RUNNING APPLICATION
* Install virtual environment

        $ python3.8 -m venv --without-pip virtual

        $ source virtual/bin/activate

        $ curl https://bootstrap.pypa.io/get-pip.py | python

* Install Django and its dependencies

        $ pip3 install django

        $ pip install django

        $ pip install -r requirements.txt

* Run application

        $ python3.8 manage.py runserver

## TESTING THE APPLICATION
* To run the tests for the class models:

        $ python3.8 manage.py test intaclone

--------------------------------------------------------------------------
## TECHNOLOGIES USED
* Python3.8

* MDBootstrap

* Postgresql

* Django

* Heroku

* JQuery && JavaScript

---------------------------------------------------------------------------
## LICENSE

Copyright (c) 2020 - [Mishael-Ndegwa]

---------------------------------------------------------------------
Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.