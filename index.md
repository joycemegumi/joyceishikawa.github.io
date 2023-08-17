---
layout: default
video_urls:
  - url: https://youtu.be/qe13jgi8Dv4
    title: Generating New Video
  - url: https://youtu.be/1GhVirfRe0Q
    title: Generate an Existing Video
---

## Portfolio of Projects
---

### Designing an Experimental Study on Customer Engagement on Instagram Shop
![R Badge](https://img.shields.io/badge/-R-276DC3?logo=r&logoColor=white) ![pwr Badge](https://img.shields.io/badge/-pwr-276DC3?logo=r&logoColor=white) ![dplyr Badge](https://img.shields.io/badge/-dplyr-276DC3?logo=r&logoColor=white) ![agricolae Badge](https://img.shields.io/badge/-agricolae-276DC3?logo=r&logoColor=white) ![data.table Badge](https://img.shields.io/badge/-data.table-276DC3?logo=r&logoColor=white) 

Instagram has helped businesses and entrepreneurs build their digital storefronts through its shopping feature and has allowed users to shop easily. In this project, my team sought to learn what type of features increase users' average daily session time on Instagram’s shop feed by designing a hypotehtical experiment and conducting simulated studies. The attributes studied were exposure to product categorization, creator product curation, and price and description in the feed. 
<img src="images/treatments.jpeg"/>

A one-way analysis of variance test with the Tukey’s Honest Significant Difference (HSD) correction was conducted to evaluate the effect of each treatment group in comparison to the control group to review if a significant effect size was present.

<img src="images/simulations results.png"/>

[View Project](https://joycemegumi.github.io/research-design-project)

---
### Optimizing NYPD Resource Allocation
#### Unveiling Insights Through an ETL Pipeline with NYC Open Data API, PostgreSQL, Apache Spark, and Flask
![Python Badge](https://img.shields.io/badge/-Python-3776AB?logo=python&logoColor=white) ![Docker Badge](https://img.shields.io/badge/-Docker-2496ED?logo=docker&logoColor=white) ![Apache Spark Badge](https://img.shields.io/badge/-Apache%20Spark-E25A1C?logo=apache-spark&logoColor=white) ![PostgreSQL Badge](https://img.shields.io/badge/-PostgreSQL-336791?logo=postgresql&logoColor=white) ![Flask Badge](https://img.shields.io/badge/-Flask-000000?logo=flask&logoColor=white)

In response to the surge in major crime rates in NYC, our team developed a web application tool aimed at mitigating this issue. We designed and implemented a robust ETL pipeline to curate essential data, which served as the foundation for developing a web application tailored for NYPD officials. This dynamic tool not only identifies precincts with elevated crime rates, but also highlights those with a disproportionate incidence of major crimes. 

By utilizing the NYC Open Data API, PostgreSQL, Apache Spark, and Flask, we've created a powerful solution empowering officials to strategically allocate NYPD resources, ultimately fostering informed decision-making for safer communities.

![NY Crime Flask App](images/ny-crime-demo.gif)
[View the Code on GitHub](https://github.com/joycemegumi/Managing-Data-Project)

### Automating Content Creation with a Serverless Architecture
#### Transforming a 2 Million+ Companies Dataset into Dynamic Video Presentations
![AWS VPC Badge](https://img.shields.io/badge/-VPC-232F3E?logo=amazon-aws&logoColor=white) ![Lambda Badge](https://img.shields.io/badge/-Lambda-FF9900?logo=amazon-aws&logoColor=white) ![S3 Badge](https://img.shields.io/badge/-S3-569A31?logo=amazon-aws&logoColor=white) ![RDS Badge](https://img.shields.io/badge/-RDS-FF7F50?logo=amazon-aws&logoColor=white) ![API Gateway Badge](https://img.shields.io/badge/-API%20Gateway-FF9900?logo=amazon-aws&logoColor=white) ![CloudFront Badge](https://img.shields.io/badge/-CloudFront-232F3E?logo=amazon-aws&logoColor=white)

Manual content creation involves extensive time and effort by video editors that need to search for video assets, apply copy, styling etc. This process can be time-consuming and may lead to delays in delivering timely content to customers, potentially missing valuable opportunities.

In this project my team built a company video generator web application based on companies datasets from Kaggle. This cutting-edge platform will allow users to effortlessly generate videos by simply selecting their company name and desired theme by leveraging the integration of the [JSON2Video API](https://json2video.com/) and [Pexel API](https://www.pexels.com/api/).

<img src="images/comapny-video-generator-architecture.jpeg"/>


Benefits :
* Cost and time efficiency in content creation.
* Enabling non-technical users to create videos.

{% for video in page.video_urls %}
#### {{ video.title }}

<iframe width="560" height="315" src="{{ video.url }}" frameborder="0" allowfullscreen></iframe>
{% endfor %}

[View the Web Application](https://frontendcodegroup2.s3.amazonaws.com/videogenerator.html)

[View the presentation on Canva](https://www.canva.com/design/DAFr0hoDX14/3IRODlYJekxRvXHBT6kVJA/view?utm_content=DAFr0hoDX14&utm_campaign=designshare&utm_medium=link&utm_source=publishsharelink)

[View the project on GitHub](https://github.com/joycemegumi/Comapny-Video-Generator)