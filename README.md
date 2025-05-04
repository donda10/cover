#  Book Front Cover Page Design
## Date:
9-12-2024

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
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Cool Book Cover</title>
  <link rel="stylesheet" href="book.css">
</head>
<body>
  <div class="book-cover-container">
    <div class="book-cover">
      <!-- Background -->
      <div class="background-image"></div>

      <!-- Overlaid Graphics -->
      <div class="overlay"></div>

      <!-- Title Section -->
      <div class="cover-content">
        <h1 class="title">Mastering<br><span>Computer Science</span></h1>
        <p class="author">by Simon Malachi</p>
      </div>

      <!-- Highlight Bar -->
      <div class="highlight-bar">Exclusive Edition</div>

      <!-- Author Image Section -->
      <div class="author-image">
        <img src="WhatsApp Image 2024-12-09 at 23.31.10.jpeg" alt="Author Image">
      </div>

      <!-- Footer Section -->
      <div class="cover-footer">
        <p>Learn, Innovate, Succeed</p>
      </div>
    </div>
  </div>
</body>
</html>


CSS
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
  }
  
  body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    background-color: #121212;
    font-family: 'Arial', sans-serif;
  }
  
  /* Book Cover Container */
  .book-cover-container {
    display: flex;
    justify-content: center;
    align-items: center;
  }
  
  .book-cover {
    position: relative;
    width: 400px;
    height: 600px;
    border-radius: 10px;
    overflow: hidden;
    background-color: #202020;
    box-shadow: 0px 10px 25px rgba(0, 0, 0, 0.5);
  }
  
  /* Background Image */
  .background-image {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background-image: url('HD-wallpaper-chipp-circuit-computer-electronics-information-led-man-retro-science-tech-technology.jpg'); /* Replace with your image */
    background-size: cover;
    background-position: center;
    opacity: 0.5; /* Dimmed to enhance text visibility */
  }
  
  /* Overlay for Gradient Effect */
  .overlay {
    position: absolute;
    top: 0;
    left: 0;
    width: 100%;
    height: 100%;
    background: linear-gradient(to bottom, rgba(0, 0, 0, 0.7), rgba(0, 0, 0, 0.9));
    z-index: 1;
  }
  
  /* Title Section */
  .cover-content {
    position: absolute;
    top: 30%;
    left: 10%;
    z-index: 2;
    color: #fff;
  }
  
  .title {
    font-size: 40px;
    font-weight: bold;
    line-height: 1.2;
    text-transform: uppercase;
  }
  
  .title span {
    color: #00b4d8; /* Highlighted text color */
  }
  
  .author {
    margin-top: 10px;
    font-size: 18px;
    font-style: italic;
    color: #ccc;
  }
  
  /* Highlight Bar */
  .highlight-bar {
    position: absolute;
    top: 10%;
    right: 0;
    background-color: #00b4d8;
    color: #fff;
    font-size: 14px;
    text-transform: uppercase;
    padding: 10px 20px;
    transform: rotate(45deg);
    transform-origin: top right;
    z-index: 2;
  }
  
  /* Author Image */
  .author-image {
    position: absolute;
    bottom: 10%;
    right: 10%;
    width: 100px;
    height: 100px;
    border-radius: 50%;
    overflow: hidden;
    border: 4px solid #00b4d8; /* Highlight border to match theme */
    box-shadow: 0 4px 15px rgba(0, 0, 0, 0.5);
    z-index: 2;
  }
  
  .author-image img {
    width: 100%;
    height: 100%;
    object-fit: cover;
  }
  
  /* Footer Section */
  .cover-footer {
    position: absolute;
    bottom: 20px;
    width: 100%;
    text-align: center;
    z-index: 2;
    color: #fff;
    font-size: 16px;
    text-transform: uppercase;
    font-weight: bold;
    letter-spacing: 1px;
    background-color: rgba(0, 0, 0, 0.5);
    padding: 10px 0;
  }
  

```


## OUTPUT:
![alt text](<Screenshot (20)-1.png>)


## RESULT:
The program for designing book front cover page using HTML and CSS is completed successfully.
