---
title: "More Precise Regression Test Selection via Reasoning about Semantics-Modifying Changes"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Jiyang Zhang
- Pengyu Nie
- Milos Gligoric
- Owolabi Legunsen

## Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-01-24T00:00:00Z"
doi: ""

## Schedule page publish date (NOT publication's date).
# publishDate: "2022-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name. 
publication: In *32th ACM SIGSOFT International Symposium on Software Testing and Analysis*
publication_short: In *ISSTA 2023*. This paper won an *ACM SIGSOFT Distinguished Paper Award*

abstract: "Regression test selection (RTS) speeds up regression testing by onlyre-running tests that might be affected by code changes. Ideal RTSsafelyselects all affected tests andpreciselyselects only affectedtests. But, aiming for this ideal is often slower than re-runningall tests. So, recent RTS techniques use program analysis to tradeprecision for speed, i.e., lower regression testing time, or even usemachine learning to trade safety for speed. We seek to make recentanalysis-based RTS techniques more precise, to further speed up re-gression testing. Independent studies suggest that these techniquesreached a “performance wall” in the speed-ups that they provide.We manually inspect code changes to discover those that do notrequire re-running tests that are only affected by such changes.We categorize 29 kinds of changes that we find from five projectsinto 13 findings, 11 of which are semantics-modifying. We enhancetwo RTS techniques—EkstaziandSTARTS—to reason about our findings. Using 1,150 versions of 23 projects, we evaluate the impacton safety and precision of leveraging such changes. We also evaluateif our findings from a few projects can speed up regression testing inother projects. The results show that our enhancements are effectiveand they can generalize. On average, they result in selecting 41.7%and 31.8% fewer tests, and take 33.7% and 28.7% less time thanEkstaziandSTARTS, respectively, with no loss in safety." 

# Summary. An optional shortened abstract.
summary: "Improving the performance of RTS with code semantics"

tags: ["regression test selection"]

# Display this page in the Featured widget? 
featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'ctaxonomy-slides.pdf'
url_source: ''
url_video: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- RTS

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
