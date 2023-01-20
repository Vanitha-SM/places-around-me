# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

<<<<<<< HEAD
## Step 1: 
Open up a terminal in your preffered location, and start a django project using djang-admin startproject Next setup an app inside the project folder using django-admin startapp
=======
## Step 1:
Open up a terminal in your preffered location, and start a django project using djang-admin startproject <your-project-name> Next setup an app inside the project folder using django-admin startapp <your-app-name>

## Step 2:
Once Created ,link your app to the project by adding it in the list of apps in settings.py file located inside the project folder. Add access to your host in allowed host setting and add static folders path to your settings.py file.

## Step 3:
Create a static folder and template folder and add all your required files for the project - Images .etc in your static folder. In the Template folder add your html files required for the pages.

## Step 4:
Head to the views.py in your app folder and create required functions to render a particular page or template when requested by the client. Next go to the urls.py and route the correct view functions to each particular request as needed.

## Step 5:
Next start the server from the projects main directory using python3 manage.py runserver 0:<portnumber>. Now the pages can be accessed from all the routed addresses in urls.py .
>>>>>>> bc629c2ad5478e0c8218884f1bd5b26925a4de69

## Step 2:
 Once Created ,link your app to the project by adding it in the list of apps in settings.py file located inside the project folder. Add access to your host in allowed host setting and add static folders path to your settings.py file.

## Step 3:
 Create a static folder and template folder and add all your required files for the project - Images .etc in your static folder. In the Template folder add your html files required for the pages.

## Step 4: 
Head to the views.py in your app folder and create required functions to render a particular page or template when requested by the client. Next go to the urls.py and route the correct view functions to each particular request as needed.

## Step 5:
 Next start the server from the projects main directory using python3 manage.py runserver 0:. Now the pages can be accessed from all the routed addresses in urls.py .
## Code:

## index.html
<<<<<<< HEAD

=======
    
>>>>>>> bc629c2ad5478e0c8218884f1bd5b26925a4de69
<!DOCTYPE html>
<html lang="en">
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font colour="red"><b>Nanganallur</b></font>
        </h1>
        <h3 align="left">
            <font colour="blue"><b>Click on the location for details</b></font>
        </h3>
        <center>
            <img id="Image-Maps-Com-image-maps-2023-01-13-033840" src="places.png" border="0" width="1835" height="959" orgWidth="1835" orgHeight="959" usemap="#image-maps-2023-01-13-033840" alt="" />
            <map name="image-maps-2023-01-13-033840" id="ImageMapsCom-image-maps-2023-01-13-033840">

                <area  alt="" title="Nanganallur Anjaneyar Temple" href="anjaneyar.html" shape="rect" coords="1358,664,1408,714" style="outline:none;" target="_self">
                <area  alt="" title="Pazhavanthangal Railway Station" href="railways.html" shape="rect" coords="1039,460,1089,510" style="outline:none;" target="_self"     />
                <area  alt="" title="Kendriya Vidyalaya" href="kv.html" shape="rect" coords="932,381,984,431" style="outline:none;" target="_self">
                <area  alt="" title="Arthanareeswarar Temple" href="at.html" shape="rect" coords="1066,731,1118,781" style="outline:none;" target="_self">
                <area  alt="" title="Chennai International Airport" href="airport.html" shape="rect" coords="202,267,307,376" style="outline:none;" target="_self">
                <area shape="rect" coords="1833,957,1835,959" alt="Image Map" style="outline:none;" title="Image Map" href="https://www.image-maps.com/" />
                
            </map>
        </center>
    </body>
</html>
<<<<<<< HEAD

## airport.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Chennai International Airport</title>
    </head>
    <body bgcolor="Lime">
        <h1 align="center">
            <font color="red"><b>Nanganallur</b></font>
        </h1>
        <h3 align="center">
            <<font color="blue"><b>International Airport Of Chennai</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="San serifs" size="5">
                <b>
                    Chennai International Airport (IATA: MAA, ICAO: VOMM) is an international airport serving the city of Chennai, Tamil Nadu and its metropolitan area. It is located in Meenambakkam, around 20 km southwest of the city centre. Chennai International Airport is the 4th busiest airport in India and third busiest airport for international traffic in India. It was also 49th busiest airport in Asia in 2018 making it one of the four major airports in India under the top 50 list of 2018. In financial year 2021, the airport handled 9.53 million passengers.

The airport is served by the airport metro station of the Chennai Metro and the Tirusulam railway station of the Chennai Suburban Railway system. To cope with the passenger traffic, two new terminals, including one satellite terminal, are under construction to handle 40 million passengers per year.Once completed, it will be India's first airport to have a satellite terminal. The new satellite terminal will be connected through a four way underground walkalator for passenger movement across different terminals. Still, the Tirusulam airport complex is expected to reach saturation by 2035, with a peak capacity of 40 million passengers, and a proposal for a new greenfield airport in Parandur has been approved. Once the new airport is commissioned, both the airports will be functional.
                </b>
            </font>
        </p>
    </body>
