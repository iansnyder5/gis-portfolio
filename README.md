# isnyder-portfolio
This is my portfolio for 90-753: Advanced GIS, at Carnegie Mellon University's Heinz College. My portfolio lives at http://iansnyder5.github.io/isnyder-portfolio/

# About me

Pronouns: He/Him/His. I'm a second-year MSPPM-DC student at Carnegie Mellon University's Heinz College of Information Systems and Public Policy. I'm originally from the Philadelphia area (Montgomery County, for those with any familiarity). I spent four wonderful years at the University of Pittsburgh, where I graduated with a Bachelor of Arts in Political Science and a Neuroscience Minor (thanks, past life as a pediatric dentist). I came straight to Heinz from Pitt with the hope of honing a quantitative skillset to accompany my qualitative skills from undergrad and using these skills to promote racial equity and anti-racist local government policy. I've worked in Pittsburgh City Council (twice, two different offices), the Borough of Dormont, PA, and as a Mayoral Fellow in the City of Chicago. I'm currently a Heinz Policy Fellow at the National League of Cities' Race, Equity, And Leadership (REAL) initiative, and I plan to move back to Philadelphia and work in City government post-graduation.

# What I hope to learn

I believe that GIS/mapping is one of the most effective tools we, as public policy students and future policymakers, have to translate data and trends to stakeholders, decisionmakers, and the greater public. Health Care GIS, which I took last spring, was an extremely informative and useful course that adequately prepared me to conduct GIS analyses in a workplace setting (ArcMap is another story). However, like other Heinz skill-based courses, I left feeling that I had learned enough GIS to be *adequate* but not exceptional. Because I see myself as more of an intermediary between those who conduct data analysis and those who communicate it, for most other skills I've learned at Heinz (R, Python, Tableau, Access), this is fine. I want to graduate, though, as an "expert" in one skill. I think GIS/mapping is the most important critical for which I could take a deeper dive and attempt to get closer to "expert" status. I hope that Advanced GIS will allow me to sharpen the ArcGIS Pro skills I learned last year while, more imporantly, equipping me with an expanded mapping toolkit that I can use in a workplace (see: local government) that may not (probably does not) have the resources to buy ArcGIS Pro software. The first step toward racial equity is identifying racial inequities through data, and I can make a more substantial contribution to ensure racial equity and anti-racist local policy by visualizing and communicating these disparities through maps.

# Portfolio.

## Lab: Create a custom Google Maps style from an image

Final product: http://iansnyder5.github.io/isnyder-portfolio/google_map_style_philly.html

### Part I

For this lab, I wanted to color-coat Philadelphia in colors that showcase the city's pride. I originally thought to use a public image of the City of Philadelphia [flag](https://www.google.com/url?sa=i&url=https%3A%2F%2Fcommons.wikimedia.org%2Fwiki%2FFile%3AFlag_of_Philadelphia%2C_Pennsylvania.svg&psig=AOvVaw1G4uqklXZ5TZ5j3cxXksAC&ust=1584990411875000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCJCT58XjrugCFQAAAAAdAAAAABAD), but the color palette picked up on too many of the detail colors from the crest in the middle. Because I'm an avid Phillies fan, I then thought to use a public image of the basic Phillies [logo](https://www.google.com/url?sa=i&url=https%3A%2F%2Fen.wikipedia.org%2Fwiki%2FFile%3APhiladelphia_Phillies_Insignia.svg&psig=AOvVaw292-JEWARJusNaWBMZbpHF&ust=1584990497153000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCPC8p-7jrugCFQAAAAAdAAAAABAD), instead. However, the color scale centered on white, which I thought would not make for an interesting map base. My third attempt involved a public image of an [older Phillies logo](https://www.google.com/url?sa=i&url=https%3A%2F%2Fwww.flickr.com%2Fphotos%2Fmelling2293%2F6171367700&psig=AOvVaw292-JEWARJusNaWBMZbpHF&ust=1584990497153000&source=images&cd=vfe&ved=0CAIQjRxqFwoTCPC8p-7jrugCFQAAAAAdAAAAABAH), which used universally-beloved "throwback" colors. The white background of this image produced the same problem I had with the first Phillies logo. Thankfully, there was another public version of the image with a black background, which allowed me to center on "Cornflower Blue" and was my eventual inspiration for the color palette (below):

![PhilliesLogoandPalette](PhilliesGISLogoPalette.png)

Originally, I followed the methodology and sequencing of assigning colors from the palette verbatim from the example provided. This meant that, based on my color palette, I assigned the streets the "Light Steel Blue" color.

![PhillyMapTake1](PhillyMapTake1.png)

While this looked neat, the featured colors of the palette I selected are really the Cornflower Blue and "Brown," which is more commonly referred to as a "maroon." In the original version, only the names of parks featured the "Brown" color prominently. I made some tweaks to feature "Brown" as the street color so the map would highlight "Cornflower Blue" and "Brown" foremost.

![PhillyMapFinal](PhillyMapFinal.png)


### Part II

I've never created an API before, so Part II was daunting to me, at the start. The main issue I had, though, was that the . (period) that Google recommended for API restrictions before the web address was unnecessary. After troubleshooting and removing that, I found the process rather straightforward.

Continuing on the theme of Philly pride, I created 3 layers of "Philly Must-Haves" point features using Google MyMaps: "Wawa," "Cheesesteak," and "Soft Pretzel." Though all three groups are featured on the final lab (link above), they exported as a single entity in the KML file and all appear as white markers in the final map. To see the three layers individually through Google MyMaps, click [here](https://drive.google.com/open?id=1eu_47bS8iQjbzsqGd8PTZiv_Nio2Urca&usp=sharing).

_Takeaway: I didn't know *anything* we just did existed before this Lab, and I'm excited to have an easy-to-use skill to add to my toolbox after the first week!_
