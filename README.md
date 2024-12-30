# New York City Evictions Data Sonification

In the midst of an affordable housing crisis, New York City has faced an ongoing problem of eviction. In 2017, the city reached a peak level of evictions, with over 20 thousand New Yorkers being asked to leave their home. While the COVID-19 pandemic moratorium gave New Yorkers a break from this threat, evictions are now back on the rise. This data sonification conveys the rate of housing evictions in New York City from January 2017 to October 2024.  

Higher monthly eviction rates are mapped to louder, lower-pitched notes, and lower monthly eviction rates are mapped to quieter, higher-pitched notes. Each passing year is marked with a triangle ding. News segment audio is also layered into the sonification to indicate important events and societal changes. Cricket sounds mark the Covid-19 pandemic.  

### Sonification:
* Audio-only: [nyc-evictions-sonification.wav](https://github.com/awalmer/NYC-Evictions-Sonification/blob/main/nyc-evictions-sonification.wav)
* Audio-visual: [YouTube video](https://youtu.be/8h3_ijIudHo?si=W0mxN-3d_uELJy8Z) (includes narration, training listening, and animated data visualization)

### References:
* Matt Russo's [Tutorial](https://youtu.be/DUdLRy8i9qI?si=vGBBpAzAX5cnGiZp) on YouTube (I adapted this method)
* Original [Python script](https://github.com/SYSTEMSounds/sonification-tutorials/blob/main/data2midi-part1.py) on GitHub
* Data from [NYC OpenData](https://data.cityofnewyork.us/City-Government/Evictions/6z8x-wfk4/data_preview), inspired by [Data Is Plural](https://www.data-is-plural.com/archive/2024-09-25-edition/) (thanks, Jeremy Singer-Vine!)
* Audio clips from YouTube and [freesound.org](https://freesound.org/)
* Logic Pro X for audio editing

### Design Rationale:
**Mapping:** Lower, louder notes correspond to larger eviction rates, while higher, quieter notes correspond to smaller eviction rates. I made this choice because the deeper notes have a more resounding, impactful effect.
**Musical key:** C Aeolian. Thematically, the topic of resident evictions is a somber one. I wanted the tone to reflect that.
**Additional audio:** I captured audio from news segments on YouTube, as well as cricket sounds from freesound.org. The news segments are meant to help tell the story and inform the reader what historical/legislative events are happening over time.
**Additional time marker:** The trianlge sound indicates the passing of each year (temporal context).

### Original Publication (RJI Fellowship Article)
* Article, ["Customization is key to a compelling sonification"](https://rjionline.org/news/customization-is-key-to-a-compelling-sonification/)
* [GitHub repository](https://github.com/awalmer-rji/NYC-Evictions-Sonification/) with materials for readers to replicate the sonification process

### About Author:
Aura Walmer  
www.aurawalmer.com  
aurawalmer@gmail.com

