---
title: 1st USS - GlobPOP
# date: "2023-12-15"
# event: Wowchemy Conference
# event_url: https://example.org
profile: true

event: 1st Urban Science and Sustainability (USS) Conference
event_url: https://www.ussconference.net/ussc/en

location: The Institute of Urban Environment, Chinese Academy of Sciences (CAS)

summary: Welcome to view the GlobPOP. You can view and download the dataset, reproducible code, temporal validation results and PowerPoint further.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
# date: '2030-06-01T13:00:00Z'
# date_end: '2030-06-01T15:00:00Z'
# all_day: false

# Schedule page publish date (NOT talk date).
# publishDate: '2023-12-15T00:00:00Z'

authors:
- "Luling Liu"
- "Xin Cao"
- "Shijie Li"
- "Na Jie"

author_notes:
- "Beijing Normal University"
- "Beijing Normal University"
- "Beijing Normal University"
- "Beijing Normal University"


tags: ["event"]

# Is this a featured talk? (true/false)
featured: true

# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
#   focal_point: Right

# links:
#   - icon: twitter
#     icon_pack: fab
#     name: Follow
#     url: https://twitter.com/georgecushen
# url_code: ''
# url_pdf: ''
url_slides: uploads/USS_2023_GlobPOP_Luling Liu.pdf
url_code: 'https://github.com/lulingliu/GlobPOP'
url_dataset: 'https://zenodo.org/doi/10.5281/zenodo.7813301'

# Markdown Slides (optional).
#   Associate this talk with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
# slides: 'example'
slides: ''

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
# projects:
#   - example
# projects : []


---

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vQ08Ir0GjHEn7OcKS7dFxLOWexDBVez4At_Qg0UM1XZr3KpHkUct1xi3L0rBP9JM1VYfzqjPXxqyVnB/embed?start=false&loop=false&delayms=3000" frameborder="0" width="1280" height="749" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>  


{{% callout note %}}
Click on the **Slides** button above to download the slides.
{{% /callout %}}


<!-- Slides can be added in a few ways:

- **Create** slides using Wowchemy's [_Slides_](https://wowchemy.com/docs/managing-content/#create-slides) feature and link using `slides` parameter in the front matter of the talk file
- **Upload** an existing slide deck to `static/` and link using `url_slides` parameter in the front matter of the talk file
- **Embed** your slides (e.g. Google Slides) or presentation video on this page using [shortcodes](https://wowchemy.com/docs/writing-markdown-latex/).

Further event details, including [page elements](https://wowchemy.com/docs/writing-markdown-latex/) such as image galleries, can be added to the body of this page. -->

<!-- <iframe src="https://onedrive.live.com/embed?resid=D14E0CC306E1B8F1%213105&authkey=!AEIMMklQRUTiZjU&em=2" width="100%" height="100%"  frameborder="0" scrolling="yes"></iframe> -->







**Abstract**

Continuously monitoring global population spatial dynamics is crucial for implementing effective policies related to sustainable development, including epidemiology, urban planning, and global inequality. However, existing global gridded population products lack consistent population estimates, making them unsuitable for time-series analysis. To address this issue, this study designed a data fusion framework based on cluster analysis and statistical learning approaches, which led to the generation of a continuous global gridded population dataset (GlobPOP). 


The GlobPOP dataset was evaluated through two-tier spatial and temporal validation to demonstrate its accuracy and applicability. The spatial validation results show that the GlobPOP dataset is highly accurate. The temporal validation results also reveal that the GlobPOP dataset performs consistently well across eight representative countries and cities despite their unique population dynamics. With the availability of GlobPOP datasets in both population count and population density formats, researchers and policymakers can leverage the new dataset to conduct time-series analysis of the population and explore the spatial patterns of population development at global, national, and city levels. 


To validate the temporal accuracy of GlobPOP at the country level, we have developed an interactive web application, accessible at https://globpop.shinyapps.io/GlobPOP/, where data users can explore the country level population time-series curves of interest and compare them with census data.



<iframe src="https://globpop.shinyapps.io/GlobPOP/" width="100%" height="100%" scrolling="yes" ></iframe>
