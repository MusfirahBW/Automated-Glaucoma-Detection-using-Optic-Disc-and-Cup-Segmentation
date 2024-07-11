# Automated-Glaucoma-Detection-using-Optic-Disc-and-Cup-Segmentation
This project contributes to the advancement of automated glaucoma detection using retinal image analysis. By developing a robust and accurate segmentation algorithm, using RNNs and CNNs in Python.

# Statement:
Glaucoma is an eye disease that can cause loss of vision by damaging the optic nerve. It is the second leading cause of blindness worldwide after cataract. Early diagnosis of glaucoma is a key to prevent permanent blindness, yet it has no noticeable early symptoms. Color fundus photography allows the optic disk to be examined which is a fundamental step to diagnose glaucoma. This is done by measuring the vertical cup-to-disk ratio (CDR).

# Significance:
This project contributes to the advancement of automated glaucoma detection using retinal image analysis. By developing a robust and accurate segmentation algorithm, the project aims to:
• Improve the efficiency and objectivity of glaucoma diagnosis.
• Reduce reliance on subjective visual assessment by ophthalmologists.
• Facilitate early detection of glaucoma, leading to improved patient outcomes.

# Methodology:
Develop a novel image segmentation algorithm to automatically delineate the optic disc (OD) and optic cup (OC) within retinal fundus images from the ORIGA dataset. This segmentation will facilitate the calculation of the cup-to-disc ratio (CDR), a crucial parameter for glaucoma detection.

## 1. Optic Disc Segmentation: The algorithm will be designed to first segment the OD region. This can be achieved by employing deep learning architectures, such as convolutional neural networks (CNNs) or U-Nets, trained on a set of labeled fundus images where the OD is accurately outlined.
## 2. Optic Cup Segmentation: Following successful OD segmentation, the algorithm will focus on delineating the OC within the previously identified OD region. This can be achieved by refining the initial segmentation or employing a separate method specifically trained for OC segmentation within pre-segmented OD regions.

## 3. Cup-to-Disc Ratio (CDR) Calculation: Once both OD and OC are segmented, the CDR will be automatically calculated as the ratio of the OC area to the OD area. This quantitative measure serves as a vital indicator for glaucoma diagnosis.

# Evaluation:
1. Employ standard metrics like accuracy, precision, recall, and Intersection over Union (IoU) to assess segmentation performance.
2. Compare calculated CDR with established clinical criteria for glaucoma diagnosis.
Constraints:
Develop an algorithm meeting the below time and accuracy/sensitivity requirements.
1. Time complexity between 10-30 seconds per image for unsupervised method.
2. Time complexity between 10-30 milliseconds per image for supervised method
3. Segmentation accuracy of OD and OC between 90-95%.
4. Segmentation sensitivity/recall of OD and OC between 80-90%.

# Dataset: ORIGA
