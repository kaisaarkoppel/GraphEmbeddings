# GraphEmbeddings
Graph embedding plots by attributes of master's project "Understanding Segregation in the Baltic States Based on Person-to-Person Financial Transactions".

Main folders representing three countries of Baltic States:
 * **EE** - Estonia 
 * **LV** - Latvia
 * **LT** - Lithuania.

Each of the main folder has folders for each of its county/region. The .png files are graph embedding results of 2017 and 2021 on one of the four attributes:
* gender,
* language,
* income group,
* age group.

Files for gender, language and age group are mainly in four versions:
* version1: _[year]\_emb\_[attribute].png_ is the smallest
* version2: _[year]\_emb\_[attribute]\_**square**.png_ is the square size of the smallest
* version3: _[year]\_emb\_[attribute]**2**.png_ is the largest
* version4: _[year]\_emb\_[attribute]**2\_square**.png_ is the square size of the largest

Language is mainly in 3x4 versions:
* first group with four aforementioned versions, _[year]\_emb\_**lang**\*.png_, is of results, where the order of nodes added into graph is random
* second group with four aforementioned versions, , _[year]\_emb\_**lange**\*.png_, is of results, where the nodes representing the native language are added into graph lastly (so they are on the top of the other nodes)
* third group with four aforementioned versions, , _[year]\_emb\_**langr**\*.png_, is of results, where the nodes representing Russian language are added into graph lastly (so they are on the top of the other nodes).
