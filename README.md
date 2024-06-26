# Ex.06 Book Front Cover Page Design
## Date:

## AIM:
To design a book front cover page using HTML and CSS.

## DESIGN STEPS:

### Step 1:
Create a Django Admin project.

### Step 2:
Create an app in the Django interface.

### Step 3:
Create a folder named 'static' in the app folder.

### Step 4:
Create a new HTML file in the static folder.

### Step 5:
Write the HTML code with relevant CSS properties.

### Step 6:
Choose the appropriate style and color scheme.

### Step 7:
Insert the images in their appropriate places.

### Step 8:
Publish the website in the LocalHost.

## PROGRAM:
### html
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Book Cover Page</title>
    <style>
        .bookpage {
            width: 400px;
            height: 600px;
            color: rgba(243, 195, 195, 0.938);
            margin: 0 auto;
            padding: 20px;
            font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
            background-image: url(img.jpg);
            background-size: cover;
        }

        .insight {
            color: rgb(186, 41, 41);
        }

        .hrstyle {
            width: 100px;
        }

        .author {
            display: inline;
            color: rgb(228, 38, 38);
            font-family: Georgia;
            font-size: medium;
            position: relative;
            top: 180px;
            left: 270px;
        }

        .booktitle {
            font-family: 'Courier New', Courier, monospace;
            font-size: larger;
            text-align: center;
            color: aqua;
        }

        .id {
            width: 400px;
            position: relative;
            top: 230px;
        }

        .pub {
            font-size: medium;
            color: blanchedalmond;
            position: relative;
            top: 200px;
        }

        .ed {
            color: rgb(231, 153, 153);
            font-size: medium;
            font-family: Verdana;
            position: relative;
            top: 200px;
        }

        .subtitle {
            font-family: Tahoma;
            font-size: large;
            text-align: center;
            color: aqua;
        }

        .mypic {
            width: 100px;
            height: 100px;
            background-size: cover;
            position: relative;
            top: 150px;
            left: 250px;
        }
    </style>
</head>
<body>
<div class="bookpage">
    <div class="insight">
        SEC SERIES
    </div>
    <div class="hrstyle">
        <hr style="color: rgb(128, 128, 96);">
    </div>
    <div class="booktitle">
        <h1>Fundamentals of Ethical Hacking</h1>
    </div>
    <div class="subtitle">
        The complete guide to Ethical Hacking
    </div>
    <div class="mypic">
        <img src="aa.JPG" width="130" height="145" alt="">
    </div>
    <div class="id">
        <hr style="color: rgb(145, 145, 114);">
    </div>
    <div class="author">
        <p><b>JOTHISH E</b></p>
    </div>
    <div class="pub">
        SEC
    </div>
    <div class="ed">
        <b>Extended version</b>
    </div>
</div>
</body>
</html>
```

## OUTPUT:
![alt text](<Screenshot (33).png>)

## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
