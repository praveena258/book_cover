# Ex.06 Book Front Cover Page Design
# Date:22.04.2025
# AIM:
To design a book front cover page using HTML and CSS.

# DESIGN STEPS:
## Step 1:
Create a Django Admin project.

## Step 2:
Create an app in the Django interface.

## Step 3:
Create a folder named 'static' in the app folder.

## Step 4:
Create a new HTML file in the static folder.

## Step 5:
Write the HTML code with relevant CSS properties.

## Step 6:
Choose the appropriate style and color scheme.

## Step 7:
Insert the images in their appropriate places.

## Step 8:
Publish the website in the LocalHost.

# PROGRAM:
```
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Book Cover</title>
  <style>
    body {
      display: flex;
      justify-content: center;
      align-items: center;
      height: 100vh;
      margin: 0;
      background-color: #f0f0f0;
      font-family: 'Segoe UI', sans-serif;
    }

    .book-cover {
      width: 400px;
      height: 500px;
      color: white;
      padding: 30px 20px;
      box-shadow:#3a3a3a;
      border-radius: 16px;
      display: flex;
      flex-direction: column;
      background-image:url("images.jpeg");
      justify-content: space-between;
    }

    .book-title {
      font-size: 28px;
      font-weight: bold;
      align-content: center;
      text-align: center;
    }

    .book-author {
      font-size: 18px;
      margin-top: 10px;
      font-style: italic;
      text-align: right;
    }

    .book-footer {
      font-size: 14px;
      text-align: right;
    }
    .book-image{
      max-width: 300px;
      max-height: 400px;
      align-self: center;
      margin: 10 auto;
      border-radius: 50%;
      margin-bottom: 50px;
    }
  </style>
</head>
<body>

  <div class="book-cover">
    <div>
      <img src="LILY.png" class="book-image"/>
      <div class="book-title">LORD OF THE FLIES</div>
      <div class="book-author">william golding</div>
    </div>
    <div class="book-footer">2025 Edition</div>
  </div>
</body>
</html>

```
# OUTPUT:
![alt text](<Screenshot 2025-04-22 113917.png>)
# RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
