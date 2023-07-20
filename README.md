# Pokemon Analysis


## Data Story To Be Told
Welcome to the captivating realm of Pokémon, where extraordinary creatures with boundless potential and unique attributes roam. Our journey intertwines the magic of storytelling with the power of data-driven insights as we embark on a thrilling analysis project. Let us transcend beyond mere numbers and charts to unravel the very essence of these mythical beings and the wondrous adventures they inspire.

Objectives:

* Explore the distribution of Pokemons across different types
* Uncover attributes of the best set of Pokemon collections
* Compare pairs of Pokemons in preparation for battle


## Thought Process

Throughout this project, our thought process was guided by an insatiable curiosity about the enchanting world of Pokémon and a passion for extracting valuable insights from data. As a team of dedicated Data Analysts, we approached this analysis with a sense of wonder, as if embarking on a grand adventure to uncover the secrets hidden within the vast expanse of the Pokémon universe.

To begin our exploration, the first page of our dashboard is dedicated to "Type Distribution." Here, we aimed to showcase the mesmerizing diversity of Pokémon types, delving into the prevalence of each type across the entire dataset. Through visually engaging charts and interactive graphs, we sought to illustrate how these mythical creatures are distributed among various types, from the fiery powers of Fire-types to the graceful swiftness of Flying-types. This section of the dashboard not only provides an overview of type distribution but also sparks curiosity about the unique attributes associated with each type.

For the second page, titled "Cluster," we delved into the world of Clustering analysis, using Python to unlock deeper patterns and groupings within the Pokémon dataset. By employing sophisticated clustering algorithms, we were able to reveal natural clusters of Pokémon based on similarities in attributes and characteristics. The visualizations on this page paint a vivid picture of how Pokémon naturally segregate into distinct groups, each with its own defining traits. This exploration not only enhances our understanding of Pokémon diversity but also serves as a foundation for selecting the most balanced and powerful teams in the quest for Pokémon mastery.

Moving on to the third page, aptly named "Collection," we sought to provide valuable insights to guide fellow Trainers in assembling the most formidable Pokémon collections. Here, we analyzed the attributes that contribute to a well-balanced and powerful team, investigating combinations of types, abilities, and stats that lead to exceptional battle prowess. With compelling visualizations and data-driven recommendations, this section empowers Trainers to build teams that stand ready to conquer any challenge in their path.

Finally, the fourth page of the dashboard, "Battle," takes us into the heart of epic Pokémon showdowns. In preparation for thrilling encounters, we meticulously compare pairs of Pokémon, examining their strengths, weaknesses, and battle performance. Armed with this in-depth analysis, Trainers can make strategic choices that can spell the difference between victory and defeat on the battlefield. Aspiring to be a formidable Pokémon Master is not just about raw power, but also about understanding the intricacies of matchups, and this page equips Trainers with the knowledge they need to triumph in the most intense battles.

In essence, our dashboard weaves together data and storytelling, celebrating the marvels of the Pokémon world while empowering Trainers with the tools they need to thrive. Through "Type Distribution," "Cluster," "Collection," and "Battle" pages, we aspire to share a rich tapestry of insights, driving the spirit of adventure and camaraderie that lies at the core of the Pokémon universe. As Trainers and data explorers, let us embark on this enthralling journey together, as we unravel the mysteries and embrace the enchantment of Pokémon!



## Algorithm and Library Used

* K-Means Clustering: A popular unsupervised learning algorithm from scikit-learn (Python) used to group similar Pokémon based on attributes, revealing natural clusters within the dataset.
Libraries:

* Microsoft Power BI: A powerful business intelligence tool for data visualization and analysis, used to create interactive dashboards and reports showcasing Pokémon insights.
* Microsoft PowerPoint: Presentation software used to craft engaging narratives and showcase project findings with visuals, complementing data analysis from Power BI.

### Python:

* scikit-learn (sklearn): Used for implementing the K-Means Clustering algorithm and other machine learning tasks.
* NumPy: Essential for scientific computing, providing support for multi-dimensional arrays and mathematical functions.
* Pandas: Crucial for data manipulation and analysis, offering DataFrames to organize and clean the dataset effectively.
* Regex (Regular Expressions): Powerful tool for pattern matching and text manipulation, used to extract specific information from the Pokémon dataset.





## Data Preprocessing

### Data Cleaning

* Dropped redundant index column
* Missing/Empty values in the "Type2" column replaced with "None"
* Repeating base names was removed

### Feature Engineering
* Added "Cluster" column for each Pokemon based on the K-Means Clustering Algorithm
* Added a new image URL gotten from pokemondb.net for better visuals
* Added a new column to recognize Pokemons with secondary type

## Insights

*  There are 1194 unique Pokemons and 18 different Pokemon types.
*  Water dominates the primary type while the least represented primary type is flying.
*  While flying is the least represented primary type, it is the most represented secondary type.
*  54.6% of the Pokemons have a secondary type while 45.4% have no secondary type.
*   While water dominates the count for Pokemons with a secondary type, it only has 46% of Pokemons with a secondary type. Dragon dominates the Pokemon with a secondary type (73.5%)
* Higher number of Pokemon are in cluster 2 while a lesser number is in cluster 5. However, cluster 2 is the least performing cluster based on the average of all metrics used.
* Cluster 3 is the overall best-performing cluster on average (best in Attack, Special Attack, and Speed while coming up as 1st runner-up for other battle metrics). Cluster 3 is dominated by Pokemons with primary type as Dragons and Psychic 
* Cluster 5 is best in defense but least in speed. This explains why Pokemons with primary type Steel and Rock dominate cluster 5.
* Cluster 1 is best in Hit-point while cluster 0 is best in special defense
*  Pokemons in cluster 3 have the highest percentage of Pokemon with a secondary type (78%) while Pokemons in cluster 2 have the most minor percentage (26.7%). This could mean that having a secondary type gives Pokemons more advantage against opponents.
*  Pokemons with Flying as the primary type are weak on Defense
*  While Psychic is among the top representatives in cluster 3. Psychics also have significant members in cluster 2.
*  The Mega Pokemon are stronger than their base forms.


## Screen Recording
[![here](https://img.youtube.com/vi/wD-X1t2tY_E/0.jpg)](https://www.youtube.com/watch?v=wD-X1t2tY_E)


## Team Eternamax

* Ogechukwu Sylvia Okwu
* Ernest Owojori

