# Ex04 Places Around Me
## Date:27/11/24

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
<html>
<head>
<title>My City</title>
</head>
<body>
<h1 align="center">
<font color="purple"><b>Ambattur</b></font>
</h1>
<h3 align="center">
<font color="red"><b>Manasa Devi AT (24900506)</b></font>
</h3>
<center>
<img src="Map.png.png" usemap="#MyCity">
<map name="MyCity">
<img src="Screenshot 2024-11-26 094011.png" usemap="#image-map">

<map name="image-map">
    <area target="" alt="Vcare Hospiatl" title="Vcare Hospiatl" href="Vcare.html" coords="702,508,964,604" shape="rect">
    <area target="" alt="Thangal park" title="Thangal park" href="park.html" coords="1102,190,1271,279" shape="rect">
    <area target="" alt="Stedford Hospital" title="Stedford Hospital" href="Stedford.html" coords="472,138,692,238" shape="rect">
    <area target="" alt="Naidu Hall" title="Naidu Hall" href="Naidu Hall.html" coords="713,101,962,215" shape="rect">
    <area target="" alt="Oragadam" title="Oragadam" href="Oragadam.html" coords="929,0,1090,90" shape="rect">
</map>
</map>
</center>
</body>
</html>

<html>
<head>
<title>Mycity</title>
</head>
<body bgcolor="pink">
<h1 align="center">
<font color="Red" size="7px"><b>Ambattur</b></font>    
</h1>
<h3 align="center">
<font color="brown" size="6px"><b>Vcare Hospital</b></font>    
</h3>
<hr size="3" color="black">
<p align="justify" style="font-size: larger; font-family: 'Times New Roman';">
<front face="New Times Roman"  size="5px">
Dr.Praba is the founder of Vcare Clinic in Ambattur, Chennai, specializes in hair and skin care solutions. Located at Prince Info Park, Tower B, Ambattur Industrial Estate, the clinic offers treatments like hair transplants, PRP therapy, and advanced diagnostics for hair loss and skin issues. Known for its modern facilities and qualified staff, VCare has become a trusted name for personalized cosmetic and trichology treatments. VCare, located in Ambattur, Chennai, specializes in hair and skin treatments. It offers advanced solutions for issues such as hair loss, dandruff, pigmentation, acne, and anti-aging. The clinic provides services like hair transplantation, laser hair removal, and customized skincare treatments. They also focus on holistic approaches, including lifestyle and dietary recommendations​.
</p>
</body>
</html>

<html>
<head>
<title>My city</title>
</head>
<body bgcolor="Lavender">
<h1 align="center">
<font color="dark pink" size="7px"><b>Ambattur</b></font>    
</h1>
<h3 align="center">
<font color="blue" size="6px"><b>Thangal park</b></font>    
</h3>
<hr size="3" color="black">
<p align="justify" style="font-size: larger; font-family: 'Times New Roman';">
<front face="New Times Roman"  size="5px">
Thangal Park is located in the Kallikuppam area of Ambattur, Chennai, part of the city's Zone 7. It is known for being close to residential neighborhoods and urban amenities. Ambattur itself is a major suburb of Chennai, featuring notable infrastructure like Sir Ivan Stedeford Hospital and access to railway stations such as Ambattur and Pattaravakkam, offering strong connectivity.Thangal Pond Park, located in Vijayalakshmi Puram, Ambattur, Chennai, is a serene spot popular for morning walks, jogging, and leisure activities. It features a peaceful ambiance with lush greenery, making it suitable for families and fitness enthusiasts. Visitors appreciate its tree coverage and play area for kids, though some suggest better maintenance.
</p>
</body>
</html>

