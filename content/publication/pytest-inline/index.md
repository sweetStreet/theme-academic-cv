---
title: "pytest-inline: An inline testing tool for Python"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Zachary Thurston
- Alan Han
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
publication: In *45th IEEE/ACM International Conference on Software Engineering, Tool Demonstrations*
publication_short: In *ICSE Demo 2023* 

abstract: "We present pytest-inline, the first inline testingframework  for  Python.  We  recently  proposed  inline  tests  tomake  it  easier  to  test  individual  program  statements,  but  thereis currently no framework-level support available for developersto  write  inline  tests  in  Python.  To  fill  this  gap,  we  design  andimplement  pytest-inline  as  a  pytest  plugin,  which  is  the  mostpopular Python testing framework. In pytest-inline, a developercan write inline tests by assigning test inputs to variablesin  the  target  statement  and  specifying  the  expected  outputs.Then,  pytest-inline  runs  each  inline  test  and  fails  if  the  targetstatement’s  output  does  not  match  the  expected  result.  In  thispaper, we describe the design of pytest-inline, the testing featuresthat  it  provides,  and  the  intended  use  cases.  Our  evaluation  ofpytest-inline on the inline tests we wrote for 80 target statementsfrom 31 open-source Python projects shows that using it to runinline tests incurs negligible overhead, at 0.012x. pytest-inline isopen-sourced, and a video demo of pytest-inline can be found athttps://www.youtube.com/watch?v=pZgiAxR_uJg." 

# Summary. An optional shortened abstract.
summary: "A new type of statement-level tests"

tags: ["inline testing"]

# Display this page in the Featured widget? 
featured: true

url_pdf: ''
url_code: 'https://github.com/pytest-dev/pytest-inline'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: 'pytest-inline-slides.pdf'
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
- inline-tests

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
