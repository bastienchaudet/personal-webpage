---
title: 'An optimized Space-Time Multigrid algorithm for parabolic PDEs'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Bastien Chaudet-Dumas
  - Martin J. Gander
  - Ausra Pogozelskyte

date: '2023-03-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-03-01T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['3']

# Publication name and optional abbreviated publication name.
publication: Submitted

abstract: "We investigate three directions to further improve the highly efficient Space-Time Multigrid algorithm with block-Jacobi smoother introduced in [GanNeu16]. First, we derive an analytical expression for the optimal smoothing parameter in the case of a full space-time coarsening strategy; second, we propose a new and efficient direct coarsening strategy which simplifies the code by preventing changes of coarsening regimes; and third, we also optimize the entire two cycle to investigate if further efficiency gains are possible. Especially, we show that our new coarsening strategy leads to a significant efficiency gain when the ratio τ/h2 is small, where τ and h represent the time and space steps. Our analysis is performed for the heat equation in one spatial dimension, using centered finite differences in space and Backward Euler in time, but could be generalized to other situations. We also present numerical experiments that confirm our theoretical findings."

tags: []

# Display this page in the Featured widget?
featured: true

url_pdf: '/publication/opt-STMG/An_optimized_space_time_multigrid_algorithm_for_parabolic_PDEs_arXiv.pdf'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

---
