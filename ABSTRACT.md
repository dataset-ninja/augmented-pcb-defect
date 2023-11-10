**Augmented PCB Defect** is a dataset designed for object detection, encompassing 10,668 images with 21,664 labeled objects across six distinct classes, including *mouse_bite*, *missing_hole*, *spurious_copper*, and others such as *spur*, *open_circuit*, and *short*. Meticulously curated with a focus on Tiny Defect Detection (TDD), this dataset plays a pivotal role in advancing quality control measures in the production of printed circuit boards (PCBs), a fundamental and crucial aspect of manufacturing processes in the electronics industry.

This dataset is the result of comprehensive experimentation conducted on the original PCB Defect Dataset [(available on DatasetNinja)](https://datasetninja.com/pcb-defect). The initial dataset comprises 693 PCB defective images, each annotated with corresponding files. The average pixel size of each image in this dataset is 2,777x2,138. The PCB defects are categorized into 6 classes, including missing hole, mouse bite, open circuit, short, spur, and spurious copper, with each image potentially containing multiple defects. Recognizing the limitations of the small dataset, data augmentation techniques were applied before training, and subsequently, the images were cropped into 600x600 sub-images. This process resulted in the creation of a training set and a testing set, comprising 9,920 and 2,508 images, respectively, contributing to a more robust and diversified dataset for the development and evaluation of object detection models in the context of PCB defect detection.

| Type of Defects   | Number of Images | Number of Defects |
|-------------------|------------------:|-------------------:|
| Missing Hole      | 1832             | 3612              |
| Mouse Bite        | 1852             | 3684              |
| Open Circuit      | 1740             | 3548              |
| Short             | 1732             | 3508              |
| Spur              | 1752             | 3636              |
| Spurious Copper   | 1760             | 3676              |
| **Total**         | **10,668**       | **21,664**         |

<i>Please note that the distribution of train/test/val does not match what the authors indicate in the article.</i>
