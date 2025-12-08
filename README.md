# Ex.06 Book Front Cover Page Design
## Date: 6.12.2025

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
<!DOCTYPE html>
<html>
<head>
    <title>Book Cover</title>

    <style>
        body {
            background-color: #f2f2f2;
            font-family: Arial;
            margin: 0;
            padding: 0;
        }

        .mainbox {
            width: 600px;
            margin: 40px auto;
            background: blue;
            padding: 25px;
            border: 2px solid black;
            border-radius: 10px;
        }

        .hrstyle hr {
            border: 2px solid black;
        }

        .booktitle h1 {
            text-align: center;
            color: goldenrod;
        }

        .subtitle {
            text-align: center;
            font-size: 18px;
            font-style: italic;
            margin-bottom: 15px;
        }

        .mypic {
            text-align: right;
            margin: 10px 0;
        }

        .mypic img {
            border: 2px solid black;
            border-radius: 6px;
        }

        .author {
            text-align: left;
            font-size: 20px;
            margin-top: 10px;
        }

        .pub, .ed {
            text-align: left;
            margin-top: 8px;
            font-size: 18px;
            font-weight: bold;
        }
    </style>
</head>

<body>

<div class="mainbox">

    <div class="hrstyle">
        <hr>
    </div>

    <div class="booktitle">
        <h1>WEB Development: The Complete Reference</h1>
    </div>

    <div class="subtitle">
        with Django and Bootstrap Insights
    </div>

    <div class="mypic">
        <img src="MyPhoto.jpg" width="130" height="145" alt="">
    </div>

    <div class="author">
        <p><b>Dhanalakshmi chandrasekaran</b></p>
    </div>

    <div class="pub">
        SEC
    </div>

    <div class="ed">
        <b>Extended Edition</b>
    </div>

    <div class="hrstyle">
        <hr>
    </div>

</div>

</body>
</html>

```





## OUTPUT:
<img width="813" height="632" alt="Screenshot 2025-12-08 081008" src="https://github.com/user-attachments/assets/9cabe588-2f74-414f-a927-88c4f4c004f4" />




## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
