---
title: "CrawLabel: Computing Natural-Language Labels for UI Test Cases"

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here 
# and it will be replaced with their full name and linked to their profile.
authors:
- admin
- Rahulkrishna Yandrapally
- Anup K. Kalia
- Saurabh Sinha
- Rachel Tzoref-Brill
- Ali Mesbah

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

abstract: "End-to-end test cases that exercise the application under test via its user interface (UI) are known to be hard for developers to read and understand; consequently, diagnosing failures in these tests and maintaining them can be tedious. Techniques for computing natural-language descriptions of test cases can help increase test readability. However, so far, such techniques have been developed for unit test cases; they are not applicable to end-to-end test cases.\\

In this paper, we focus on the problem of computing natural-language labels for the steps of end-to-end UI test cases for web applications. We present two techniques that apply natural-language processing to information available in the browser document object model (DOM). The first technique is an instance of a supervised approach in which labeling-relevant DOM attributes are ranked via manual analysis and fed into label computation. However, supervised approach requires a training dataset. So we propose the second technique, which is unsupervised: it leverages probabilistic context-free grammar learning to compute dominant DOM attributes automatically. We implemented these techniques, along with two simpler baseline techniques, in a tool called CrawLabel (available as a plugin to Crawljax, a state-of-the-art UI test-generation tool for web applications) and evaluated their effectiveness on open-source web applications. Our results indicate that the supervised approach can achieve precision, recall, and F1-score of 83.38, 60.64, and 66.40, respectively. The unsupervised approach, although less effective, is competitive, achieving scores of 72.37, 58.12, and 59.77. We highlight key results and discuss the implications of our findings." 

# Summary. An optional shortened abstract.
summary: "Automatically generating natural-language labels for the steps of end-to-end UI test cases for web applications."

tags: ["UI testing", "test summarization"]

# Display this page in the Featured widget? 
featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: 'https://utexas-my.sharepoint.com/:v:/g/personal/yl34469_austin_eid_utexas_edu/ES_ZXC84rKZDo6VNtTO5yTcBMFKGWZ8d2YqT2ruAq7HU4g?e=mgvhRS'


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
- ui-test-summarization

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---


