---
title: Parallel Minimum Spanning Forest Computation using Sparse Matrix Kernels

summary: SIAM PP 2022
abstract: Formulations of graph algorithms using sparse linear algebra have yielded highly scalable distributed algorithms for problems such as connectivity and shortest path computation. We develop the first formulation of the Awerbuch-Shiloach parallel minimum spanning forest (MSF) algorithm using linear algebra primitives. We introduce a multilinear kernel that operates on an adjacency matrix and two vectors. This kernel updates graph vertices by simultaneously using information from both adjacent edges and vertices. In addition, we explore optimizations to accelerate the shortcutting step in the Awerbuch-Shiloach algorithm. We implement this MSF algorithm with Cyclops, a distributed-memory library for generalized sparse tensor algebra. We analyze the parallel scalability of our implementation on the Stampede2 supercomputer.

# Talk start and end times.
#   End time can optionally be hidden by prefixing the line with `#`.
date: "2022-02-25T13:00:00Z"
all_day: true

# Schedule page publish date (NOT talk date).
publishDate: "2017-01-01T00:00:00Z"

authors: []
tags: []

# Is this a featured talk? (true/false)
featured: false

image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/bzdhc5b3Bxs)'
  focal_point: Right

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects:
- example
---
