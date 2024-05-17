---
title: "ExLi: An Inline-Test Generation Tool for Java"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Aditya Thimmaiah
- Owolabi Legunsen
- Milos Gligoric

## Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2024-05-15T00:00:00Z"
doi: ""

## Schedule page publish date (NOT publication's date).
# publishDate: "2022-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name. 
publication: In *The ACM International Conference on the Foundations of Software Engineering, Tool Demonstrations*
publication_short: In *FSE demo 2024*

abstract: "We present ExLi, a tool for automatically generating inline tests, which were recently proposed for statement-level code validation. ExLi is the first tool to support retrofitting inline tests to existing codebases, towards increasing adoption of this type of tests. ExLi first extracts inline tests from unit tests that validate methods that enclose the target statement under test. Then, ExLi uses acoverage-then-mutants based approach to minimize the set of initially generated inline tests, while preserving their fault-detection capability. ExLi works for Java, and we use it to generate inlinetests for 645 target statements in 31 open-source projects. ExLi reduces the initially generated 27,415 inline tests to 873. ExLi improves the fault-detection capability of unit test suites from which inline tests are generated: the final set of inline tests kills up to 24.4% more mutants on target statements than developer written and automatically generated unit tests. ExLi is open sourced at https://github.com/EngineeringSoftware/exli and a video demo is available at https://youtu.be/qaEB4qDeds4." 

# Summary. An optional shortened abstract.
summary: "Extracting inline tests from running unit tests."

tags: ["inline testing"]

# Display this page in the Featured widget? 
featured: true

url_pdf: ''
url_code: 'https://github.com/EngineeringSoftware/exli'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- inline-tests-extraction

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
