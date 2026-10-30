# Machine Learning

Theory assignments, practical notebooks, and contest work from the first semester of my M.Sc. in Computer Engineering at Sharif University of Technology, taught by Dr. Ali Sharifi-Zarchi. Author: Farzan Rahmani.

## Repository Guide

| Path | Contents |
| --- | --- |
| `HWs/HW1/` | Introductory practical exercises and perceptron notebooks, with starter and submitted versions |
| `HWs/HW2/` | K-nearest neighbors, ensembles, clustering, and PCA |
| `HWs/HW3/`–`HWs/HW6/` | Subsequent practical/theory assignments, including original question notebooks and submissions |
| `ML_contest/ML/` | General machine-learning contest notebook |
| `ML_contest/NLP/` | NLP contest notebook |
| `ML_contest/Vision/` | Computer-vision contest notebook |
| `exam/` | Exam material |
| `ML Cheatsheet.pdf`, `src.txt` | Reference sheet and resource link |

## Getting Started

Use Python with Jupyter or another notebook environment. For the scikit-learn assignments, a starting environment is:

```sh
python -m pip install jupyterlab numpy pandas scikit-learn matplotlib seaborn
python -m jupyterlab
```

Additional assignments and contest notebooks may need their own deep-learning or NLP libraries. Check each notebook's setup/import cells and choose compatible versions; the repository does not supply one pinned environment for all exercises.

## Working Through an Assignment

1. Read the question notebook and accompanying theory material.
2. Open the submitted version, often identified by `FarzanRahmani` or `403210725` in its filename.
3. Check dataset locations and expected filenames. Some notebooks read relative names such as `dataset.csv` or `test.csv`.
4. Run preprocessing, splitting, fitting, and evaluation cells in order.

Keep validation and test data separate when comparing models. Saved metrics depend on the data split, preprocessing, random seeds, and library versions. Contest datasets or pretrained resources may need to be obtained from their original sources.

## Scope and License

This is an academic archive of independent experiments, question templates, and submissions. See [LICENSE](LICENSE) for repository license terms; supplied course material and external datasets retain their own attribution and terms.
