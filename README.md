# Women's lectures in Italy, 1880–1930: thematic map prototype

**[View the interactive map](https://daniv1t.github.io/lectures_topics_prototype2026/)**

For this prototype, a corpus of 378 lectures given by women between 1880 and 1930 was organised in a CSV file, with information about the lecturers, places, dates and publications. I then indexed these lectures according to eleven themes, recorded in binary (yes/no) columns, so that a single lecture could be associated with several themes.
After checking and cleaning the data, particularly the geographic coordinates that had been altered while handling the file, I used R and the Leaflet package to create an interactive map of 295 lectures; the remaining 83 cannot yet be located. For 130 lectures with unusable coordinates, I reused those of another lecture held in the same city. 
These locations are therefore accurate at city level but do not necessarily correspond to the exact venue.

Each theme forms a separate layer, identified by its own colour and available to switch on or off, while pop-up cards provide the main information about each lecture. A lecture associated with several themes appears in each relevant layer, but it is counted only once in the corpus total. Lectures without an assigned theme appear in the “Not classified” layer.
