---
title: "Comparing and Combining Analysis-Based and Learning-Based Regression Test Selection"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- Jiyang Zhang
- admin
- Milos Gligoric
- Owolabi Legunsen
- August Shi

## Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-02-25T00:00:00Z"
doi: ""

## Schedule page publish date (NOT publication's date).
# publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name. 
publication: In *3rd ACM/IEEE International Conference on Automation of Software Test*
publication_short: In *AST 2022* 

abstract: Regression testing—rerunning tests on each code version to detect newly-broken functionality—is important and widely practiced. But, regression testing is costly due to the large number of tests and the high frequency of code changes. Regression test selection (RTS) opti- mizes regression testing by only rerunning a subset of tests that can be affected by changes. Researchers showed that RTS based on pro- gram analysis can save substantial testing time for (medium-sized) open-source projects. Practitioners also showed that RTS based on machine learning (ML) works well on very large code repositories, e.g., in Facebook’s monorepository. We combine analysis-based RTS and ML-based RTS by using the latter to choose a subset of tests selected by the former. We first train several novel ML models to learn the impact of code changes on test outcomes using a train- ing dataset that we obtain via mutation analysis. Then, we evaluate the benefits of combining ML models with analysis-based RTS on 10 projects, compared with using each technique alone. Combining ML-based RTS with two analysis-based RTS techniques–Ekstazi and STARTS–selects 25.34% and 21.44% fewer tests, respectively.

# Summary. An optional shortened abstract.
summary: "We combine analysis-based RTS and ML-based RTS by using the latter to choose a subset of tests selected by the former."

tags: ["regression test selection"]

# Display this page in the Featured widget? 
featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Overflow of techniques'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- predictiverts

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


