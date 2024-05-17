---
title: "Inline tests"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Pengyu Nie
- Owolabi Legunsen
- Milos Gligoric

## Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2022-09-01T00:00:00Z"
doi: ""

## Schedule page publish date (NOT publication's date).
# publishDate: "2022-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name. 
publication: In *37th IEEE/ACM International Conference on Automated Software Engineering*
publication_short: In *ASE 2022* 

abstract: "Unit tests are widely used to check source code quality, but they can be too coarse-grained or ill-suited for testing individual program statements. We introduce inline tests to make it easier to check for faults in statements. We motivate inline tests through several language features and a common testing scenario in which inline tests could be beneficial. For example, inline tests can allow a developer to test a regular expression in place. We also define language-agnostic requirements for inline testing frameworks. Lastly, we implement I-Test, the first inline testing framework. I-Test works for Python and Java, and it satisfies most of the requirements. We evaluate I-Test on open-source projects by using it to test 144 statements in 31 Python programs and 37 Java programs. We also perform a user study. All nine user study participants say that inline tests are easy to write and that inline testing is beneficial. The cost of running inline tests is negligible, at 0.007x–0.014x, and our inline tests helped find two faults that have been fixed by the developers." 

# Summary. An optional shortened abstract.
summary: "A new type of statement-level tests"

tags: ["inline testing"]

# Display this page in the Featured widget? 
featured: true

url_pdf: ''
url_code: 'https://github.com/EngineeringSoftware/inlinetest'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'inline-tests-slides.pdf'
url_source: ''
url_video: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Overview of techniques'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- inline-tests

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
