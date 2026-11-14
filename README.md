### Intra-subject random forest for UL use detection

Code to reproduce the results comparing three cross-validation strategies
(random window-level, continuous within-task, leave-one-task-out) for
detecting UL use. Data is from a previous pilot study dataset. 

### Environment

```
pip install -r requirements.txt
```

### How to run

The notebook uses relative paths (`../data/right.csv` and `../results/`), so it
must be run from inside the `Code/` folder.

```
cd Code
jupyter nbconvert --to notebook --execute intra_subject_random_forest_splits.ipynb
```

or open the notebook in Jupyter and select *Restart Kernel and Run All Cells*. Results are deterministic (fixed seed 42).

