---
title: "Extracting inline tests from unit tests"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Pengyu Nie
- Anna Guo
- Milos Gligoric
- Owolabi Legunsen

## Author notes (optional)
# author_notes:
# - "Equal contribution"
# - "Equal contribution"

date: "2023-05-10T00:00:00Z"
doi: ""

## Schedule page publish date (NOT publication's date).
# publishDate: "2022-10-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name. 
publication: In *32th ACM SIGSOFT International Symposium on Software Testing and Analysis*
publication_short: In *ISSTA 2023*

abstract: "We recently proposed inline tests for validating individual programstatements; they allow developers to provide test inputs, expectedoutputs, and test oracles immediately after a target statement. But,existing code can have many target statements. So, automatic gen-eration of inline tests is an important next step towards increasingtheir adoption. We proposeExLi, the first technique for automat-ically generating inline tests.ExLiextracts inline tests from unittests; it first records all variable values at a target statement whileexecuting unit tests. Then,ExLiuses those values as test inputsand test oracles in an initial set of generated inline tests. Targetstatements that are executed many times could have redundant ini-tial inline tests. So,ExLiuses a novel coverage-then-mutants basedreduction process to remove redundant inline tests. We implementExLifor Java and use it to generate inline tests for 718 target state-ments in 31 open-source programs.ExLireduces 17,273 initiallygenerated inline tests to 905 inline tests. The final set of generatedinline tests kills up to 25.1% more mutants on target statementsthan developer written and automatically generated unit tests. Thatis,ExLigenerates inline tests that can improve the fault-detectioncapability of the test suites from which they are extracted." 

# Summary. An optional shortened abstract.
summary: "Extracting inline tests from running unit tests."

tags: ["inline testing"]

# Display this page in the Featured widget? 
featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'exli-slides.pdf'
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
- inline-tests-extraction

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
