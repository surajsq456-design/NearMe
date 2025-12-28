# Ex03 Places Around Me
## Date: 

## AIM
To develop a website to display details about the places around my house.

## DESIGN STEPS

### STEP 1
Create a Django admin interface.

### STEP 2
Download your city map from Google as an image.

### STEP 3
Insert the image using ```<img>``` tag and link it to the map.

### STEP 4
Using ```<map>``` tag name the map.

### STEP 5
Create clickable regions in the image using ```<area>``` tag.

### STEP 6
Write HTML programs for all the regions identified.

### STEP 7
Execute the programs and publish them.

## CODE
```
map.html

<html>
    <head>
        <title>perambur</title>

    </head>
    <body>
        <h1 align="center"> perambur</h1>
        <h2 align="center"> suraj (25002481)</h2>
        <img src="Screenshot 2025-12-28 225211.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="perambur srinivasa" title="perambur srinivasa" href="perambursrinivasa.html" coords="323,663,465,727" shape="rect">
    <area target="" alt="chennai gold" title="chennai gold" href="chennaigold.html" coords="97,657,252,656,173,717" shape="poly">
    <area target="" alt="dr. ambedkar goverment arts college" title="dr. ambedkar goverment arts college" href="dr.ambedkarclg.html" coords="798,525,952,550,951,592,700,594,690,549,700,538,744,530,778,528" shape="poly">
    <area target="" alt="ctte clg" title="ctte clg" href="ctte clg.html " coords="315,400,64" shape="circle">
    <area target="" alt="kpn fast parcel service" title="kpn fast parcel service" href="kpn.html" coords="413,288,492,275,551,286,589,312,576,330,534,339,500,335,466,338,445,334,432,333,416,328,407,307,407,295,424,285,432,280,462,274,438,276,445,280,479,275,510,272,524,280,483,337" shape="poly">
</map>
    </body>
</html>

chennaigold.html

<html>
    <head>
        <title>
            CHENNAI GOLD
        </title>
    </head>
    <body bgcolor="green">
        <h1 align="center" style="color: red;">Chennai gold</h1>
        <hr>
        <h2>a reference to the prevailing market rate or standard price of gold in Chennai, often used to set jewellery and bullion prices locally.</h2>
    </body>
</html>

cttecclg.html

<html>
    <head><title>CTTE College</title></head>
    <body bgcolor="purpl">
        <h1 align="center">CTTE College</h1>
        <hr>
        <h3>Chevalier T. Thomas Elizabeth College for Women (CTTE) — a women-only self-financing college in Perambur, Chennai, founded in 1985 and affiliated with University of Madras, offering a variety of undergraduate and postgraduate courses to empower women through holistic education <h3>
    <body>
<html>

dr.ambebedkarclg.html

<html>
    <head><title>dr. ambedkar goverment arts college</title></head>
    <body bgcolor="red">
        <h1 align="center">Dr. Ambedkar Government Arts College</h1>
        <hr>
        <h3>Dr. Ambedkar Government Arts College (DAGAC) — a government-run college in Vyasarpadi, Chennai, established in 1972 and affiliated with University of Madras, offering a wide range of undergraduate, postgraduate and doctoral courses across arts, science, commerce and management.</h3>
    </body>
</html>

kpn.html

<html>
    <head>
        <title>kpn fast parcel service</title>
    </head>
    <body bgcolor="yellow">
        <h1 align="center">kpn fast parcel service</h1>
        <hr>
        <h3>KPN Speed Parcel Service — a well-known courier and parcel-delivery company in South India, operating across Tamil Nadu and nearby states, offering fast, reliable domestic parcel services from multiple branches in Chennai and beyond.</h3>
    </body>
</html>

```

## OUTPUT

![alt text](<Screenshot 2025-12-28 225432.png>)
![alt text](<Screenshot 2025-12-28 225548.png>)
![alt text](<Screenshot 2025-12-28 225759.png>)
![alt text](<Screenshot 2025-12-28 225854.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