<html>
<head>
<title>My city</title>
</head>
<body bgcolor="cyan">
<h1 align="center">
<font color="dark pink" size="7px"><b>Ambattur</b></font>    
</h1>
<h3 align="center">
<font color="blue" size="6px"><b>Stedford Hospital</b></font>    
</h3>
<hr size="3px" color="blue">
<p align="justify" style="font-size: larger; font-family: 'Times New Roman';">
<front face="New Times Roman"  size="5px">
Sir Ivan Stedeford Hospital in Ambattur, Chennai, is a well-known multispecialty hospital established in 1966 by the AMM Foundation. Named after Sir Ivan Stedeford, a philanthropist and industrialist, the hospital offers comprehensive services across departments like cardiology, neurology, oncology, urology, and pediatrics.It is equipped with modern facilities, including ICUs, NICUs, dialysis units, advanced diagnostic tools (CT, MRI), and specialized surgical units. The hospital performs approximately 6,500 surgeries annually and treats over 450,000 patients each year. It also emphasizes education and research in healthcare.Sir Ivan Stedeford Hospital in Ambattur, Chennai, is a multi-specialty hospital established in 1966 under the AMM Foundation. It offers modern medical facilities and services, including cardiology, gastroenterology, orthopedics, urology, ENT, and general surgery. The hospital features a 200-bed capacity, emergency care, a blood bank, diagnostics (MRI, CT, ultrasound), and advanced operation theaters. It also has a dialysis unit, pharmacy, and a well-equipped laboratory.
</p>
</body>
</html>

<html>
<head>
<title>My city</title>
</head>
<body bgcolor="hotpink">
<h1 align="center">
<font color="azure" size="7px"><b>Ambattur</b></font>    
</h1>
<h3 align="center">
<font color="purple" size="6px" ><b>Naidu Hall</b></font>    
</h3>
<hr size="3" color="azure">
<p align="justify" style="font-size: larger; font-family: 'Times New Roman';">
<front face="New Times Roman"  size="5px">
Naidu Hall, a popular clothing store chain in Chennai, specializes in women's innerwear, lingerie, readymade blouses, sarees, casual wear, and accessories. Founded in 1939, it has grown to multiple branches across Tamil Nadu, offering quality and affordability. Their collections cater to women, men, and children, featuring trusted brands like Jockey and Triumph.The flagship store is located in Pondy Bazaar, T. Nagar, with other outlets in Anna Nagar, Adyar, and Vadapalani. Naidu Hall is renowned for personalized service and diverse product lines, including nightwear and ethnic wear​
</p>
</body>
</html>

<html>
<head>
<title>My city</title>
</head>
<body bgcolor="turquoise">
<h1 align="center">
<font color="darkslategrey" size="7px"><b>Ambattur</b></font>    
</h1>
<h3 align="center">
<font color="darkolivegreen" size="6px"><b>Oragadam</b></font>    
</h3>
<hr size="3px" color="seagreen">
<p align="justify" style="font-size: larger; font-family: 'Times New Roman';">
<front face="New Times Roman" color="darkolivegreen" size="6px">Oragadam, located near Chennai, is a rapidly developing industrial and residential hub. Known as South Asia’s largest automobile manufacturing center, it houses plants for global giants like Renault-Nissan, Hyundai, Daimler, and Ford. Other major industries, including Samsung, Motorola, and Apollo Tyres, have also established facilities here, contributing to its economic growth.
The area offers excellent infrastructure with well-connected roads, including the Chennai-Bangalore Highway and proximity to Sriperumbudur. It also supports sustainable living with modern residential townships like Hiranandani Parks, offering eco-friendly amenities, schools, and healthcare facilities. The area's industrial boom has made it a hotspot for real estate investments, combining economic and lifestyle advantages
</p>
</body>
</html>

```
## OUTPUT
![image](https://github.com/user-attachments/assets/b6674e80-efe7-4c98-8340-b87178a2d59d)
![alt text](<Screenshot (46).png>)
![alt text](<Screenshot (44).png>)
![alt text](<Screenshot (45).png>)
![alt text](<Screenshot (47).png>)
![alt text](<Screenshot (49).png>)

## RESULT
The program for implementing image maps 
using HTML is executed successfully.
