# Fintech-Webcrawler
A webcrawler that tracks fintech entities and extract their most important information

## Idea

The idea is to develop a tool that reduces the data collection stage in the data science lifecycle.

Given that data collection is one of the most time consuming activities it would be desirable to build a tool that reduces the time spend in doing this task. Note that data collection efficency is a case by case study due to the different sources of data that could range from physical data collection to computer based, in this is case the data collection is from websites and dues it can be further automated in such a way that the data collectors and reviewers doesn't waste time opening new links and searching for keywords although they will still review the data to make sure it is of good quality.

The data collection when reviewing fintech entities is the following:
1. Gather information from blogs, lists and news about fintech where the entities are identified.
2. The entities are listed in a table.
3. For each entity some features are extracted as: webpage, incorporation date, operation headquarters, etcetera.
4. Some features are extracted from third party public databases
5. Each entity is classified given some methodology
6. The structured data is saved into the database

Once the data collection is done, data analysis can be performed.

## Requirements
1. The app should reduce the time spent in data collection for an entity in 30%
2. The app should show information of interest that could be used by the user to make further research.
