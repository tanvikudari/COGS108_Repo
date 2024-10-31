# **COGS 108 \- Project Proposal**

# **Names**

* Hailey Ye  
* Kalista Cancel  
* Christian Virata  
* Jacob Thongvanh  
* Tanvi Kudari

# **Research Question**

RESEARCH QUESTION: What is your research question? Include the specific question you're setting out to answer. This question should be specific, answerable with data, and clear. A general question with specific subquestions is permitted. (1-2 sentences)

* *How do weather conditions affect/influence demands for electric bicycle and scooter rentals in urban areas ?*  
  *   
* *Possible Data: Rental logs, weather data (temperature, precipitation, wind), time of day/week, major events*

## **Background and Prior Work**

 *Micro-mobility solutions, including electric scooters and bicycles, are increasingly seen as significant components of urban transportation. These solutions offer a flexible and environmentally friendly alternative to traditional motorized vehicles, especially valuable in congested urban areas. By providing on-demand mobility for short distances, micro-mobility can enhance urban accessibility and reduce the dependence on vehicles, thus contributing to a reduction in urban traffic congestion and pollution\<sup\>\<a href="\#ref1"\>1\</a\>\</sup\>. Weather conditions significantly impact the utilization of micromobility platforms. Studies have consistently shown that elements such as rain, temperature, and wind can affect the frequency and duration of trips made using shared e-scooters and e-bikes\<sup\>\<a href="\#ref2"\>2\</a\>\</sup\>. For example, poorer weather conditions, particularly in cold, rainy, and windy scenarios, are known to decrease the demand for these modes of transportation, as they expose riders to discomfort and potential safety risks\<sup\>\<a href="\#ref1"\>1\</a\>\</sup\>.*

*In Robert B. Nolan’s article, he explored the specific impacts weather on these modes of transportation in Austin, Texas, utilizing a comprehensive dataset corresponding to trip data with various weather conditions. Within his study, it was found that all micro-mobility devices saw decreased usage of cold, rainy, and extremely hot conditions, but e-scooters were slightly less sensitive to adverse weather in comparison to bicycles, which could correlate to the lower physical effort required and shorter trips durations typical of scooter usage\<sup\>\<a href="\#ref2"\>2\</a\>\</sup\>.*

*In Lars Böcker’s article, we were able to see insights into how bike-sharing systems could serve as a complement to public transportation, especially in facilitating the first and last mile of commuter journeys. Their study in Oslo showed the potential of integrating bike-sharing with public transportation to enhance the overall efficiency and appeal of the urban transport systems. However, they also identified significant demographic differences in bike-sharing usage, with lower participation rates among women and older adults, suggesting a need for targeted strategies to increase the inclusiveness of these services\<sup\>\<a href="\#ref1"\>1\</a\>\</sup\>.*

*With these studies in mind, we believe that they both illustrate the potential and the limitations of micro-mobility as a component of urban transportation strategies. While offering benefits, the sensitivity of these systems to environmental factors and demographic disparities must be addressed to maximize their effectiveness and reach. By analyzing data from multiple service providers and comparing urban contexts, this project aims to contribute insights to the ongoing discussions about the role of micromobility in sustainable urban transportation.*

### ***References***

*\<a name="ref1"\>1\</a\> Böcker, L., et al. (2020). Bike sharing use in conjunction with public transport: Exploring spatiotemporal, age and gender dimensions in Oslo, Norway. Transportation Research Part A, 138, 389–401.*

*\<a name="ref2"\>2\</a\> Noland, R.B. (2021). Scootin’ in the rain: Does weather affect micromobility? Transportation Research Part A, 149, 114–123.*

**Links to previous work:**

