# Ex04 Places Around Me
## Date: 23/04/2025

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google.

### STEP 3
Using ```<map>``` tag name the map.

### STEP 4
Create clickable regions in the image using ```<area>``` tag.

### STEP 5
Write HTML programs for all the regions identified.

### STEP 6
Execute the programs and publish them.

## CODE
```
<<<<<<< HEAD
map.html
=======
>>>>>>> 630ffd8c420df15eebe6c20d155ab50f718ba1ef
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>kanchipuram</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>PARANTHAMAN (212224040232)</b></font>
</h3>
<center>
    <img src="Screenshot 2024-11-26 080856.png" usemap="#image-map">

    <map name="image-map">
        <area target="" alt="narbhavi hospital" title="narbhavi hospital" href="hosp.html" coords="66,276,225,339" shape="rect">
        <area target="" alt="gsr residency" title="gsr residency" href="gsr.html" coords="537,298,720,361" shape="rect">
        <area target="" alt="old zari" title="old zari" href="old.html" coords="580,551,738,621" shape="rect">
        <area target="" alt="thirukalimedu" title="thirukalimedu" href="thiru.html" coords="1046,676,1214,771" shape="rect">
        <area target="" alt="fasttrack store" title="fasttrack store" href="fast.html" coords="658,738,835,820" shape="rect">
        <area target="" alt="" title="" href="" coords="" shape="0">

</center> 

</body>
<<<<<<< HEAD
</html> 

hosp.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Narbhavi Hospital</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #e1afaf;
            color :aquamarine
            padding: 10px 0;
            text-align: center;
        }
        .content {
            padding: 20px;
            margin-top: 20px;
        }
        .content h2 {
            color: #333;
        }
        .content p {
            font-size: 16px;
            color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Narbhavi Hospital</h1>
    </header>
    
    <div class="content">
        <h2>About Narbhavi Hospital</h2>
        <p>Narbhavi Hospital is a leading healthcare facility committed to providing compassionate care and advanced medical services. With a team of experienced doctors and healthcare professionals, it offers a wide range of treatments in a comfortable and patient-friendly environment. The hospital focuses on delivering high-quality care with state-of-the-art technology and facilities. It is dedicated to the health and well-being of the community, ensuring timely and effective care. Narbhavi Hospital's mission is to offer personalized healthcare solutions for every patient, promoting better outcomes and a healthier future.</p>
    </div>
</body>
</html>

 old.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>old zari</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #860463;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        .content {
            padding: 20px;
            margin-top: 20px;
        }
        .content h2 {
            color: #bd3030;
        }
        .content p {
            font-size: 16px;
            color: #010101;
        }
    </style>
</head>
<body>
    <header>
        <h1>old zari</h1>
    </header>
    
    <div class="content">
        <h2>About old zari store</h2>
        <p>Old zari sarees are exquisite traditional garments known for their intricate embroidery and rich craftsmanship. The zari work, typically done with gold or silver thread, adds a luxurious and regal touch to the fabric. These sarees are often passed down through generations, cherished for their cultural and sentimental value. Over time, the zari can show signs of age, giving the saree a vintage charm that is highly appreciated by collectors and enthusiasts. Wearing an old zari saree evokes a sense of timeless elegance and heritage, making it a treasured piece in any wardrobe.</p>
    </div>
</body>
</html>
 
 gsr.html
 <!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>GSR Residency</title>
    <style>
        body {
            font-family: 'Verdana', sans-serif;
            line-height: 1.6;
            background-color: #e9ecef;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #007BFF;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        .content {
            padding: 20px;
            margin-top: 20px;
        }
        .content h2 {
            color: #333;
        }
        .content p {
            font-size: 16px;
            color: #444;
        }
    </style>
</head>
<body>
    <header>
        <h1>GSR Residency</h1>
    </header>
    
    <div class="content">
        <h2>About GSR Residency</h2>
        <p>GSR Residency is a modern residential complex located in a peaceful and well-connected area. The residency offers spacious apartments with contemporary designs and world-class amenities. Residents enjoy a comfortable and secure living environment, with easy access to key services. The surrounding neighborhood is vibrant, with schools, hospitals, and markets nearby. GSR Residency is an ideal place for families looking for a harmonious blend of comfort and convenience.</p>
    </div>
</body>
</html>
 
fast.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FastTrack Store</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            line-height: 1.6;
            background-color: #f0f0f0;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #333;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        .content {
            padding: 20px;
            margin-top: 20px;
        }
        .content h2 {
            color: #333;
        }
        .content p {
            font-size: 16px;
            color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>FastTrack Store</h1>
    </header>
    
    <div class="content">
        <h2>About FastTrack Store</h2>
        <p>FastTrack Store is a retail outlet offering a wide range of trendy accessories and fashion items. Known for its stylish watches, bags, and eyewear, it caters to fashion-forward individuals. The store features high-quality products with a modern and sleek design. Customers can enjoy an exciting shopping experience with various promotions and discounts. Located in a prime area, FastTrack Store is a popular destination for those looking to update their style.</p>
    </div>
</body>
</html>
 
thiru.html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Thirukalimedu</title>
    <style>
        body {
            font-family: 'Georgia', serif;
            line-height: 1.6;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
        }
        header {
            background-color: #4CAF50;
            color: white;
            padding: 15px 0;
            text-align: center;
        }
        .content {
            padding: 20px;
            margin-top: 20px;
        }
        .content h2 {
            color: #333;
        }
        .content p {
            font-size: 16px;
            color: #555;
        }
    </style>
</head>
<body>
    <header>
        <h1>Thirukalimedu</h1>
    </header>
    
    <div class="content">
        <h2>About Thirukalimedu</h2>
        <p>Thirukalimedu is a serene village located in Tamil Nadu, known for its rich cultural heritage and historical significance. The place is famous for the ancient temple dedicated to Lord Shiva, attracting devotees from surrounding regions. The village is surrounded by beautiful landscapes and offers a peaceful retreat away from urban bustle. Thirukalimedu also hosts annual religious festivals, which bring the community together. The vibrant traditions and scenic beauty make it a must-visit location for culture and history enthusiasts.</p>
    </div>
</body>
=======
>>>>>>> 630ffd8c420df15eebe6c20d155ab50f718ba1ef
</html>

```

## OUTPUT
![alt text](1.png)
![alt text](2.png)
![alt text](3.png)
![alt text](4.png)
![alt text](5.png)
![alt text](6.png)

## RESULT
The program for implementing image maps using HTML is executed successfully.
