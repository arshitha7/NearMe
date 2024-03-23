# Ex04 Places Around Me
## Date: 23/03/2024

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
### map.html
```
<html>
    <head>
        <title>
            My City
        </title>
    </head>
    <body>
        <h1 align="center">
            <font color="red"><b>Nagercoil</b></font>
        </h1>
        <h3 align="center">
            <font color="blue"><b>Arshitha MS (212223240015)</b></font>
        </h3>
        <center>
            
<map name="MyCity">
    <area shape="rect" coords="100,100,900,900" href="expmap.html" title="My Home Town"</map>
    

    <img src="map.png" usemap="#image-map">

<map name="image-map">
    <area target="_blank" alt="St Xavier's Catholic College of Engineering" title="St Xavier's Catholic College of Engineering" href="xavier.html" coords="964,84,1154,184" shape="rect">
    <area target="_blank" alt="Suchindram" title="Suchindram" href="suchindram.html" coords="1676,521,1800,576" shape="rect">
    <area target="_blank" alt="Parvati Amman Temple" title="Parvati Amman Temple" href="parvati.html" coords="1222,609,97" shape="circle">
    <area target="_blank" alt="Kottar" title="Kottar" href="kottar.html" coords="1544,416,1676,472" shape="rect">
    <area target="_blank" alt="S.N.Hospital" title="S.N.Hospital" href="sn.html" coords="1474,544,1666,616" shape="rect">
</map>
        </center>
    </body>

</html>
```
### xavier.html
```
<html>
    <head>
        <h1 align ="center"><font color="brown" >St Xavier's Catholic College of Engineering</font></h1>
    </head>
    <body style="background-color:rgb(188, 219, 243);">
        
        
         <h4 align="center" ><img src="xavier.png" width="300" height="300"></h4>
        
        
        <h2 align="center"><font color="blue">About Xavier College</font></h2>
        <p>
                     St. Xavier's Catholic College of Engineering is an Autonomous institution 
            which is owned,administered and run by the Roman Catholic Diocese of Kuzhithurai. 
            Rev. Dr. M. Maria William is the current Correspondent of the college.
            It was established in 1998 by the Roman Catholic Diocese of Kottar. 
            It is located 5 km west of main town Nagercoil.
            The college is approved by the government of Tamil Nadu and is recognized by 
            AICTE, New Delhi. The college is affiliated to 
            Anna University, Chennai.
        </p>
        <p>
                     The college is situated in the lap of the Western Ghats at 
            Chunkankadai in Kanyakumari District, overlooking the highway, NH 47. In June 2002,
             the institution was awarded the ISO 9001:2000 certificate by STQC certification services.
            The institution has been accredited by the National Assessment and 
            Accreditation Council (NAAC) with 'A' Grade. 
            All UG Programs of the institution, except B.Tech.(AI&DS), are accredited by 
            National Board of Accreditation (NBA) and all courses
            are permanently affiliated by Anna University, Chennai. The college is recognized under 
            2f&12B of the UGC act, 1956.
        </p>
    </body>
</html>
```
### suchindram.html
```
<html>
    <head>
        <h1 align ="center"><font color="brown" >Suchindram</font></h1>
    </head>
    <body style="background-color:rgb(198, 150, 150);">
        
        
         <h4 align="center" ><img src="suchindram.png" width="500" height="300"></h4>
        
        
        <h2 align="center"><font color="blue">About Suchindram</font></h2>
        <p>
            Suchindram is located at Kanyakumari District.[1] It has an average elevation of 19 metres (62 feet).

            Suchindram is a temple town situated in the southernmost district of Kanyakumari in Tamil Nadu, India.
            It is 11 km from Kanyakumari city and 7 km from Nagarcoil town 105 km from adjacent Tirunelveli district
            and approximately 81 km from Trivandrum city. The town of Suchindrum is renowned for the 
            Thanumalayan Temple and was an important citadel of Travancore.
        </p>
        <p>
            Suchindram is a panchayat town in Kanyakumari district in the Indian state 
            of Tamil Nadu with Indian postal code as 629704. It is an important pilgrim centre 
            and the site of the famous Thanumalayan Temple. There is an Anjaneya, (or Hanuman), statue 
            which stands at 22 feet (6.7 m) and is carved of a single granite block.
        </p>
    </body>
</html>
```
### parvati.html
```
<html>
    <head>
        <h1 align ="center"><font color="brown" >Parvati Amman Temple</font></h1>
    </head>
    <body style="background-color:rgb(247, 195, 195);">
        
        
         <h4 align="center" ><img src="parvati.png" width="500" height="400"></h4>
        
        
        <h2 align="center"><font color="red">About Parvati Amman Temple</font></h2>
        <p>
            The Mandaikkadu Bhagavathi Amman Temple is dedicated to 
            Goddess Parvati also known as Bhagavathi. This temple is located near Nagercoil-colachel 
            state highway in the town of Mandaikkadu. Many legends associated with the temple 
            along with a beautiful sea shore location add to its sanctity of this temple. 
            This makes it a sought after pilgrim center for people from Kerala and Tamil Nadu. 
            Simple Kerala style architecture and an earthy idol of the presiding deity will delight 
            and calm you at the same time. It is said that one day Sri Guru Shankaracharya along with his
             Keralite disciples were performing a Srichakra Puja. It so happened that the chakra 
             did not return back after the puja got over, as it usually did. 
        </p>
    </body>
</html>
```
### sn.html
```
<html>
    <head>
        <h1 align ="center"><font color="brown" >S.N.Hospital</font></h1>
    </head>
    <body style="background-color:rgb(193, 236, 187);">
        
        
         <h4 align="center" ><img src="sn.png" width="500" height="400"></h4>
        
        
        <h2 align="center"><font color="darkgreen">About S.N.Hospital </font></h2>
        <p>
            S N Super Speciality Hospital has been providing quality healthcare services 
            in the region to the people with their diverse medical needs. Under the visionary leadership
             and committed management, S N Super Speciality Hospitals has evolved as a Centre of excellence 
             in Health Care Services with  the highest quality standards (NABH) of medical treatment to 
             all sections of the society.  We are driven and motivated by the requirements of patients. 
             We are committed to your good health and well being. We take pride in providing Multi- Speciality 
             medical care under one roof with highly experience and qualified Doctor’s, Nursing and Support Staff.
        </p>
    </body>
</html>
```
### kottar.html
```
<html>
    <head>
        <h1 align ="center"><font color="brown" >Kottar</font></h1>
    </head>
    <body style="background-color:rgb(207, 205, 233);">
        
        
         <h4 align="center" ><img src="kottar.png" width="500" height="400"></h4>
        
        
        <h2 align="center"><font color="red">About Kottar</font></h2>
        <p>
            Kottar is a locality and a bazaar area of Nagercoil, Tamil Nadu state, 
            in the southernmost part of Peninsular India; though a part of Nagercoil today, 
            it is the original town around which the city of Nagercoil grew. It was an 
            ancient trade centre of both Pandyans and Cheras at various times. The ancient 
            mercantile centre of Kottar was established on the banks of the Pahrali River (Pazhayar).

        Robert Caldwell describes the extent of Malayalam in the mid 19th century as extending
        from the vicinity of Mangalore in the north where it supersedes with Tulu and Kannada to
        Kottar beyond Pahrali River near Kanyakumari in the south where it begins to supersede with 
        the Tamil and from Malabar Coast in the west to Western Ghats in the east besides the 
        inhabited islands of Lakshadweep in the Arabian Sea.[note 1]
        </p>
    </body>
</html>
```


## OUTPUT
### map.html
![output1](<map out.png>)
### xavier.html
![output2](<xavier out.png>)
### suchindram.html
![output3](<such out.png>)
### parvati.html
![output4](<parvati out.png>)
### sn.html
![output5](<sn out.png>)
### kottar.html
![output6](<kottar out.png>)


## RESULT
The program for implementing image maps using HTML is executed successfully.
