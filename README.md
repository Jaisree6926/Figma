# Ex09 Event Registration Web Application
## Date:6.11.2025

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
```
1.html


<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="iphone-16-1-1">
<div class="rectangle-1-2"></div>
<div class="rectangle-2-3"></div>
<p class="text-4"><span class="text-white">Username:</span></p>
<div class="rectangle-3-5"></div>
<p class="text-6"><span class="text-white">password: </span></p>
<p class="text-7"><span class="text-rgb-15-63-100">Register </span></p>
<p class="text-8"><span class="text-white">DRESTEIN</span></p>
<img src="images/image-1-9.png" class="image-1-9" alt="image-1" />
</div>

</body>
</html>

2.html


<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <style>
    :root {
  --font-family-inter: 'Inter', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
}

.text-white {
  color: var(--text-white);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.text-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: 700;
  font-size: 36px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.image-2-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 80px;
  width: 100%;
  height: auto;
}

.iphone-16-2-1 {
@media (max-width: 1440px) {
  .iphone-16-2-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-2-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(15, 63, 100, 1);
}

  </style>
</head>
<body>
<div class="iphone-16-2-1">
<p class="text-2"><span class="text-white">Thank you
      for
Registering </span></p>
<img src="images/image-2-3.png" class="image-2-3" alt="image-2" />
</div>

</body>
</html>


event.html


<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <style>
    :root {
  --font-family-inter: 'Inter', sans-serif;
  --text-rgb-15-63-100: rgba(15, 63, 100, 1);
}

.text-rgb-15-63-100 {
  color: var(--text-rgb-15-63-100);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.image-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 80px;
  width: 100%;
  height: auto;
}

.rectangle-4-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
  border-radius: 60px;
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-15-63-100);
}

.iphone-16-3-1 {
@media (max-width: 1440px) {
  .iphone-16-3-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-3-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(15, 63, 100, 1);
}

  </style>
</head>
<body>
<div class="iphone-16-3-1">
<img src="images/image-1-2.png" class="image-1-2" alt="image-1" />
<div class="rectangle-4-3"></div>
<p class="text-4"><span class="text-rgb-15-63-100">Blitz ON</span></p>
</div>
<p class="text-4"><span class="text-rgb-15-63-100">Meme Masters</span></p>
</div>
<p class="text-4"><span class="text-rgb-15-63-100">Code Karaoke</span></p>
</div>
<p class="text-4"><span class="text-rgb-15-63-100">Windows Security</span></p>
</div>
<p class="text-4"><span class="text-rgb-15-63-100">Techscape</span></p>
</div>
<p class="text-4"><span class="text-rgb-15-63-100">Power Paradox</span></p>
</div>
<p class="text-4"><span class="text-rgb-15-63-100">Shark Tank</span></p>
</div>
<p class="text-4"><span class="text-rgb-15-63-100">Spirathon</span></p>
</div>
<p class="text-4"><span class="text-rgb-15-63-100">Brain O Mania</span></p>
</div>


</body>
</html>

4.html


<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  <link href="https://fonts.googleapis.com/css?family=Inter&display=swap" rel="stylesheet">

  <style>
    :root {
  --font-family-inter: 'Inter', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
}

.text-white {
  color: var(--text-white);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.image-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 80px;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 36px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.iphone-16-4-1 {
@media (max-width: 1440px) {
  .iphone-16-4-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-4-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(15, 63, 100, 1);
}

  </style>
</head>
<body>
<div class="iphone-16-4-1">
<img src="images/image-1-2.png" class="image-1-2" alt="image-1" />
<p class="text-3"><span class="text-white">Registration 
completed </span></p>
</div>

</body>
</html>

styles.css

:root {
  --font-family-inter: 'Inter', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
  --text-rgb-15-63-100: rgba(15, 63, 100, 1);
}

.text-white {
  color: var(--text-white);
}

.text-rgb-15-63-100 {
  color: var(--text-rgb-15-63-100);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.rectangle-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
  border-radius: 70px;
}

.rectangle-2-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
  border-radius: 70px;
}

.text-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.rectangle-3-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(217, 217, 217, 1);
  border-radius: 70px;
}

.text-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.text-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 20px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-rgb-15-63-100);
}

.text-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-inter);
  font-weight: normal;
  font-size: 36px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.image-1-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  border-radius: 80px;
  width: 100%;
  height: auto;
}

.iphone-16-1-1 {
@media (max-width: 1440px) {
  .iphone-16-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .iphone-16-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(15, 63, 100, 1);
}

```
## OUTPUT:

![alt text](<Screenshot 2025-11-10 135153.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
