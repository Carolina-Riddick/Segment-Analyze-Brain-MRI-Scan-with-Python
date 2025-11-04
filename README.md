# <span style="color:rgb(213,80,0)">Segment and Analyze Brain MRI Scan Using Python</span>

Converted to Python for execution in Kaggle. This notebook reproduces the typical steps:
- Load MRI NIfTI (`.nii` / `.nii.gz`) with `nibabel`
- Visualize slices with `matplotlib` and `nilearn`
- Quick brain segmentation using Otsu thresholding (`scikit-image`)
- Compute basic volumes and save outputs

Notes:
- If you run this in Kaggle ensure your data files (e.g. `brainSegData_anat.nii.gz`) are placed under `/kaggle/input/` or uploaded to the notebook's working directory.
- The notebook uses `nibabel`, `nilearn`, `scikit-image`, `numpy`, `matplotlib`. Install them in the Kaggle notebook cell if needed.

[Kaggle notebook](https://www.kaggle.com/code/carolinariddick/segment-analyze-brain-mri-scan-with-python/edit)
