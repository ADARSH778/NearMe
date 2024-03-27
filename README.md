# Ex04 Places Around Me
## Date: 27-03-2024

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
<font color="red"><b>Nellore</b></font>
</h1>
<h2 align="center">
<font color="green"><b>Adarsh Chowdary R (212223040166)</b></font>
</h2>
<center>
<img src="map.png" usemap="#MyCity" height="610" width="1450">
<map name="MyCity">
<area shape="rect" coords="600,350,300,100" href="home.html" title="My Home Town">
<area shape="rect" coords="650,350,400,100" href="temple.html" title="sri Anjineya Swamy Temple">
<area shape="rect" coords="850,350,750,200" href="ground.html" title="Vrc Cricket ground">
<area shape="rect" coords="750,350,750,300" href="school.html" title="Modern High school">
<area shape="rect" coords="570,230,45,50" href="station.html" title="Nellore Railway Station">
</map>
</center>
</body>
</html>

home.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="orange">
<h1 align="center">
<font color="red"><b>Nellore</b></font>
</h1>
<h2 align="center">
<font color="black"><b>Nellore - My Home Town</b></font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Nellore, often referred to as "Nelluru," holds a special place in the hearts of its residents as a cherished hometown. Nestled in the southern part of Andhra Pradesh, India, Nellore exudes a sense of community and belonging. Its warm and welcoming atmosphere, coupled with its rich cultural heritage, creates a unique charm that resonates with locals and visitors alike. From its bustling markets filled with fresh produce to its serene lakes and parks, Nellore offers a delightful blend of urban amenities and natural beauty. Whether it's enjoying traditional delicacies at local eateries or partaking in cultural festivities, the spirit of Nellore's hometown pride shines through in every aspect of daily life.
</font>
</p>
</body>
</html>

temple.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="yellow">
<h1 align="center">
<font color="brown"><b>Nellore</b></font>
</h1>
<h2 align="center">
<font color="red"><b>Sri Anjineya Swamy Temple</b></font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Lord Hanuman is a prominent deity in Hinduism and is revered for his unwavering devotion to Lord Rama. Temples dedicated to Lord Hanuman can be found in various parts of the world, and the name "Anjineya Swamy Temple" could be associated with one such temple.Hanuman temples can be found throughout India and in various other countries with Hindu communities. These temples vary in size and architectural style. Devotees visit these temples to offer prayers, seek blessings, and express their devotion to Lord Hanuman.Hanuman is often depicted as a monkey god, symbolizing strength, agility, and unwavering devotion. His role in the Hindu epic Ramayana, where he plays a crucial part in the rescue of Sita, adds to his significance in the Hindu pantheon.
</font>
</p>
</body>
</html>

school.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="gold"><b>Nellore</b></font>
</h1>
<h2 align="center">
<font color="skyblue"><b>Modern High School</b></font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
The Modern High School in Nellore is a beacon of educational excellence, offering a nurturing environment for students to thrive academically and personally. With a commitment to holistic development, the school provides a comprehensive curriculum, state-of-the-art facilities, and dedicated educators who inspire and guide students towards success. Emphasizing innovation, critical thinking, and character building, the Modern High School in Nellore prepares students to excel in a rapidly evolving world while instilling values of integrity, leadership, and service. It stands as a testament to educational innovation and serves as a cornerstone in shaping the future leaders of tomorrow.
</font>
</p>
</body>
</html>

ground.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="blue"><b>Nellore</b></font>
</h1>
<h2 align="center">
<font color="green"><b>VRC Cricket ground</b></font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
A cricket group could refer to a sports team or club that plays the game of cricket. Cricket is a popular sport in many countries, and teams can range from local and amateur clubs to professional and international teams. Players in a cricket group often practice and compete together in various formats of the game, such as Test matches, One Day Internationals (ODIs), and Twenty20 (T20) matches.Some organizations or communities are dedicated to supporting a particular cricket team or player. These fan clubs, often referred to as cricket groups, bring together fans who share a common passion for a specific team or player. They may organize events, share updates, and celebrate the successes of their favorite cricket entities.
</font>
</p>
</body>
</html>

station.html

<html>
<head>
<title>My Home Town</title>
</head>
<body bgcolor="violet">
<h1 align="center">
<font color="red"><b>Nellore</b></font>
</h1>
<h2 align="center">
<font color="blue"><b>Railway Station</b></font>
</h2>
<hr size="3" color="red">
<p align="justify">
<font face="Georgia" size="5">
Nellore railway station is a vital transportation hub located in the city of Nellore, Andhra Pradesh, India. Serving as a crucial link in the Indian railway network, it facilitates both passenger and freight transport. With its strategic location, Nellore railway station connects travelers to various destinations across the country. Equipped with modern amenities and services, it ensures convenience and efficiency for passengers commuting through its premises. Nellore railway station plays a significant role in fostering connectivity and contributing to the region's socio-economic development.It totally consists of 4 platforms.
</font>
</p>
</body>
</html>

```

## OUTPUT

![alt text](<Screenshot (29).png>)
![alt text](<Screenshot (31).png>)
![alt text](<Screenshot (32).png>)
![alt text](<Screenshot (34).png>)
![alt text](<Screenshot (33).png>)
![alt text](<Screenshot (30).png>)

## RESULT
The program for implementing image maps using HTML is executed successfully.
