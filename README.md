# Module10-Mission-to-Mars;

Robin had been admiring images of Mars’s hemispheres online and realized that the site is scraping-friendly. She would like to create web app to include all four of the hemisphere
images. 
<br> 
To do this, we will use BeautifulSoup and Splinter to scrape full-resolution images of Mars’s hemispheres and the titles of those images, to store the scraped data on a Mongo database. Then  use a web application to display the data, and alter the design of the web app to accommodate these images.

Mission to Mars ipynb is the starting point; with the help from [Missionto Mars Challange.ipynb](https://github.com/4renginy/Module10-Mission-to-Mars/blob/main/mission%20to%20mars%20challange.ipynb)file we created the scrap.py file.

[scraping.py](https://github.com/4renginy/Module10-Mission-to-Mars/blob/main/scraping.py) will go out the web and scrap what we wanted with the help of splinter and beautiful soup. 
[app.py](https://github.com/4renginy/Module10-Mission-to-Mars/blob/main/app.py) file will put all this information into mongo database with the help of flask.

Now we collected all the inforamtion from web it is time to present it. The way we did is creating an index.html file. This file will have info about Mars pictures, Mars facts, Weather and Hemisphare information and pictures. We also added a button to scrape the latest info as soon as we click on it.

The web page looks like this;
[!Mission_to_Mars_indexpage](https://github.com/4renginy/Module10-Mission-to-Mars/blob/main/missionto%20mars.PNG)









