# jackson-portfolio
Working portfolio for Advanced GIS (Spring 2020).

# About Me
My name is Victoria Jackson and I am a second-year MSPPM with a concentration in Urban and Regional Economic Development. I grew up as a military kid moving across the United States, but I most recently hail from the land of Cheerwine and Bojangles (otherwise known as North Carolina). I graduated from Davidson College in 2012 with the idea that I would pursue a career in education, or at least working with kids. To that end, I taught in a middle school for two years before working as a Teen Services Specialist at ImaginOn, a branch of Charlotte-Mecklenburg Library. My experiences working in those environments led me to pursue a public policy degree for reasons that are probably too long to sum up in this introduction. I'll just say that my goal now is to provide opportunities for communities that haven't had access to them. 

Other than that, the essentials about me: I love burgers, live theater, and singing way off-key in my car. My current hobbies include muay thai and improving my Spanish fluency. And... 

# What I Hope to Learn
...I hope to improve upon the skills that I learned in my prior GIS class! As a visual learner, I really appreciate the power of being able to visualize data to make information accessible to as many people as possible. Given this, I really hope to learn how to effectively visualize map data across multiple platforms so I can do this work without relying one type of software. 

As a policy student, I hope to learn more about the ethics behind collecting mapping data; particularly when people are not aware of how much of their personal data they are giving up. Having not taken any technology/privacy courses, I hope this class can serve as a start to understanding the ins-and-outs of this subject.   

# Portfolio



## Lab Assignment: Geographic Footprint ##
__Assignment: Use the open-source, geospatial tool [Kepler](https://kepler.gl/) to map [412 Food Rescue](https://412foodrescue.org/) pick-up and delivery data.__

The following screenshots are of maps analyzing volunteer trips from point of origin to destination over multiple months. The blue arcs signify the origins and the red arcs the destinations of the pick-ups.

![412KeplerArcMap](https://github.com/jacksonvict/jackson-portfolio/blob/master/412KeplerArcMap.png?raw=true)

![412KeplerArcMapIII](https://github.com/jacksonvict/jackson-portfolio/blob/master/412KeplerArcMapIII.png?raw=true)





## Lab Assignment: Custom ArcGIS Map ##
__Assignment: Create a custom ArcGIS basemap style based on something interesting or inspiring__

![TheGoodPlace](https://media.giphy.com/media/xULW8i1lsTvYAyJgVW/giphy.gif)
###### Credit:[@thegoodplace GIPHY](https://giphy.com/gifs/xULW8i1lsTvYAyJgVW/html5) ######





## Lab Assignment: Mapbox
__Assignment: Follow the tutorial to learn how to do basic mapping with Mapbox.__

The final product can be found [here](https://api.mapbox.com/styles/v1/jacksonvict/ck8o3sjcm37x51is66x8hys4f.html?fresh=true&title=view&access_token=pk.eyJ1IjoiamFja3NvbnZpY3QiLCJhIjoiY2s4NmZzajQzMGY0MTNmbGo0anMzZXdvaiJ9.f2oyXTDNtXVS76FqydAVwA)

__Reflection__

Arguably, Mapbox was the most frustrating experience I had with any of the mapping programs to date. The experience required multiple attempts at troubleshooting. Initially, the program would not accept my JSON files for county prescriptions because of the size of the file. In my second attempt, I tried to upload the CSV files under tilesets, but they were rejected. Interestingly,  Mapbox gives an option to covert datasets into tilesets so I uploaded both the state and county CSV files as two separate datasets as a work around. This resulted in point features rather than an actual shape. I began my third work-around to use the shapefiles (which took an inconvenient amount of time to load). This worked.

One thing that I did not enjoy about Mapbox was the inability to move the layers. I am unsure in anybody else ran into this issue, but I was only able to move the layers created from my tiles sets. All other feature layers had to be moved as a group, though I did have the option of turning sub-layers off and on.  Additionally, looking at my published map, I do not see a key to explain the graduated coloring. I may have missed a step, but I am not sure how useful this map would be as a deliverable to explain the data to someone unfamiliar with it. 

Despite these frustrations, I did like Mapbox as an alternative to ArcGIS though I feel like I would do all my work beforehand in ArcGIS. I do not have a lot of experience with JSON and could not understand what I needed to fix to make my CSV file work, so I had to rely on what I could do in GIS. However, if the files were already formatted, I believe I would find it useful for producing a comparative map. I would be interested to see what other types of analysis could be done with Mapbox.

