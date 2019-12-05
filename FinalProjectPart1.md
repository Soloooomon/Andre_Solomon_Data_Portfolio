# Final Project (Part I)
## Outline
### Summary
For the final project, I will analyze my own personal Spotify data, particularily self-curated playlists, from 2019 thus far to formulate a tailored guide that will represent new musical selections for consumption in the upcoming year 2020. Besides pursuing my own data, I am interested in comparing myself versus the "average" U.S. individual, in terms of each group's musical prospects for 2020. 

I was spured to tackle this project due to skeptism on Spotify's "Discover" playlists, which seems inconsistent and/or lacks satisfaction. In the Digital Age of the 21st Century, we have permitted computers and algorhythms to dicate choice, therefore, I am looking to present a chance to customize musical journeys that allign with individuals' specific musical tastes. Basically, implementing step-by-step analysis instructions. Many Americans, no the world, listen to music on the daily, so why not have the best music that fits you? 
#### Challenges
I do believe that this project will provide challenges. 
Here are some examples:
- Overwhelming Data: Since I will be collecting data from a year's worth of music it might provide challenging to complie it all
- Project Simplicity: With the goal of curating two playlists based on interest, might be difficult to have a lot of meaningful content
- Research: Since part of the data collection will require me to do some digging into new musical content, this could be laborious/difficult in selecting appropriate items for the playlists

### Project Structure
The project will begin looking at two datasets: Spotify's Current Top 200 Songs from the U.S. (Pulled 11/13/19) and André Solomon's 2019 Spotify data (primarily from André created playlists). Looking at both data structures, it ultimately has to be organized into buckets: Genre/Mood, Artists, Albums, and Songs. Since the objective is to discover new songs for consumption, there will be limitations on selected songs, no songs that are found prior 2018 will not be considered. Once songs are put into buckets, the analysis of trend data will commence. For example, knowing that one of my top played genres is "Pop" then I can elimiinate genres that do not match that stipulation, and the same prinicple can be ultizied on the reamining buckets. Once the elimination process has been completed, there will be a truncated list of the trend data. Due to the massive amounts of music, there will have to be barriers on selection. Therefore, selction will be based on these guidlines:

- Top 5 Genres
- Top 10 Artists
- Top 20 Albums 
- Top 30 Songs

I believe that this will give enough content to conduct a deeper analyzation of the music. (Note the same principle will be applied towards the 2020 selections). After these have been determined, I will have to do some personal digging on both what the average U.S. individual and I should listen to. Ultimately, creating two new playlist. Refering back to the guidlines, the new playlists will involve the same characteristics, enough content to have a solid musical selection for the start of the new year. 
#### User Story/Motivation
For the reader, I want them to understand the process of making intentful music selections, a way to discover music that authentically resonates with their tastes. 
#### Call to Action
Map your musical interests to determine what new music alligns to you personally. 
## Initial Sketches
![Initial Sketches](https://user-images.githubusercontent.com/54474707/68827062-cafd7980-066e-11ea-8eed-4a9e998a8f7f.png)
## The Data
<div class='tableauPlaceholder' id='viz1574032677482' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;U_&#47;U_S_TopChartsSpotify&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='U_S_TopChartsSpotify&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;U_&#47;U_S_TopChartsSpotify&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1574032677482');var vizElement = divElement.getElementsByTagName('object')[0];vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>

To my advantage, Spotify publically shares their data. The U.S. Top Charts for 2019 (Songs) can be found on Spotify's [public website](https://spotifycharts.com/regional) which shows the top charts both weekly and daily in various regions in the world. 

In terms of my own Spotify data anyone with an account (free or premium) can request their own personal data. 

Here is the way to obtain it: 

- Visit Spotify's website 
- Go to your account page
- Click the *Privacy* tab 
- Scroll all the way down and view the section titled *Download your Data* 

There contains a three step process where you have to...
1. Request the Data 
2. Wait for the data to be complied (30 day max) 
3. Download the data (comes in a JSON format) 

Here is a sample of my personal Spotify data: 
<div class='tableauPlaceholder' id='viz1574034754165' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Sa&#47;SamplefoAndresSpotifyData&#47;Sheet2&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SamplefoAndresSpotifyData&#47;Sheet2' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Sa&#47;SamplefoAndresSpotifyData&#47;Sheet2&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='filter' value='publish=yes' /></object></div><script type='text/javascript'>var divElement = document.getElementById('viz1574034754165');var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';var scriptElement = document.createElement('script');scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);</script>

<iframe src="https://open.spotify.com/embed/playlist/2TsPeivv5iidS2iztvx7xs" width="300" height="380" frameborder="0" allowtransparency="true" allow="encrypted-media"></iframe>

### Using the Data
As I mentioned previously, I will use both the United States' and my spotify data to structure the top favorite genres, artists, and songs for each participant. Overall, a way to curate two playlists, (one for the U.S. and another for myself) which will allow both parties to tap into new musical content for the start of 2020 that more efficiently guages interest. Additionally, provide simple instructions for individuals to conduct analysis on their own; a way to give every individual the opprounity to shape their own musical journey. To create these playlists it will require me to tap into Spotify's music library and test out new content to determine if it resonates with both parties' interests.

With Spotify's *Discover* feature, I am often skeptical of the methods. Therefore, I will also conduct research that  conentrates on the questions: Does  Spotify's discover feature incoprorates clout? More so, are well-known artists given the opprotutnity to be "discovered" over others? Is there monetary transactions that take place? What factors go into understanding an individual's musical taste?

Lastly, besides the final outcome of creating playlists and conducting critical research, I want to present standard graphs on a Tableau Dashboard that will track stream use and popularity  
## Method/Medium
### Story Platform
For the project I will be utilizing the digital platform *Shorthand* to map out my data story. 
### Recording Data & Graphing 
For measuring and presenting the data I will take advantge of *Tableau* to host all of the excel data and [Tableau Public](https://public.tableau.com/profile/andre8313#!/) to allow my dashboard to be presented publically with my readers
### Brainstorms/Sketches
To collect my thought process throughout this project, I will use a mixture of the digital platform *Balsmiq* and paper documents
# [Back to Home](/README.md)
