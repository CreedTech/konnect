# NewsGrid - News Portal

## Introduction

Developed an Online News Portal, that allows various users to easily create, read, bookmark news articles.

Technologies used:

- Front end: HTML, CSS, JavaScript, Bootstrap (for Admin Panel only)
- Back end: PHP, MySQL
  <br>

This project aims to develop a computerized and easy to access the day-to-day news without having to wait. “NewsGrid” is aimed at developing such an efficient website that helps in providing up to date news about various happenings around the world.

#### [View Demo]

```
admin Credentials
email: admin@admin.com
password: Adminpass1
```


## Module Description

### Admin Module

- Admin can modify and delete user account and restrict them from entering the logged-in portal of NewsGrid.
- Admin can modify and delete Author account and restricting inactive authors from writing new articles on NewsGrid.
- Admin can add, modify and delete categories under which various articles are written.
- Admin can delete all the News Articles present in the NewsGrid Portal, decides whether the particular article should stay or not.
- Admin manages the Trending section of the portal, chooses which article goes under Trending section and is displayed on carousel
- Admin can manage his account credentials (i.e.) can change password.

<hr style="font-size: 10px;margin: auto;" width="90%" >

### Author Module

- Author can write new articles and post in the NewsGrid portal by selecting the appropriate category in which the article is written and to be displayed.
- Author can modify and delete articles written by him only.
- Author can manage his account credentials (i.e.) can change password & name.

<hr style="font-size: 10px;margin: auto;" width="90%" >

### User Module

- User can browse through NewsGrid website and search for articles under various categories present in the portal.
- User can search for articles based in his preferred categories like Sports, Entertainment, Politics, etc.
- User can search for a particular article based on specific keywords like title of the article or category name, trending.
- User can sort articles date wise and view articles posted on particular date of choice or between a span of days.
- User can also look up the trending articles of the week.
- User can manage his account credentials (i.e.) can change password.

<hr style="font-size: 10px;margin: auto;" width="90%" >


---

## Development setup

#### 1. Clone the project 

```git
 $ git clone https://github.com/CreedTech/konnect.git
```
or download the project via GitHub

#### 2. Move project folder to htdocs folder

if you cannot find the htdocs folder please follow the below links,

- [Where to find htdocs in XAMPP Mac](https://stackoverflow.com/questions/45518021/where-to-find-htdocs-in-xampp-mac)
- [Find htdocs path, no matter where file is stored](https://stackoverflow.com/questions/5536730/find-htdocs-path-no-matter-where-file-is-stored)
- [htdocs path in linux](https://stackoverflow.com/questions/1582851/htdocs-path-in-linux)
- [https://stackoverflow.com/questions/1582851/htdocs-path-in-linux](https://stackoverflow.com/questions/44989243/unable-to-find-htdocs-on-xampp)

#### 3. Restore Database

- Goto phpMyAdmin and create a Database names `news-portal`.
- Now Select Import.
- Find 'File to import:' section and choose the file 'news-portal.sql' which is located under project folder and hit GO.

#### 4.Setup Database Configurations

- Go to project folder -> includes -> database.inc.php.
- Setup your configurations related to MySQL.
  - Eg: Server Name -> `localhost`, MySQL Username -> `root`.

#### 5. Start Server

- Start the server and run http://localhost:8888/Folder_name/index.php (replace the port number 8888 to your port).
- Alternatively you can also run the command on your terminal
  ```terminal
     php -S localhost:8888 (replace the port number to your choice)
  ```
