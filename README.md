# Ex04 Places Around Me
## Date: 15:04:2024

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
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="red"><b>GUMMIDIPOONDI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>VIGNESH M(212223240176))</b></font>
</h3>
<center>
<img src="Screenshot 2024-04-02 104051.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="600, 100, 900, 500" href="home.html" title="My Home Town">
<area shape="circle" coords="500,250,150,100" href="pvt.html" title="DanBlock Indian pvt">
<area shape="circle" coords="200,200,200,200" href="industry.html" title="Kamachi Industerial Limited">
<area shape="circle" coords="1000,250,150,200" href="village.html" title="Kottai karai">
<area shape="rect" coords="700,100,1000,600" href="temple.html" title="New Gummidipoondi temple"
</map>
</center>
</body>
</html>

home.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>GUMMIDIPOONDI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Gummidipoondi village</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
As of 2001 India census,[2] Gummidipoondi had a population of 32,665. Males constitute 52% of the population and females 48%.
Gummidipoondi has an average literacy rate of 86.5%, higher than the national average of 74.5%: male literacy is 89.7%, and 
female literacy is 83.4%. In Gummidipoondi, 12% of the population is under 6 years of age. Most popular village Thiruvallur (dis)
Find detailed information on Manufacturing companies in Gummidipoondi, Tamil Nadu, India, including financial statements, 
sales and marketing contacts, top competitors, and firmographic insights. Dun & Bradstreet gathers Manufacturing business
information from trusted sources to help you understand company performance, growth potential, and competitive pressures. 
View 356 Manufacturing company profiles below.
</p>
</body>
</html>
pvt.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>GUMMIDIPOONDI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>DanBlock Indian pvt</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Industry: Motor Vehicle Parts Manufacturing ,  Transportation Equipment Manufacturing ,  Manufacturing
Motor vehicle brake systems and partsSee other industries within the  Manufacturing sector: Aerospace Product and
Parts Manufacturing ,  Agriculture, Construction, and Mining Machinery Manufacturing ,  Alumina and Aluminum Production
Is this your business? Contact us to understand how D&B calculated your company’s specific ESG Ranking, provide new or 
updated information to ensure your company’s ESG Ranking remains accurate and up to date, or dispute your current ranking.
</p>
</body>
</html>

industry.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>GUMMIDIPOONDI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Kamachi Industerial Limited</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Kamachi Industries Limited is a Public incorporated on 08 October 2003. It is classified as Non-govt company and is registered at
Registrar of Companies, Chennai. Its authorized share capital is Rs. 2,050,000,000 and its paid up capital is Rs. 2,029,196,170. 
It is inolved in Manufacture of Basic Iron & Steel Kamachi Industries Limited's Annual General Meeting (AGM) was last held on N/A 
and as per records from Ministry of Corporate Affairs (MCA), its balance sheet was last filed on 31 March 2018.
Kamachi Industries Limited's Corporate Identification Number is (CIN) U27106TN2003PLC051727 and its registration number is 51727.
Its Email address is cs@kamachigroup.com and its registered address is ABC Trade Centre Old No.50, (New No. 39), 3rd Floor, 
Anna Salai Chennai TN 600002 IN. Current status of Kamachi Industries Limited is - Active.
</p>
</body>
</html>


village.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>GUMMIDIPOONDI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>Kottai karai village</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Area (2020)	0.19 km²
Population (2020)	447
Population Density	2321 people per km²
Male Population	225
Female Population	222
Nearest airport & distance (Aerial)	Chennai International Airport, 36.24 km
Nearest Railway Station & Distance (Aerial)	Gummidipundi, 0.81 km
The locality Kottai Karai falls in Thiruvallur district situated in Tamil Nadu state, with a population 447.
The male and female populations are 225 and 222 respectively. The size of the area is about 0.19 square kilometer. 
</p>
</body>
</html>


temple.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="red"><b>GUMMIDIPOONDI</b></font>
</h1>
<h3 align="center">
<font color="blue"><b>New Gummidipoondi temple</b></font>
</h3>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The 600 years old temple of Sree Baleeswarar in new Gummidipundi should have been a very great and grand temple in the days past,
with its beautiful gopuram, vimaanam and the adjoining lotus pond. But today as you pass the area it is barely noticeable. Years of 
neglect and vandalism has eroded the temple and left its imprint on the face of this temple. Today a few people living in the vicinity 
who identify themselves as traditional custodians are doing their best to revive and restore this temple to whatever extent possible.
Take a left just before the Gummidipundi railway station on the Kolkata highway, immediately after the Zion Church and drive for about
a couple of kilometers to reach the temple. The location is called new gummidipundi and the temple is located in 13.403762,80.123119. 
the house of the local gentleman who is trying his best to do something is adjoining the temple and they will be happy to open the temple for you.
After visiting this temple drive down another few kilometers to see the sad state of another great temple of the bygone era –
the Chandrasekaraswamy Temple.Share this:
</p>
</body>
</html>
```
## OUTPUT

![Screenshot 2024-04-02 104051](https://github.com/vigneshvickyu/NearMe/assets/151948835/537b7789-f5ee-40c0-836b-7d9c588f3ddc)

![Screenshot 2024-04-21 224021](https://github.com/vigneshvickyu/NearMe/assets/151948835/e62af40a-3404-4f81-8499-373ce4dbac36)

![Screenshot 2024-04-21 224033](https://github.com/vigneshvickyu/NearMe/assets/151948835/16d93f28-e77c-4709-a2f7-6b02178c061b)

![Screenshot 2024-04-21 224044](https://github.com/vigneshvickyu/NearMe/assets/151948835/7f5cd06f-e2b2-453a-90a4-ddc499195c71)

![Screenshot 2024-04-21 224109](https://github.com/vigneshvickyu/NearMe/assets/151948835/5c727adf-635c-4814-a163-125d299403a3)

![Screenshot 2024-04-21 224056](https://github.com/vigneshvickyu/NearMe/assets/151948835/6a0c709d-31fc-4eb3-b2ff-d171953369b9)


## RESULT
The program for implementing image maps using HTML is executed successfully.