* [Lars Böcker: Bike sharing use in conjunction to public transport: Exploring spatiotemporal, age and gender dimensions in Oslo, Norway](https://www.sciencedirect.com/science/article/abs/pii/S0965856420306285?via%3Dihub)  
* [Robert B. Noland: Scootin’ in the rain: Does weather affect micromobility?](https://www.sciencedirect.com/science/article/abs/pii/S0965856421001294?via%3Dihub)

* Include a general introduction to your topic  
* Include an explanation of what work has been done previously  
* Include citations or links to previous work

This section will present the background and context of your topic and question in a few paragraphs. Include a general introduction to your topic and then describe what information you currently know about the topic after doing your initial research. Include references to other projects that have asked questions or approached similar problems. Explain what others have learned in their projects.

Find some relevant prior work, and reference those sources, summarizing what each did and what they learned. Even if you think you have a totally novel question, find the most similar prior work that you can and discuss how it relates to your project.

References can be research publications, but they need not be. Blogs, GitHub repositories, company websites, etc., are all viable references if they are relevant to your project. It must be clear which information comes from which references. (2-3 paragraphs, including at least 2 references)

**Use inline citation through HTML footnotes to specify which references support which statements**

For example: After government genocide in the 20th century, real birds were replaced with surveillance drones designed to look just like birds.[1](https://github.com/COGS108/Group007-FA24/blob/89bdf310c94f98619e48432d14737d6a9ac9f2b2//#cite_note-1) Use a minimum of 2 or 3 citations, but we prefer more.[2](https://github.com/COGS108/Group007-FA24/blob/89bdf310c94f98619e48432d14737d6a9ac9f2b2//#cite_note-2) You need enough to fully explain and back up important facts.

Note that if you click a footnote number in the paragraph above it will transport you to the proper entry in the footnotes list below. And if you click the ^ in the footnote entry, it will return you to the place in the main text where the footnote is made.

To understand the HTML here, `<a name="#..."> </a>` is a tag that allows you produce a named reference for a given location. Markdown has the construciton `[text with hyperlink](#named reference)` that will produce a clickable link that transports you the named reference.

1. [^](https://github.com/COGS108/Group007-FA24/blob/89bdf310c94f98619e48432d14737d6a9ac9f2b2//#cite_ref-1) Lorenz, T. (9 Dec 2021\) Birds Aren’t Real, or Are They? Inside a Gen Z Conspiracy Theory. *The New York Times*. [https://www.nytimes.com/2021/12/09/technology/birds-are-real-gen-z-misinformation.html](https://www.nytimes.com/2021/12/09/technology/birds-arent-real-gen-z-misinformation.html)  
2. [^](https://github.com/COGS108/Group007-FA24/blob/89bdf310c94f98619e48432d14737d6a9ac9f2b2//#cite_ref-2) Also refs should be important to the background, not some randomly chosen vaguely related stuff. Include a web link if possible in refs as above.

# **Hypothesis**

*We predict that the demand for electric bicycle and scooter rentals will significantly decrease/lower due to weather factors such as high precipitation, low temperature, low visibility, and strong winds. Conversely, moderate weather such as mild temperatures, low precipitation, and light winds with high visibility will increase demand as it creates optimal conditions for outdoor travel activities. These predictions are hypothesized based on consumer’s and people's decisions about outdoor activities and its usual influence by weather.*

# **Data**

1. Explain what the **ideal** dataset you would want to answer this question. (This should include: What variables? How many observations? Who/what/how would these data be collected? How would these data be stored/organized?)

	**A first deal set would be the full systemic data from major micro mobility service providers (Lime, Spin, Bird, Lyft, Jump, etc.). Ideally, these datasets would provide us with excessive data that we would manipulate/ remove to focus on the variables that relate to our area of interest and proposed location. Variables such as the *vehicle type (bike or scooter), trip duration, time/ date of rental, start location of the trip (latitude and longitude), and end location of the trip (latitude and longitude) would help us identify changes in demand within urban spaces. Since many of these rental companies already store and collect this data, we would utilize their existing datasets.  In terms of the weather aspect of our research question, an ideal dataset would cover overlapping dates to the rental dates of the other dataset for us to properly evaluate their interactions. Some ideal variables in this dataset would include the average daily temperature, rain levels, average rain speed, and humidity. We would store the data in a relational database. Our information regarding the vehicle type, weather, trip duration, and days vehicles are rented will be neatly stored there.***

2. Search for potential **real** datasets that could provide you with something useful for this project. You do not have to find every piece of data you will use, but you do need to have demonstrated some idea that (a) this data is gettable and (b) that this data may be different from what your ideal is.

Potential datasets: 

[https://data.austintexas.gov/Transportation-and-Mobility/Shared-Micromobility-Vehicle-Trips-2018-2022-/7d8e-dm7r/about\_data](https://data.austintexas.gov/Transportation-and-Mobility/Shared-Micromobility-Vehicle-Trips-2018-2022-/7d8e-dm7r/about_data) 

[https://www.kaggle.com/datasets/razamh/escooters-trips](https://www.kaggle.com/datasets/razamh/escooters-trips) 

[https://www.lyft.com/bikes/bay-wheels/system-data](https://www.lyft.com/bikes/bay-wheels/system-data) 

[https://www.climate.gov/maps-data/dataset/daily-temperature-and-precipitation-reports-data-tables](https://www.climate.gov/maps-data/dataset/daily-temperature-and-precipitation-reports-data-tables) 

# **Ethics & Privacy**

* Thoughtful discussion of ethical concerns included  
* Ethical concerns consider the whole data science process (question asked, data collected, data being used, the bias in data, analysis, post-analysis, etc.)  
* How your group handled bias/ethical concerns clearly described

Acknowledge and address any ethics & privacy related issues of your question(s), proposed dataset(s), and/or analyses. Use the information provided in lecture to guide your group discussion and thinking. If you need further guidance, check out [Deon's EDeonthics Checklist](http://deon.drivendata.org/#data-science-ethics-checklist). In particular:

* Are there any biases/privacy/terms of use issues with the data you proposed?  
  ***There could be sampling bias regarding locations where certain areas have higher user demand. This can lead to underrepresentation of groups in lower income areas. A privacy issue could be that trips record precise location information of the users start and end locations. This could reveal information about where the user works and where they live.***  
* Are there potential biases in your dataset(s), in terms of who it composes, and how it was collected, that may be problematic in terms of it allowing for equitable analysis? (For example, does your data exclude particular populations, or is it likely to reflect particular human biases in a way that could be a problem?)  
  * **Potential biases or issues with our datasets stem mainly from our micro mobility informational datasets. This is because most of these companies withhold their systemic data from the public and our desired variables aren’t easily accessible. However, we did find a couple sufficient datasets. The potential bias or issue with them however is that it wouldn’t be a fully represented sample. The datasets we found cover Chicago, Austin, and San Francisco and thus wouldn’t be the best representative sample for any generalized findings, unless we consider narrowing the scope of our research.**


* How will you set out to detect these specific biases before, during, and after/when communicating your analysis?  
  * Looking into the samples of our datasets will help us detect biases before our analysis. If there appears to be collection bias in the design of the data collection this should be evaluated before we start analyzing.*During analysis we can analyze how weather affects certain groups and see which groups if affects the most regarding electric scooter/bike usage. After analysis we will be able to clearly report our findings of the biases.*

* Are there any other issues related to your topic area, data, and/or analyses that are potentially problematic in terms of data privacy and equitable impact?  
  *A problematic issue that is related to our topic area could be that companies know when and where you are while using their vehicle, so companies would need to ensure strict data privacy. This concern is pretty protected by most companies making our dataset collection a little more difficult, but for available data we found, users may be sensitive to the sharing of this information.*  
* How will you handle issues you identified?  
  *To handle these issues data will be grouped and anonymized. We will also try to group trip details by location to make it more organized, while also ensuring the privacy of the users data that is being collected.* 

# 

# 

# 

# **Team Expectations**

Read over the [COGS108 Team Policies](https://github.com/COGS108/Projects/blob/master/COGS108_TeamPolicies.md) individually. Then, include your group’s expectations of one another for successful completion of your COGS108 project below. Discuss and agree on what all of your expectations are. Discuss how your team will communicate throughout the quarter and consider how you will communicate respectfully should conflicts arise. By including each member’s name above and by adding their name to the submission, you are indicating that you have read the COGS108 Team Policies, accept your team’s expectations below, and have every intention to fulfill them. These expectations are for your team’s use and benefit — they won’t be graded for their details.

### ***Communication***

* *We will use iMessages for quick, informal updates and questions, and  for detailed discussions or sharing files. For complex discussions or brainstorming, Zoom meetings will be preferred. iMessages should be responded to within 12 hours if possible.*   
* *We will meet at least twice via Zoom or in person, for overall task planning and progress updates.*   
* *We aim for a "blunt but polite" tone. Clear, direct feedback is encouraged, but should remain respectful and polite*  
  * *"I think X is a problem because of Y. Does everyone else see it that way too or am I missing something?"*

### ***Decision-Making***

* *Decisions will be made by majority vote, in the case where someone is unavailable, decisions may be made by the majority of those present.*  
* *In terms of delegation, routine decisions may be delegated to the person responsible for that specific area.*

### ***Task Assignments***

* *In this case, each person will have a specialized and primary focus of the project such as research, data, analysis, and coding but will also support other roles when needed.*  
* *We will follow our project timeline for managing task lists and tracking progress*  
* *In our weekly, we will update deadlines or reassess responsibilities when needed*

### ***Struggles to Meet Deadlines***

* *When a team member finds themselves struggling to meet deadlines, they should notify the group ahead of time in iMessage as soon as possible.*   
* *The group will then discuss the reallocation of timeline and task to keep the project on track.*

# 

# **Project Timeline Proposal**

Specify your team's specific project timeline. An example timeline has been provided. Changes the dates, times, names, and details to fit your group's plan.

If you think you will need any special resources or training outside what we have covered in COGS 108 to solve your problem, then your proposal should state these clearly. For example, if you have selected a problem that involves implementing multiple neural networks, please state this so we can make sure you know what you’re doing and so we can point you to resources you will need to implement your project. Note that you are not required to use outside methods.

### Project Timeline Proposal
| Meeting Date | Meeting Time      | Completed Before Meeting                                          | Discuss at Meeting                                                   |
|--------------|-------------------|-------------------------------------------------------------------|-----------------------------------------------------------------------|
| 10/22        | 1 PM              | Read & think about COGS 108 expectations; brainstorm topics/questions | Determine best form of communication; finalize project topic; discuss hypothesis; begin background research |
| 10/26        | 11 AM             | Do background research on micro-mobility and weather impacts      | Discuss ideal dataset(s) and ethics; draft project proposal          |
| 11/04        | 12 PM             | Edit, finalize, and submit proposal; search for potential weather and micro-mobility datasets | Discuss wrangling and potential analytical approaches; assign group roles and set mini checkpoint dates |
| 11/08        | 11 AM             | Import & wrangle data (e.g., Lime, Spin, Bird rental data); explore weather dataset | Review/edit wrangling/EDA process; refine analytical approach based on initial data exploration |
| 11/15        | 12 PM             | Complete data wrangling and initial EDA; begin formal analysis (e.g., correlation with weather factors) | Review analysis progress; identify gaps in data/methods; adjust roles as needed |
| 11/29        | 12 PM             | Complete core analysis; draft results, conclusions, and discussion sections | Review/edit full project; discuss potential biases; prepare for final edits |
| 12/15        | Before 11:59 PM   | NA                                                                | Submit the final project and complete group project surveys           |


