---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Bechdel Test: Female Representation in Movies"
summary: " Analyzing the imbalance of gender potrayal in films - and the surprising number of movies that do not make the cut! "
authors: []
tags: 
  - Projects
categories: []
date:

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
#   placement: 3
  focal_point: "Smart"
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
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


### Introduction
Before we begin, since we're talking about movies, imagine the following scene -

Two women discussing movies; one remarks that she will only see a film if it meets a certain set of requirements involving female characters and their depiction.

This exact dialog that started as a joke in one of Alison Bechdel's comic strip - “Dykes to Watch Out For”, sparked a critical conversation and often comes up when thinking about female representation in media.

**What exactly is the Bechdel Test?**

It is a 3-question litmus test to gauge gender bias in movies. These are fairly basic questions -

1. The movie must feature at least two women in it.  
2. The women must talk to each other.  
3. Their discussion must be about something other than a man.  

Simple, right?

Well, a surprising number of movies do not pass this simple test!

To name a few -
- Bullet Train
- Dead Poet's Society
- Slumdog Millionaire
- The Lord of the Rings trilogy
- The Prestige
- The Shawshank Redemption

As aggravating it is, I found the concept incredibly fascinating and decided to tinker with the data myself and see how it turns out!

### Insights

**1. Distribution of total movies release each year and the movies that pass the first rule of the Bechdel Test**
![screen reader text](movie_release_years.png "")

**2. Movies featuring atleast Two Female actors**
![screen reader text](bechdel_total.png "")

**3. Percentage of movies that pass the first rule of the test directed by each gender**
![screen reader text](directors_gender_percentage_passed.png "")


### Thoughts
The Bechdel Test first appeared in the comic in 1985. Almost 40 years on, we're not exactly doing very well addressing the core gender inequalities.

### Data

**Dataset Sources:**
- [Top 10,000 IMDb Movies (1915 - 2023)](https://www.kaggle.com/datasets/willianoliveiragibin/10000-data-about-movies-1915-2023/data)

- [Actors' Gender](https://github.com/taubergm/HollywoodGenderData/blob/master/all_actors_movies_gender_gold.csv)

- [Directors' Gender](https://github.com/taubergm/HollywoodGenderData/blob/master/all_directors_gender.csv)