</html>

## anjaneyar.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Nanganallur Anjaneyar Temple</title>
    </head>
    <body bgcolor="lime">
        <h1 align="center">
            <font color="red"><b>Nanganallur</b></font>
        </h1>
        <h3 align="center">
            <<font color="blue"><b>Nanganallur Anjaneyar Temple</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="San serifs" size="5">
                <b>
                    he Anjaneya Temple at Nanganallur, Chennai is a Hindu temple dedicated to the god Hanuman. The principal idol of Hanuman is 32-feet tall and sculpted from a single piece of granite, which the second tallest Hanuman after Panchavatee near Puducherry. 
                    The idol was installed in 1989 and consecrated in 1995. Sri Maruthi Bhaktha Samajam Trust, consisting of people with high spiritual beliefs, wished for this temple. Sri Chandrashekarendra Saraswati mahaswamiji of Kanchi Mutt entrenched the 32-foot idol 
                    of Anjaneyar in 1989 and consummated the Kumbabishekam in 1995. The distinguished factor of the 32-feet idol is that it was molded out of a single rock. 
                 </b>
            </font>
        </p>
    </body>
</html>

## at.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Arthanareeswarar Temple</title>
    </head>
    <body bgcolor="Lime">
        <h1 align="center">
            <font color="red"><b>Nanganallur</b></font>
        </h1>
        <h3 align="center">
            <<font color="blue"><b>Arthanareeswarar Temple</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="San serifs" size="5">
                <b>
                    This Hindu temple is located in Nanganallur, Chennai and is dedicated to Lord Shiva.
According to the historical legend, an old man once tried to clean the tank or pond in his land. While cleaning, he found idols of the temple in the tank submerged and buried. These idols were immediately cleaned and moved to a tent with a thatched roof. At the beginning, worshipping of these idols began by the lighting of lamps. The Hindu temple was built later on.
As the deity’s idol was under water for a long period, he is known as Jalakandeswarar( Jal standing for water). Later on the name was changed to Arthanareeswara. Arthanareeswara is the form of the supreme being representing both male and female forms at the same time. The devotee worshipping the Linga found at this Indian temple, accept the concept of worshipping Shiva and Devi together.
                </b>
            </font>
        </p>
    </body>
</html>

## kv.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Kendriya Vidyalaya</title>
    </head>
    <body bgcolor="Lime">
        <h1 align="center">
            <font color="red"><b>Nanganallur</b></font>
        </h1>
        <h3 align="center">
            <<font color="blue"><b>Kendriya Vidyalaya</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="San serifs" size="5">
                <b>
                    The Kendriya Vidyalaya Sangathan (transl. Central School Organization) is a system of central government schools in India that are instituted under the aegis of the Ministry of Education, Government of India. As of July 2022, it has a total of 1,248 schools in India, and three abroad in Moscow, Tehran and Kathmandu. It is one of the world's largest chains of schools and also the largest chain of schools in India is controlled by 25 Regional Offices and 05 ZIETs (Zonal Institute of Education and Training) under KVS (HQ).

The Kendriya Vidyalaya Sangathan follows the vision of "imparting knowledge/values and nurturing the talent, enthusiasm and creativity of the students and for seeking excellence through high-quality educational endeavours.
                </b>
            </font>
        </p>
    </body>
</html>

## railways.html

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>Pazhavanthangal Railway Station</title>
    </head>
    <body bgcolor="Lime">
        <h1 align="center">
            <font color="red"><b>Nanganallur</b></font>
        </h1>
        <h3 align="center">
            <<font color="blue"><b>Pazhavanthangal Railway Station</b></font>
        </h3>
        <hr size="3" color="red">
        <p align="justify">
            <font face="San serifs" size="5">
                <b>
                    Pazhavanthangal railway station is one of the railway stations of the Chennai Beach–Chengelpet section of the Chennai Suburban Railway Network. It serves the neighbourhood of Pazhavanthangal and surrounding areas. It is situated about 18 km (11 mi) from Chennai Beach, and has an elevation of 12 m (39 ft) above sea level.
Pazhavanthangal railway station lies on the Madras Beach—Tambaram suburban section of the Chennai Suburban Railway, which was opened to traffic on 11 May 1931. The tracks were electrified on 15 November 1931.[1] The section was converted to 25 kV AC traction on 15 January 1967
                </b>
            </font>
        </p>
    </body>
</html>

## Output:
![out1](/out1.png)
![out2](/out2.png)
![out3](/out3.png)
![out4](/out4.png)
![out5](/out5.png)
![out6](/out6.png)
=======
## Output:
    ![Screenshot (65)](https://user-images.githubusercontent.com/119557985/213361222-207448c4-5151-4755-b261-5d50f709d723.png)


>>>>>>> bc629c2ad5478e0c8218884f1bd5b26925a4de69
## Result:
The program for places around me through image mapping is completed successfully.
