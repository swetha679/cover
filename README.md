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
```
DEVELOPED BY: SWETHA NIVASINI B R
REG NO:212224040345
```

```
html:


<!DOCTYPE html>
<html lang="en">
<head>

<title>Guide</title>
<link rel="stylesheet" href="bstyle.css"> 




</head>
<body>
  <div class="cover">
    <div class="tagline">Universe's Wisdom</div>
   <div class="title">
  <span>The Essential Guide</span>
  <span>to Astrology &</span>
  <span>Planetary Calculations</span>
</div>

    <div class="subtitle">
      Decode your Birth chart,<br>
      discover signs, houses, and aspects.
    </div>
  
    
    <div class="wave"></div>
      <img src="mg pub.jpg" alt="Author Picture" class="author-pic"> 
       <div class="bottom-section">
    <div class="divider"></div>
    <div class="author">Scholar Mg Pur</div>
    <div class="publisher">PKMM PUBLISHERS</div>
      <div class="edition">Sixth Edition</div>
  </div>
   
  </div>
</body>
</html>


  css:
  body {
  margin: 0;
  font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
  background-color: #2c2c2c;
  color: white;
}

.cover {
  position: relative;
  width: 100%;
  height: 100vh;           
  max-width: 600px;
  margin: 0 auto;
  padding: 40px 20px;
  background-color: #2c2c2c;
  overflow: hidden;
  z-index: 1;
}


.wave {
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: linear-gradient(rgba(44, 44, 44, 0.6), rgba(44, 44, 44, 0.6)), 
              url('venus.jpg') no-repeat center center;
  background-size: cover;
  z-index: 0;
}
.cover {
  display: flex;
  flex-direction: column;
 justify-content: space-between;
  height: 95vh;
  position: relative;
  padding: 40px 20px;
  background-color: #2c2c2c;
  max-width: 600px;
  margin: 0 auto;
  overflow: hidden;
}

.tagline {
  color: #ffffff;
  font-size: 19px;
  margin-bottom: 10px;
  border-left: 7px solid orange;
  padding-left: 12px;
  
  font-weight: bold;
}

.title {
  font-size: 48px;
  font-weight: bold;
  line-height: 1.3;
  margin-bottom: -20px;
 
  margin-top: 150;   
     

}

.subtitle {
  font-size: 35px;
  color: #f0f0f0;
  margin-bottom: 40px; 
}

.edition {
  position: absolute;
  right: 20px;
  bottom: 80px;
  font-size: 18px;
  color: orange;
  font-weight: bold;
  z-index: 2;
}

.divider {
  width: 100%;
  height: 4px;
  background-color: orange;
  margin: 30px 0 20px;
  border-radius: 2px;
}

.author {
  font-size: 20px;
  color: rgb(255, 255, 255);
  font-weight: bold;
  margin-bottom: 10px;
}

.publisher {
  font-size: 16px;
  color: white;
  font-weight: bold;
  background-color: #442d04;
  display: inline-block;
  padding: 5px 0px;
  border-radius: 5px;
  margin-left: 0px;
}

.author-pic {
  width: 150px;
  height: 150px;
  object-fit: cover;
  border-radius: 50%;
  position: absolute;
  right: 20px;        
  bottom: 150px;     
  border: 3px solid #442d04;
  
}
.title, .subtitle, .tagline, .author, .publisher,.divider{
  position: relative;
  z-index: 1;
}

```



## OUTPUT:

![Screenshot 2025-05-27 210506](https://github.com/user-attachments/assets/6b07534e-67b0-456c-a64b-4c278ca38fb5)







## RESULT:
The program for designing a book front cover page using HTML and CSS has been completed successfully.
