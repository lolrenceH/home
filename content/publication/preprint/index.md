---
title: "TrieDedup: A fast trie-based deduplication algorithm to
handle ambiguous bases in high-throughput sequencing"
authors:
- admin
- Sai Luo 
- Ming Tian 
- Adam Yongxin Ye

date: "2022-02-22T00:00:00Z"
doi: " https://doi.org/10.1101/2022.02.20.481170"

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: High-throughput sequencing is a powerful tool and is extensively applied in biological studies. However sequencers may report bases with low qualities and lead to ambiguous bases, 'N's. PCR duplicates introduced in library preparation need to be removed in genomics studies, and several deduplication tools have been developed for this purpose. However, the existing tools cannot deal with 'N's correctly or efficiently. Here we proposed and implemented TrieDedup, which uses trie (prefix tree) structure to compare and store sequences. TrieDedup can handle ambiguous base 'N's, and efficiently deduplicate at the level of raw sequences. We also reduced its memory usage by approximately 20% by implementing restrictedListDict. We benchmarked the performance of the algorithm and showed that TrieDedup can deduplicate reads up to 160-fold faster than pairwise comparison at a cost of 36-fold higher memory usage. TrieDedup algorithm may facilitate PCR deduplication, barcode or UMI assignment and repertoire diversity analysis of large scale high-throughput sequencing datasets with its ultra-fast algorithm that can account for ambiguous bases due to sequencing errors.

# Summary. An optional shortened abstract.
summary: We proposed and implemented TrieDedup to fastly and accurately deduplicate high-throughput sequencing experiments while accounting for sequencing artifacts. TrieDedup uses trie (prefix tree) structure to compare and store sequences. Our benchmark experiments show TrieDedup can deduplicate reads up to 160-fold faster than pairwise comparison at a cost of 36-fold higher memory usage. 

tags:
- Source Themes
featured: true

links:
- name: Custom Link
  url: https://www.biorxiv.org/content/10.1101/2022.02.20.481170v1
url_pdf: https://www.biorxiv.org/content/10.1101/2022.02.20.481170v1.full.pdf
url_code: 'https://github.com/lolrenceH/TrieDedup'
url_dataset: '#'
url_poster: '#'
url_project: ''
url_slides: ''
url_source: '#'
url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
