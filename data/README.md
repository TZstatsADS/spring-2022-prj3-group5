### Data folder

The data directory contains data used in the analysis. This is treated as read only; in paricular the R/python files are never allowed to write to the files in here. Depending on the project, these might be csv files, a database, and the directory itself may have subdirectories.

+ **Details**: Since image data is large to be uploaded, the data is not saved here. The folder strucutre follows:
```
data/
├──images/
├────XXXXX.png (image data for training)
├────testXXXXX.png (image data for testing)
├── clean_labels.csv
├── noisy_labels.csv
|── label_prediction.csv

```
