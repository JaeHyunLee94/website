---
title: 'Momentum-preserving inversion alleviation for elastic material simulation'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:

  - Heejo Jeong,
  - Seung-wook Kim
  - admin
  - Kiwon Um
  - Min Hyung Kee
  - JungHyun Han


# Author notes (optional)
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'

date: '2024-05-172T00:00:00Z'
doi: 'https://doi.org/10.1002/cav.2249'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-17T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In Computer Animation and Social Agents (CASA)
publication_short: In Computer Animation and Virtual Worlds

abstract: This paper proposes a novel method that enhances the optimization-based elastic body solver. The proposed method tackles the element inversion problem, which is prevalent in the prediction-projection approach for numerical simulation of elastic bodies. At the prediction stage, our method alleviates inversions such that the subsequent projection solver can benefit in stability and efficiency. To prevent excessive suppression of predicted inertial motion when alleviating, we introduce a velocity decomposition method and adapt only the non-rigid motion while preserving the rigid motion, that is, linear and angular momenta. Thanks to the respected inertial motion in the prediction stage, our method produces lively motions while keeping the entire simulation more stable. The experiments demonstrate that our alleviation method successfully stabilizes the simulation and improves the efficiency particularly when large deformations hamper the solver.

# Summary. An optional shortened abstract.
summary: Heejo Jeong, Seung-wook Kim, JaeHyun Lee, Kiwon Um, Min Hyung Kee, JungHyun Han
tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

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
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ''
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
  # - example

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Supplementary notes can be added here, including [code, math, and images](https://wowchemy.com/docs/writing-markdown-latex/). -->
