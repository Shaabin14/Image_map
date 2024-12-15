# Ex04 Places Around Me
# Date: 20.10.2024
# AIM
To develop a website to display details about the places around my house.

# DESIGN STEPS
## STEP 1
Create a Django admin interface.

## STEP 2
Download your city map from Google.

## STEP 3
Using <map> tag name the map.

## STEP 4
Create clickable regions in the image using <area> tag.

## STEP 5
Write HTML programs for all the regions identified.

## STEP 6
Execute the programs and publish them.

# CODE
index.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Image Map</title>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link rel="stylesheet" href="css/style.css">
</head>
<body>
<h1>Mannivakkam's Map</h1>
    <div class="container">
        <div class="image_container">
            <img id="image" src="image.png" usemap="#image-map">
            <map name="image-map">
                <area alt="Supermarket" title="Supermarket" href="second.html" coords="28,413,300,480" shape="rect">
                <area alt="Ruby" title="Ruby" href="third.html" coords="143,570,262,705,418,586" shape="poly">
                <area alt="Casagrand" title="Casagrand" href="fourth.html" coords="317,100,108" shape="circle">
            </map>
        </div>
    </div>
</body>
</html>

```
second.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Sivasakthi Supermarket</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f8f9fa;
            text-align: center;
        }
        header {
            background-color: #28a745;
            color: white;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
        }
        main {
            padding: 20px;
        }
        .responsive-image {
            width: 100%;
            max-width: 600px;
            height: auto;
        }
        footer {
            background-color: #343a40;
            color: white;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Sivasakthi Supermarket</h1>
    </header>
    <main>
        <p>Your one-stop shop for all your daily needs!</p>
        <img src="sivasakthi-supermarket-mannivakkam-chennai-supermarkets-1exjsok.avif" alt="Sivasakthi Supermarket" class="responsive-image">
    </main>
    <p style="font-weight: bold; text-align: center;">Sivasakthi Supermarket in Mannivakkam is a trusted destination for all your daily shopping needs. Known for its wide range of quality products, the supermarket offers everything from fresh fruits and vegetables to groceries, dairy products, household essentials, and more. Conveniently located in the heart of Mannivakkam, Sivasakthi Supermarket is committed to providing customers with a seamless shopping experience through excellent customer service and competitive pricing. Whether you're stocking up on staples or looking for specialty items, Sivasakthi Supermarket ensures you find everything you need under one roof, making it a preferred choice for families in the community. </p>
    <footer>
        <p>&copy; 2024 Sivasakthi Supermarket. All rights reserved.</p>
    </footer>
</body>
</html>

```
third.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Ruby Royal Tower</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f4f8;
            text-align: center;
        }
        header {
            background-color: #8b0000;
            color: white;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
        }
        main {
            padding: 20px;
        }
        .responsive-image {
            width: 100%;
            max-width: 500px;
            height: auto;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Ruby Royal Tower</h1>
    </header>
    <main>
        <p>A symbol of luxury and elegance in the heart of the city!</p>
        <img src="JLL_CHN_Ruby_Royal_Tower_279_ELV_primary.jpg" alt="Ruby Royal Tower" class="responsive-image">
    </main>
    <p style="font-weight: bold; text-align: center;">Ruby Royal Tower in Mannivakkam stands as a landmark of modern architecture and luxurious living. Designed to provide a perfect blend of comfort and sophistication, this premium residential complex offers spacious apartments, state-of-the-art amenities, and a serene environment. Conveniently located in the rapidly developing neighborhood of Mannivakkam, Ruby Royal Tower ensures easy access to schools, shopping centers, healthcare facilities, and major transportation hubs. Whether you're looking for a dream home or a sound investment, Ruby Royal Tower promises a lifestyle that combines elegance, convenience, and tranquility, making it a preferred choice for families and professionals alike.</p>
    <footer>
        <p>&copy; 2024 Ruby Royal Tower. All rights reserved.</p>
    </footer>
</body>
</html>

```
fourth.html
```
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Casagrand</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #e9f5f8;
            text-align: center;
        }
        header {
            background-color: #007bff;
            color: white;
            padding: 20px 0;
        }
        header h1 {
            margin: 0;
        }
        main {
            padding: 20px;
        }
        .responsive-image {
            width: 100%;
            max-width: 1800px;
            height: auto;
        }
        footer {
            background-color: #333;
            color: white;
            padding: 10px 0;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <header>
        <h1>Welcome to Casagrand</h1>
    </header>
    <main>
        <p>Discover luxury living with Casagrand – where dreams come true!</p>
        <img src="Project-Photo-10-Casa-Grande-Mannivakkam-Chennai-5097587_345_1366.jpg" alt="Casagrand" class="responsive-image">
    </main>
    <p style="font-weight: bold; text-align: center;">Casagrand is a leading real estate developer known for creating exceptional residential communities that blend modern architecture with thoughtful design. With a commitment to quality and innovation, Casagrand has delivered numerous projects across key cities, offering homes that cater to diverse lifestyles and preferences. Each project is carefully planned to provide residents with world-class amenities, ample green spaces, and a vibrant community experience. Whether it's premium apartments, luxurious villas, or affordable housing, Casagrand focuses on delivering value and enhancing the quality of living for its customers. Trusted for its transparency and customer-centric approach, Casagrand has become a preferred choice for homebuyers seeking a perfect balance of comfort, convenience, and style.Casagrand has established itself as a pioneer in the real estate industry, redefining urban living with its innovative projects. Known for their attention to detail and uncompromising quality, Casagrand homes are designed to provide the ultimate blend of luxury, functionality, and sustainability. From spacious layouts and premium finishes to well-planned amenities such as swimming pools, fitness centers, and landscaped gardens, every Casagrand property is a testament to superior craftsmanship.</p>
    <footer>
        <p>&copy; 2024 Casagrand. All rights reserved.</p>
    </footer>
</body>
</html>

```
css
```
h1{
    text-align: center;
}
body {
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh; /* Full viewport height */
    margin: 0; /* Remove default margin */
}
body {
    font-family: 'Poppins', sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f5f5f5;
}
.container {
    width: 100%;
    max-width: 1200px;
    margin: 0 auto;
    padding: 20px;
    text-align: center;
}
.image_container {
    position: relative;
    display: inline-block;
}
#image {
    max-width: 100%;
    height: auto;
    border: 2px solid #ddd;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    border-radius: 8px;
}
area {
    outline: none;
}
area[alt="Supermarket"]:hover,
area[alt="Ruby"]:hover,
area[alt="Casagrand"]:hover {
    cursor: pointer;
}
area[alt="Supermarket"]::after {
    content: "Supermarket";
    position: absolute;
    bottom: 110%;
    left: 50%;
    transform: translateX(-50%);
    background-color: #333;
    color: #fff;
    padding: 5px 10px;
    border-radius: 4px;
    white-space: nowrap;
    opacity: 0;
    pointer-events: none;
    transition: opacity 0.3s ease-in-out;
}
area[alt="Supermarket"]:hover::after {
    opacity: 1;
}
/* Style for all paragraphs */
p {
    font-size: 18px; /* Adjust as needed */
    line-height: 1.6; /* Improve readability */
    color: #333; /* Text color */
    margin: 10px 0; /* Spacing around paragraphs */
}
/* Apply a background color to the entire page */
body {
    background-color: #73b7f3; /* Light blue background color */
    margin: 0; /* Remove default margin for a clean look */
    font-family: Arial, sans-serif; /* Optional: Set a font family */
}
/* General paragraph styling (applies to all pages) */
p {
    font-size: 16px;
    line-height: 1.6;
}

/* Paragraph colors for specific pages */
body.page1 p {
    color: red; /* Page 1 paragraph color */
}

body.page2 p {
    color: blue; /* Page 2 paragraph color */
}

body.page3 p {
    color: green; /* Page 3 paragraph color */
}
/* Make all paragraphs bold */
p {
    font-weight: bold;
}

```

# OUTPUT
![img1](https://github.com/user-attachments/assets/a9d7f28c-dedb-46ef-b0ba-d3fcae205a6a)

![img2](https://github.com/user-attachments/assets/f46e4a65-51c2-4d72-a646-7f354a967a35)

![img3](https://github.com/user-attachments/assets/0d0548b6-1531-47f4-bef4-767d6e15dcdd)

![web5](https://github.com/user-attachments/assets/35de620c-af7f-4cad-be46-d04174d9f33b)

# RESULT
The program for implementing image maps using HTML is executed successfully.
