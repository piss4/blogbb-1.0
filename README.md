# Info
BlogBB is an open source blog software written in PHP. It's easy to get started with BlogBB! (see below)

[See a demo](http://blogsoftware.rf.gd/demo/)

# Credit
Scott (piss#6669) - i did everything lol

Credit to some people in the lesbian anime girls ONLY gc for helping me test. (I'm mainly just talking about Relephonus).
# Getting Started
How to get started with BlogBB.

## Installation
#### How to install BlogBB
Connect your FTP Client to your site's FTP server.

Upload all BlogBB files to the site.

## Setup
#### How to set up the database
Once you finish uploading the files, take the ```database.sql``` file and import it into your database.

Then, get your database credentials and edit ```config.php``` to match them.

#### URL
Once you've finished setting up the database, go to the ```info``` table of the database and edit the URL column to your site's URL (with trailing slash). Example: http://example.com/ (you can edit the site's URL from the admin panel later on).

#### Administration
Default admin panel login:
```
Username: Admin
Password: BlogBB Admin
```
You can change this by creating your own password with ```.htaccess```. CPanel has the ability to create one for you. If you don't want to use a password, you can always rename the admin directory and remove the ```.htaccess``` files. (Not recommended)

---

# License

[MIT License](https://choosealicense.com/licenses/mit/)

Copyright (c) 2021 BlogBB Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.