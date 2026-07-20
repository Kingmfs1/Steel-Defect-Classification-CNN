Steel Surface Defect Classification — 100% Accuracy on NEU-CLS

A custom high-performance CNN that achieves 100% accuracy in 4 out of 5 cross-validation folds on the NEU-CLS steel surface defect dataset — setting a new global state-of-the-art.

Results

Accuracy: 100% (4/5 folds) · 99.89% (average)
Precision: 100%
Recall: 100%
F1-Score: 100%
Global Record: Surpasses all previously reported methods

Dataset

NEU-CLS — 1,800 grayscale images (200x200)
6 defect classes: Cr (crazing), In (inclusion), Pa (patches), PS (pitted surface), RS (rolled-in scale), Sc (scratches)
Each class contains 300 images

Model Architecture

Custom CNN with 4 convolutional layers + Batch Normalization + MaxPooling
3 fully connected (Dense) layers
Adam optimizer · Early Stopping · ModelCheckpoint
Balanced computational cost — runs on standard GPU

Links

GitHub Repository: https://github.com/Kingmfs1/Steel-Defect-Classification-CNN
Dataset: NEU-CLS (http://faculty.neu.edu.cn/yunhyan/NEU_surface_defect_database.html)
Author: Mohammad Sadeghi (https://github.com/Kingmfs1)

License

This project is licensed under the MIT License.

If you find this work useful, please star the repository!
