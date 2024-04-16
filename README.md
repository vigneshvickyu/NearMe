# Ex04 Places Around Me
## Date: 

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
map.html


<html>
<head>
    <title>MY CITY</title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>GOBICHETTIPALAYAM</b></font>
         </h1>
         <h3 align="center">
            <font color="blue"><b>VIGNESH M (212223240176)</b></font>
         </h3>
         <center>
            <img src="map.png" usemap="#MYCITY" height="610" width="1450">
            <map name="MYCITY">
                <area shape="rect" coords="800,300,850,400" href="home.html" title="MY HOME TOWN">
                <area shape="circle" coords="700,250,150,100" href="temple.html" title="Pavala malai murugan temple">
                <area shape="circle" coords="100,400,400,500" href="college.html" title="Gobi arts & science college">
                <area shape="circle" coords="1000,250,150,200" href="mahal.html" title="Meenakshi suntharesan mahal">
                <area shape="rect" coords="300,500,550,400" href="shop.html" title="Jegan metal mart">
            </map>
         </center>
    </body>
</html>


shop.html


<html>
    <head>
        <title>MY HOME TOWN</title>

    </head>
    <body bgcolor ="yellow">
        <h1 align=""centre">
        <font color="red"><b>GOBICHETTIPALAYAM</b></font>
    </h1>
    <h3 align="centre">
        <font color="green"><b>Jegan metal mart</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
<font face "Georgia" size="5"></font>
jegan Metal Mart, your premier destination for a wide variety of products including electronics, furniture, department store items,
 gifts, appliances, mobile devices, Eversilver, and plastic household items. We take pride in offering an extensive 
 range of high-quality products to cater to all your needs.

REACH US


Address:
No.455 - Dharapuram Main Road,
Modachur GobichettiPalayam - 638 476 Erode District,
Tamil Nadu,
South India.


Email:
jaganmetalmart@gmail.com
</p >
    </body>
</html>

home.html

<html>
    <head>
        <title>MY HOME TOWN</title>

    </head>
    <body bgcolor ="pink">
        <h1 align=""centre">
        <font color="black"><b>GOBICHETTIPALAYAM</b></font>
    </h1>
    <h3 align="centre">
        <font color="blue"><b>MY HOME</b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
<font face "Georgia" size="5"></font>
My beautiful house is on the outskirts of the town. We have built our house on a suitable plot with a garden space and greenery
 to enjoy. My house has two bedrooms and a living room, along with a kitchen and a dining room and dinning hall where we dont eat
 there.Instead of eating in dinning hall i used to eat in living area watching. Near my home there is an beautiful mountain.
 Where there is available of many medicinal plants. And there was lots of sandalwoods trees ..
</p >
    </body>
</html>

temple.html

<html>
    <head>
        <title>MY HOME TOWN</title>

    </head>
    <body bgcolor ="pink">
        <h1 align=""centre">
        <font color="red"><b>GOBICHETTIPALAYAM</b></font>
    </h1>
    <h3 align="centre">
        <font color="blue"><b>PAVALAI MALAI MURUGAN TEMPLE</b></font>
    </h3>
    <hr size="3" color="lavender">
    <p align="justify">
<font face "Georgia" size="5"></font>
Temple is main deity is lorn Murugan, who us worshipped as the god of war and handsome young man ridinga peacock with six faces
 and twelve arms.Very Devine! A must visit for Murugan devotees. Temple on top of small hillock. Surrounding views are good.
The temple architecture is a fine example of the dravidian and there is a big murugan statue at the entrance.
In the temple is beautiful and it was located in the hillock. And it was the famous temple in the tamil nadu.
</p >
    </body>
</html>

college.html

<html>
    <head>
        <title>MY HOME TOWN</title>

    </head>
    <body bgcolor ="lavender">
        <h1 align=""centre">
        <font color="green"><b>GOBICHETTIPALAYAM</b></font>
    </h1>
    <h3 align="centre">
        <font color="grey"><b>GOBI ARTS & SCIENCE COLLEGE </b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
<font face "Georgia" size="5"></font>
The college was established in 1968 affiliated to Madras University, Chennai. Later, the college became affiliated to Bharathiar 
University, Coimbatore. It is a co-educational grant-in-aid institution managed by the Gobi Arts College Council, registered on
 25.8.1967 under the Societies Registration Act, XXI of 1860. The college was started with the noble objective of opening the doors 
 of higher education to the poor and meritorious students who are mostly first generation students coming from agricultural families.
 It was the famous college in that particular location..

</p >
    </body>
</html>

mahal.html

<html>
    <head>
        <title>MY HOME TOWN</title>

    </head>
    <body bgcolor ="lavender">
        <h1 align=""centre">
        <font color="green"><b>GOBICHETTIPALAYAM</b></font>
    </h1>
    <h3 align="centre">
        <font color="red"><b>MENAKSHI SUNDHARESAN MAHAL </b></font>
    </h3>
    <hr size="3" color="red">
    <p align="justify">
<font face "Georgia" size="5"></font>
Our Menakshi sundherasan mahal in Gobichettipalayam is an air conditioned hall with a seating capacity of 500 and a floating capacity of 750.
 The Dining capacity of menakshi sundherasan mahal is 200. The Function hall is in Ground floor. Parking facility is available for 200 cars 
 and 300 bikes. There is generator back up for the event to function smoothly during power cut. The Kalyana Mandapams provides
  air conditioned rooms with locker facility for the guests. You can contact us via Matrimony Mandaps for the best services.
  It was the biggest mahal in the  particular location..

</p >
    </body>
</html>
```


## OUTPUT







## RESULT
The program for implementing image maps using HTML is executed successfully.
