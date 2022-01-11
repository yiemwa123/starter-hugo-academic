---
title: Map of Salaries of Fortune 1000 Tech Companies in the United States
summary: This class project done in collaboration with Chelsea Choi, Srishti Tyagi, and Alan Jiang. We created an interactive map visualization that displays information on average salaries in a particular state, the cost of living in that state, and companies’ salaries at their headquarter office.
tags:
- Code
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

# image:
#   caption: Photo by rawpixel on Unsplash
#   focal_point: Smart

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: "https://yiemwa123.github.io/project_2_3300/"
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
__Timeline__: Nov 2021 

__Tools__: HTML, CSS, d3.js

__Role__: Designer, Developer

__Other Info__: Class Project for Data-Driven Web Applications

### Objectives of this assignment
* Create an interactive data visualization
* Make use of dynamic elements
* Integrate multiple data sources

The inspiration for this data visualization came from the idea that people may need to relocate for tech industry careers. When job seekers consider a position, they must think about cost of living and salary. The goal of the visualization is to give our audience an idea of the pros and cons of moving to a different city for a particular job.

### Functionality
* Zoom and pan of the map
_The user can zoom in an out of the map by scrolling and clicking on a state. To zoom out, the user can scroll or click the zoom out button which takes them back to the original view of the map. The user can pan the map by clicking and dragging._
* Tooltip (clicking) that displays companies, average salaries, and city
_When the user clicks on a city, it will display the companies with headquarters at that location, average salary at that location, and cost of living in that state._

### Reflection
Some potential improvements to this visualization are:

* __More data/better data cleaning__. The data provided by the map is rather limiting since it only displays companies with headquarters in those areas even though Fortune 1000 companies have offices in many other cities. The drawback of adding more cities would be that the map gets crowded, making it hard to extract information. It also would have been nice to have the cost of living of the city rather than just the state since cities within the same state can have vastly different costs of living. Some of our data can be cleaned better/researched better. For instance, our map displays Red Hat and IBM separately even though the parent company of Red Hat is IBM

* __Tooltip position__. The position of the tooltip can be a bit awkward at times and it sometimes covers up the other cities. However, as we were coding it, we found it difficult to adjust the position of the tooltip dynamically as the user is interacting with the map. If we had more time, we should certainly figure out a way to position the tooltip better.

* __Filtering cities based on salary and cost of living__. As mentioned before, overcrowding could be an issue if we decided to add more cities. One way we could combat this is if we allowed users to filter cities based on what salaries were being offered and cost of living.
