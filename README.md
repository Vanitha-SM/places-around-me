# Places Around Me
## AIM:
To develop a website to display details about the places around my house.

## Design Steps:

###Step 1:
Open up a terminal in your preffered location, and start a django project using djang-admin startproject <your-project-name> Next setup an app inside the project folder using django-admin startapp <your-app-name>

###Step 2:
Once Created ,link your app to the project by adding it in the list of apps in settings.py file located inside the project folder. Add access to your host in allowed host setting and add static folders path to your settings.py file.

###Step 3:
Create a static folder and template folder and add all your required files for the project - Images .etc in your static folder. In the Template folder add your html files required for the pages.

###Step 4:
Head to the views.py in your app folder and create required functions to render a particular page or template when requested by the client. Next go to the urls.py and route the correct view functions to each particular request as needed.

###Step 5:
Next start the server from the projects main directory using python3 manage.py runserver 0:<portnumber>. Now the pages can be accessed from all the routed addresses in urls.py .

## Code:

<!DOCTYPE html>
<html lang="en">
    <head>
        <title>My City</title>
    </head>
    <body>
        <h1 align="center">
            <font colour="red"><b>Nanganallur</b></font>
        </h1>
        <h3 align="center">
            <font colour="blue"><b>Vanitha S(22008870)</b></font>
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
## Output:

## Result:
The program for places around me through image mapping is completed successfully.
