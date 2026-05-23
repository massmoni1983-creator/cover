# Ex.05 Book Front Cover Page Design
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
```
<!DOCTYPE html>
<html>
<head>
    <title>Book Cover Page</title>

    <style>

        body{
            margin:0;
            height:100vh;
            display:flex;
            justify-content:center;
            align-items:center;
            background:#e5e5e5;
            font-family:Arial, Helvetica, sans-serif;
        }

        .cover{
            width:420px;
            height:700px;
            background-image:url("back.png");
            background-size:cover;
            background-position:center;
            position:relative;
            color:white;
            border:5px solid #8d8585;
            border-radius:5px;
            overflow:hidden;
            box-shadow:5px 5px 20px black;
        }

        .overlay{
            width:100%;
            height:100%;
            background:rgba(0,0,0,0.45);
            padding:20px;
            box-sizing:border-box;
        }

        .top{
            font-size:18px;
            font-weight:bold;
        }

        .line{
            width:100px;
            border:1px solid white;
            margin-top:8px;
        }

        h1{
            text-align:center;
            margin-top:70px;
            font-size:34px;
            line-height:58px;
            letter-spacing:1px;
            font-family:Georgia, serif;
        }

        .subtitle{
            margin-top:55px;
            font-size:16px;
            line-height:30px;
            width:70%;
        }

        .photo{
            position:absolute;
            right:25px;
            bottom:120px;
            width:115px;
            height:145px;
            border:4px solid #d8d1c7;
            object-fit:cover;
        }

        .bottom{
            position:absolute;
            bottom:20px;
            left:20px;
            right:20px;
        }

        .release{
            font-size:17px;
            font-weight:bold;
        }

        .bottomline{
            border:1px solid white;
            margin-top:8px;
            margin-bottom:10px;
        }

        .author{
            font-size:17px;
            font-weight:bold;
            float:left;
        }

        .logo{
            float:right;
            font-size:17px;
            font-weight:bold;
        }

    </style>
</head>

<body>

    <div class="cover">

        <div class="overlay">

            <div class="top">
                WEB DEVELOPING SKILLS
            </div>

            <div class="line"></div>

            <h1>
                FRONT END<br>
                BACK END<br>
                AND DATABASE<br>
            </h1>

            <div class="subtitle">
                LEARNING THE BASIC 
                WEB DEVELOPMENT SKILLS TO 
                IMPROVE YOUR SKILLS IN CODING
                AND PERFORM CHALLENGING 
                TASKS IN HACKATHONS
            </div>

            <img src="photo.png" class="photo">

            <div class="bottom">

                <div class="release">
                    LIMITED STOCKS
                </div>

                <div class="bottomline"></div>

                <div class="author">
                    MURUGA
                </div>

                <div class="logo">
                    SEC
                </div>

            </div>

        </div>

    </div>

</body>
</html>
```

## OUTPUT:
<img width="949" height="947" alt="Screenshot 2026-05-24 004843" src="https://github.com/user-attachments/assets/6c419d51-5e15-427a-b4f5-9a703b5b9899" />


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
