---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Same Data, Conflicting Insights?"
summary: " Visualizations "
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
Climate change and global warming are controversial topics, with debates centering around the extent of human influence, the urgency of action, and the potential consequences. Proponents of immediate action argue that human activities are driving climate change with severe consequences, while skeptics may question the extent of human impact or the reliability of climate models.

![screen reader text](trends.png "")

### Left Chart
It visualizes rising global temperatures over time, emphasizing the correlation with human activities. It argues that humans have made significant damaging contributions to climate change and temperatures are in fact rising sharply, implying the urgency of the matter and immediate call-to-action.

Some notable events that indicate strong human contribution are:
1.  The non-decreasing graph post World War II in 1939-1945, likely due to substantial increase in urbanization, modernization and industrialization.
2. We also see a high spike in the temperatures in 2011, that is when the Fukushima disaster occurred - yet another human-induced tragedy.

### Right Chart
Contrastingly, the right chart takes a broader perspective and showcases a relatively stable graph, indicating that it's not a real threat. It tends to speak for the natural ebb and flow of climate conditions, suggesting that current warming trends may be part of a larger natural cycle rather than solely due to human influence.

### Rhetoric/Framing Techniques used:
#### Y-Axis Scale Range: 
The scale for the y-axis for both the charts is different. The scale for the chart on the left is fitted precisely to the minimum and maximum values in the dataset thus offering a detailed, microscopic view of the plot. On the contrary, the scale for the right chart extends far beyond the dataset's extreme values. This creates the illusion of minimal variation in the graph, suggesting a relatively stable trend.
#### Color Scheme: 
The color palette for both charts is thoughtfully selected, intentionally creating a subconscious mental bias. The left chart is drawn with a vibrant, warm red color, instilling a sense of urgency and suggesting potential negative impacts. Conversely, the right chart is presented in a natural, earthy, and tranquil blue tone, encouraging a more relaxed interpretation.


### Dataset Source 
[NASA's Climate Change Data](https://data.giss.nasa.gov/gistemp/)
CSV file Under the "Tables of Global and Hemispheric Monthly Means and Zonal Annual Means" section titled **"Global-mean monthly, seasonal, and annual means, 1880-present, updated through most recent month"**.

### Data pre-processing 
Both the charts use the same data. However, I have made a few simple modifications to the dataset -
- Filtered the data to only contain the values starting from the Year 1980.
- Aggregated the values of the 12 months of the year (Jan-Dec) each given in the dataset to get a "mean" for each year. This "mean" of each year is represented in the line charts.