# Ex.06 Book Front Cover Page Design
## Date: 25/12/2025

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
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Book Cover Page</title>

    <style>
        body {
            margin: 0;
            padding: 0;
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            background-color: #e6e6e6;
            font-family: Arial, Helvetica, sans-serif;
        }

        .cover {
            width: 420px;
            height: 600px;
            background: linear-gradient(160deg, #ff3c1f, #ff6a3d);
            color: white;
            padding: 30px 25px;
            box-sizing: border-box;
            position: relative;
        }

        .header {
            font-size: 14px;
            letter-spacing: 1px;
            font-weight: bold;
        }

        .line {
            width: 60px;
            height: 2px;
            background-color: white;
            margin: 8px 0 40px 0;
        }

        .title {
            font-size: 34px;
            font-weight: bold;
            line-height: 1.2;
        }

        .subtitle {
            margin-top: 15px;
            font-size: 16px;
        }

        .edition {
            position: absolute;
            bottom: 120px;
            left: 25px;
            font-size: 14px;
            font-weight: bold;
        }

        .author {
            position: absolute;
            bottom: 50px;
            left: 25px;
            font-size: 15px;
            font-weight: bold;
        }

        .sec {
            position: absolute;
            bottom: 50px;
            right: 25px;
            font-size: 15px;
            font-weight: bold;
        }

        .photo {
            position: absolute;
            bottom: 80px;
            right: 25px;
            width: 90px;
            height: 110px;
            background-color: white;
            padding: 4px;
            box-sizing: border-box;
        }

        .photo img {
            width: 100%;
            height: 100%;
            object-fit: cover;
        }
    </style>
</head>
<body>

<div class="cover">
    <div class="header">SEC INSIGHT</div>
    <div class="line"></div>

    <div class="title">
        Web Development:<br>
        The Complete<br>
        Reference
    </div>

    <div class="subtitle">
        with Django and Bootstrap Insights
    </div>

    <div class="edition">Extended Edition</div>

    <div class="photo">
        <!-- Replace photo.jpg with actual image file -->
        <img src="1.jpg" alt="Author Photo">
    </div>

    <div class="author">Vishva S</div>
    <div class="sec">SEC</div>
</div>

</body>
</html>
```

## OUTPUT:
<img width="535" height="718" alt="image" src="https://github.com/user-attachments/assets/cc6c616d-85aa-4f85-a5c2-650254f97a7b" />




## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
