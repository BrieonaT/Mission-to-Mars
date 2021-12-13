### Project Overview

The intent of this project is to help a client named Robin, who dreams of working at NASA. Robin aims to gather data about the mission to Mars from multiple sites across the internet and collect it in a single location. She plans to build an automated webscraping app to update the data when new information comes out. In this project, we were tasked with helping Robin develop out the web app and connect it to a mongo database.

Initially, we were tasked with webscraping for the latest headlines of Mars news, a featured image and Mars facts. In the challenge however, we were tasked with adding in a scraping function for the full resolution images and titles of the hemispheres of Mars, along with adding it to the Flask webpage and MongoDataBase. 


### How to operate

To open up the application, you will need to open up Mongo via your command line. After that, you will need to open up a new command line terminal and type in 'python app.py'. If all goes well, you will be able to open up the HTML webpage in your browser and sucessfully scrape. If the webpage does not sucessfully scrape, it means you might not have the right conditions for your environment.

The scraped webpage will look like the following:
![Image of newest news and scraped newest image](https://github.com/BrieonaT/Mission-to-Mars/blob/main/Resources/Mars_news_image.png)

![Image of Mars facts](https://github.com/BrieonaT/Mission-to-Mars/blob/main/Resources/Mars_Facts.png)

![Image of Mars Hemi](https://github.com/BrieonaT/Mission-to-Mars/blob/main/Resources/Mars_Hemi.png)

Note: These images were taken on 12/13/2021, and if done at a later date might provide slightly different results due to the nature of scraping.


### Future Integration
A future way to improve or edit this repository would to be able to make it able to be used in GitHub's 'Pages' feature. This would allow people to not have to download the repository or have much technology expertise in order to view and play with the software.
