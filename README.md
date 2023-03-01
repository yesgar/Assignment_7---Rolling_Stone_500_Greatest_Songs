# Assignment_7---Rolling_Stone_500_Greatest_Songs
**Goal**:  
The main goal of this project was to determine which artist and genre reoccurred the most in Rolling Stone's 500 Greatest Songs. Additionally, I was also interested in discovering through bivariate analysis if there was a relation between TIME/BPM and BPM/YEAR between the songs in this data.

**API Documentation**:  
The API used to collect this data was BeautifulSoup.
https://beautiful-soup-4.readthedocs.io/en/latest/

**Data License**:  
I, YESENIA GARCIA, DO NOT CLAIM OWNERSHIP OF THE DATA PROVIDED. ALL CREDITS GO TO THE ORIGINATOR, CREATOR, AND OWNER OF THE MUSIC DATABASE:  
Dave Tompkins  
Continuing Lecturer  
Associate Director of Undergraduate Studies  
David R. Cheriton School of Computer Science  
Faculty of Mathematics  
University of Waterloo  
Dave Tompkins Link: https://cs.uwaterloo.ca/~dtompkin/index.html  
Dave Tompkins Music Database Link: https://cs.uwaterloo.ca/~dtompkin/music/index.html

My handling of this data is strictly for EDUCATIONAL PURPOSES ONLY for a course project in I310D at The University of Texas at Austin by extracting, transforming, and distributing the data (including in data.world) to create an informative graph. This data is NOT FOR COMMERCIAL PURPOSES, as stated in Dave Tompkins music database website:  
**"Please note that this is an educational and recreational website, not a commercial website:**  
**- I do not sell music**  
**- I do not download music**  
**- I do not distribute my music"**  
To reiterate, considering that Dave Tompkins's music database website did not list a license, the handling and usage of this data is strictly only for non-commercial purposes. I am releasing this data as a part of an academic project, and therefore for an educational purpose and not commercial use. Therefore, this data may only be used for educational purposes and non-commercial purposes with attributions or credit to the author and creator, Dave Tompkins. However, if you are wanting to use this data for commercial application, contact the author of the website, Dave Tompkins.

**Data Attribute Data Types and Descriptions**:  
#: (Data Type = int) This column signifies the ranking of the songs in Rolling Stone's 500 Greatest Songs (1 being the best)  
ARTIST: (Data Type = str) This column signifies the artist of the songs in Rolling Stone's 500 Greatest Songs  
TITLE: (Data Type = str) This column signifies the title of the songs in Rolling Stone's 500 Greatest Songs  
TIME: (Data Type = float) This column signifies the time or length of the songs in minutes in Rolling Stone's 500 Greatest Songs  
BPM: (Data Type = float) This column signifies the beats per minute of the songs in Rolling Stone's 500 Greatest Songs  
YEAR: (Data Type = int) This column signifies the year the song was released in Rolling Stone's 500 Greatest Songs  
GENRE: (Data Type = str) This column signifies the genre of the songs in Rolling Stone's 500 Greatest Songs  
DISC-TRACK: (Data Type = str) This column signifies the disc-track of the songs within the original websites database in Rolling Stone's 500 Greatest Songs  
DETAILS: (Data Type = str) This column signifies the details of the songs within the original websites database in Rolling Stone's 500 Greatest Songs (including track classification, audio, lyrics, etc.)  

**Potential Data Issues**:  
In terms of the Rolling Stone - 500 Greatest Songs data, there may be issues of sources of bias in the orginial collection considering it was derived from a single individuals educational website. Furthermore, there seems to be a few gaps regarding the datapoints attribute of Genre as well as no clear indication of when the data was made. Some points that the orignial author of the music database, Dave Tompkins, lists are stated exactly as the following:  
- There are many typos and errors -- especially in the CapitAliZation in song names  
- The year and genre data is currently a bit of a mess, but I'm working on it  
Additionally, dataset being uploaded to data.world resulted in warning messages including:  
- 1 column detected with constant values (which is expected due to the originial data formatting)
- 1 suspicious row count detected  
- 3 numeric values outside standard deviation detected  
- 5 text values outside standard deviation detected  

**Analysis**:  
Through this project I am demonstrating which artist and genre reoccurred the most in Rolling Stone's 500 Greatest Songs in order to get a better idea of which artists and genres Rolling Stone identifies as "the greatest" in comparison to other large music led magazine companies such as Billboard. By finding similarities and differences between a range of major music rating companies, there can be a collective consensus of what can be determined as the "greatest" music considering that this is an area that can be greatly subjective. Additionally, through bivariate analysis, being able to determine if there is a relation between TIME/BPM and BPM/YEAR between the songs in this data may make for insights that, although weren't my main focus in this project, may be able to provide any interesting correlations since (for example) in music, tempo refers to a specific number of beats that occur within a minute and this measure of time states the speed at which music is played in beats per minute or BPM.
