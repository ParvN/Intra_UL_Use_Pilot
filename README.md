### Intra-subject random forest for UL use detection

Code to reproduce the results comparing three cross-validation strategies
(random window-level, continuous within-task, leave-one-task-out) for
detecting UL use. Data is from a previous pilot study dataset. 

### Data

The data (`right.csv`) is from the
[upper-limb-use-assessment](https://github.com/biorehab/upper-limb-use-assessment/blob/146659eaec6055b6ac4c0f4a70c8a451db7d302f/control/data/right.csv)
repository. 

'Download it into `data/` before running the notebook.'

### Environment

```
pip install -r requirements.txt
```

### How to run

The notebook uses relative paths (`../data/right.csv` and `../results/`), so it
must be run from inside the `code/` folder or open the notebook in Jupyter and select *Restart Kernel and Run All Cells*. Results are deterministic (fixed seed 42).

