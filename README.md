# Gallery yangu

#### 14 11 2020
By Dennis K. Mutai

## Overall Project Description
Gallery yangu is a personal gallery application that displays photos for others to see.

## User stories
<ol>
    <li>A user can view different photos that interest them.</li>
    <li>A user can click on a single photo to expand it and also view the details of the photo. </li>
    <li>A user can search for different categories of photos.</li>
    <li>A user can copy a link to the photo to share with their friends.</li>
    <li>A user can view photos based on the location they were taken.</li>

</ol>


## Setup/Installation Requirements
* Python version 3
* pip
* Django
* Django-bootstrap4
* Heroku
* Gunicorn
* Internet connection

## Installation Process
<ol>
    <li>Navigate to https://github.com/DennisKipkirui/Gallery-yangu .</li>
    <li>Clone the project.</li>
    ```https://github.com/DennisKipkirui/Gallery-yangu.git```
    <li>On your machine, open the project folder in your terminal.</li>
    <li>Create a virtual environment</li>
    ```python3 -m venv virtual```
    <li>Activate the virtual environment</li>
    ```source virtual/bin/activate```
    <li>Install the requirements</li>
    ```pip install -r requirements.txt```
    <li>In gallery/settings.py file, ensure that DEBUG=True.</li>
    <li>Run the server</li>
    `python3 manage.py runserver`
</ol>

## Known Bugs
The modal displaying image details appears and disappears immediately making it appear as if it is not present.

## Contact Information
If you need clarification on any aspect, feel free to reach me via email at kipkiruimutai@gmail.com

### License
MIT License [MIT](license.txt)
Copyright (c) 2020 Dennis K. Mutai
