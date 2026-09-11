# Introduction to Data Science — Sahmyook University

Public course materials for **Introduction to Data Science** at Sahmyook University:
labs, homework, lecture notebooks, and projects.

The materials are adapted from [UC Berkeley's Data 8 / *Foundations of Data Science*](https://data8.org)
public course materials, which are released under a Creative Commons licence
(see [LICENSE.md](LICENSE.md)).

## Contents

| Folder      | What's in it                                                    |
|-------------|-----------------------------------------------------------------|
| `lab/`      | 10 weekly lab assignments (`lab01`–`lab10`)                       |
| `hw/`       | 12 homework assignments (`hw01`–`hw12`)                           |
| `project/`  | 3 projects (`project1`–`project3`)                                |
| `lectures/` | Lecture demo notebooks (`lec01`–`lec43`)                          |

## Running the notebooks

Every lab, homework, and project notebook opens in **Google Colab** and is
self-contained: the first cell installs the dependencies, clones this
repository, and sets up the autograder.

```python
!pip install -q otter-grader datascience
!git clone https://github.com/jihyungkim94/datascience.git
```

Check your answer to a question by running the `grader.check("...")` cell that
follows it. The tests are stored in each notebook's `otter` metadata, so the
notebook carries its own autograder.

To run them locally instead:

```bash
pip install otter-grader datascience jupyterlab
jupyter lab
```

Lecture notebooks have no autograder — run them top to bottom.
