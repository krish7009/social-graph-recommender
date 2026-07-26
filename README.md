# Social Graph Recommendation Engine

Two graph-based recommendation algorithms over a synthetic social network dataset (`massive_data.json`: 30 users, friend connections, and page likes).

## Algorithms

### 1. People You May Know (`people_you_may_know.ipynb`)
Suggests new friends by counting mutual connections: for a given user, looks at friends-of-friends who aren't already direct friends, and ranks them by how many mutual friends they share.

### 2. Pages You May Like (`pages_you_may_like.ipynb`)
Suggests pages by looking at what a user's friends have liked. Pages the user doesn't already follow are ranked by how many friends liked them.

### 3. Data Cleaning (`codebook_datacleaning.ipynb`)
Cleans a raw version of the dataset: drops records with missing names, removes duplicate friend IDs and duplicate page entries, and exports the cleaned dataset.

## Tech stack
Python · dictionaries/sets for graph representation · JSON I/O
