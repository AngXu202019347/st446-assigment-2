# Assignment2 - LT 2021-2022

This assignment covers two questions related to graph data processing and topic modelling.

## Questions

This assignment consists of two parts. Each part is worth 50/100 marks.

### P1: Querying the YAGO semantic knowledge base

[YAGO](https://dl.acm.org/doi/10.1145/1242572.1242667) (Yet Another Great Ontology) is a Knowledge Graph that augments WordNet with common knowledge facts extracted from Wikipedia, converting WordNet from a primarily linguistic resource to a common knowledge base. YAGO originally consisted of more than 1 million entities and 5 million facts describing relationships between these entities (see [here](https://paperswithcode.com/dataset/yago)).

**Action items** for completing this question:
* Instantiate a Dataproc cluster using the same configuration used in [Week05](https://github.com/lse-st446/lectures2022/tree/main/Week05).
* Open the [hw_yago_local.ipynb](./hw_yago_local.ipynb) notebook and follow the instructions to download the datasets.
* Fill in all the ``<YOURCODE>`` placeholders.
* Save the notebook with the outputs and submit it as part of your solution.

### P2: Topic modelling for DBLP

You will reproduce a similar example discussed in Week09, but using the DBLP database used in Week02 and Week03.

**Action items** for completing this question:
* Instantiate a Dataproc cluster using the same configuration used in [Week09](https://github.com/lse-st446/lectures2022/tree/main/Week09).
* Open the [hw_dblp.ipynb.ipynb](./hw_dblp.ipynb) notebook and follow the instructions. Make sure you download the dataset and put it into a bucket.
* Fill in all the ``<YOURCODE>`` placeholders.
* Save the notebook with the outputs and submit it as part of your solution.

**IMPORTANT**:

* Please do not wait until the last minute to do this assignment. As some of the input data is of large volume, some of the code may take a long time to run.

* Please let us know if you are running low of your GCP credits, so we can provide you another coupon.

## Marking scheme

| **Problem breakdown** | **Max marks** |
|-------------------|--------------:|
| P1-A Politicians who are also scientists (sorted alphabetically by name of person). | 10 |
| P1-B Companies whose founders were born in London (sorted alphabetically by name of founder). | 10 |
| P1-C Writers who have won a Nobel Prize (in any discipline) (sorted alphabetically by name of person). | 10 |
| P1-D Nobel prize winners who were born in the same city as their spouses. | 10 |
| P1-E Politicians that are affiliated with a right-wing party (sorted alphabetically by name of person). | 10 |
| P2-A Conversion titles->tokens->sparse vectors. Application of LDA. Discussion of results. | 25 |
| P2-B Conversion of tokens and LDA. Topic density and cosine similarity. Discussion of results. | 25 |
| Total | 100 |

## Submission date and guidelines

1. Solution deadline: **31 March, 6:00 pm**.
2. Upload your Python code (including discussion/explanation for each question) and additional files (if any) into GitHub. 
3. Please, **use only the GitHub repository created by GitHub classroom. Do not fork or use a private repository, as we cannot track your submission**.
4. There is no need for uploading training and testing datasets.
5. **IMPORTANT**: for completing your submission, go to [Moodle](https://moodle.lse.ac.uk/mod/assign/view.php?id=1080400) (Assessment 2 section) and **provide a file with a link to your GitHub repository** (this must be done by the deadline). 
6. Feedback and provisional marks will be provided only on GitHub (not on Moodle).

