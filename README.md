# Ex04 Places Around Me
# Date:
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

    {% load static %}
    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>My area</title>
    </head>
    <body>
        <!-- Image Map Generated by http://www.image-map.net/ -->
    <img src="map.png" usemap="#image-map">
    <img src="{% static 'imgapp/static/map.png' %}" alt="Example Image">

    <map name="image-map">
        <area target="" alt="Little Flower" title="Little Flower" href="little_flower.html" coords="743,525,900,588" shape="rect">
        <area target="" alt="GJOBS" title="GJOBS" href="GJOBS.html" coords="1090,311,84" shape="circle">
        <area target="" alt="Inspire Training" title="Inspire Training" href="Academy.html" coords="1105,411,1285,493" shape="rect">
        <area target="" alt="Madha Nagar" title="Madha Nagar" href="Madhanagar.html" coords="1448,233,1189,15" shape="rect">
        <area target="" alt="Rajagopalapuram" title="Rajagopalapuram" href="rajagopalapuram.html" coords="1445,516,142" shape="circle">
    </map>
    </body>
    </html>


    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>INSPIRE-TRAINING</title>
    </head>
    <body style="background-color: bisque;">
        <h1 style="text-align: center;">INSPIRE TRAINING ACADEMY</h1>
        <p style="font-size: large; text-align: center;">Inspire Training Academy brings a new dimension and enhanced dynamism in the impartation and gaining of knowledge.
            Inspire Management Training Centre is a professional leader in educational service in Doha, Qatar. Our certified courses are available under various categories such as Aviation, Hospitality, Leadership, Soft Skills, Health & Safety and many more.
        </p>

    </body>
    </html>


    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>GJOBS</title>
    </head>
    <body style="background-color: beige;">
        <h1 style="text-align: center;"> GJOBS COMPANY</h1>
        <br></br>
        <p style="font-size: medium; text-align: center;">"GJOBS INDIA PRIVATE LIMITED has established itself as a premier outsourcing company, catering to the diverse needs 
            
            of businesses across various sectors. Known for its exceptional service quality, GJOBS INDIA has become a trusted partner
            
            for companies looking to optimize their operations and focus on core business activities.Gjobs India Private Limited is a Private company incorporated on 16 September 2016. It is classified as Non-government company and is registered at Registrar of Companies, Chennai. Its authorized share capital is Rs. 100,000 and its paid up capital is Rs. 100,000. It's NIC code is 749 (which is part of its CIN). As per the NIC code, it is inolved in Business activities n.e.c..


        </P>


    </body>
    </html>


    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Little_Flower</title>
    </head>
    <body style="background-color: aquamarine;">
        <h1 style="text-align: center;">LITTLE FLOWER SCHOOL</h1>
        <p style="font-size: large; text-align: center;">A Centre for academic excellence and Achievement, it is today one of the finest institutions for the empowerment of children. Located at the cutting edge of knowledge, LFMHSS has not just kept pace with the changing world but has been the pioneering spirit behind many innovations in the field of education.
            Address: 3/250, Kundrathur Main Rd, Lawrence Nagar, Lakshme Nagar, Moulivakkam, Chennai, Tamil Nadu 600116
        Phone: 044 2382 1122 </p>
    </body>
    </html>


    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Madhanagar</title>
    </head>
    <body style="background-color: azure;">
        <h1 style="text-align: center;"> Madhanagar Main Road</h1>
        <p style="font-size: large; text-align: center;">Madha Nagar Main Road, Madha Nagar, Madhanandapuram is a in Chennai City in Tamil Nadu State, India.
            Madha Nagar Main Road, Madha Nagar, Madhanandapuram Pin code is 600116 and postal head office is Sriramachandra Deemed Uty .
            Madha Nagar is a in Kunnattur City in Tamil Nadu State, India.
    Madha Nagar Pin code is 600116 and postal head office is Sriramachandra Deemed Uty .
        </P>

    </body>
    </html>


    <!DOCTYPE html>
    <html lang="en">
    <head>
        <meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
        <title>Rajagopalapuram</title>
    </head>
    <body style="background-color: antiquewhite;">
        <h1 style="text-align: center; ">Rajagopalapuram Street</h1>
        <p style="font-size: large; text-align: center;">7/203, 2nd Street Rajagopalapuram, Moulivakkam, Chennai - 600116 (Near Bai Kadai Bus Stop)
            Sulochana Nagar is an sublocality in Moulivakkam, Chennai west, Chennai, Chennai District, Tamil Nadu, India.

    Moulivakkam (0.0 Km), Gerugambakkam (1.25 Km), Kolapakkam (2.35 Km), Iyyappanthangal (3.18 Km), Porur (3.23 Km) are the nearby areas to Sulochana Nagar.

    Periyapanicheri, Kolathuvancheri, Adayalampattu, Madanandapuram, Chennai, Meenampakkam are the nearby cities to Sulochana Nagar.
        </p>

    </body>
    </html>

# OUTPUT



 ![alt text](<Screenshot 2024-11-21 183054.png>) 

 ![alt text](<Screenshot 2024-11-21 183605.png>)

 ![alt text](<Screenshot 2024-11-21 183322.png>) 

 ![alt text](<Screenshot 2024-11-21 183407.png>) 

 ![alt text](<Screenshot 2024-11-21 183445.png>) 

 ![alt text](<Screenshot 2024-11-21 183525.png>)

# RESULT
The program for implementing image maps using HTML is executed successfully.
