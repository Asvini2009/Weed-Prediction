**Soy Weed Detection Dataset:**
The images from the dataset capture the progression of the weed and soy plant crops over different stages of the growth cycle, varying chemical treatment conditions, and also contain 3 distinct plant species, Glycine max(soy), Amaranthus viridis(caruru weed), and Cynodon dactylon(grassy weed). In this study, I used Roboflow to convert the dataset from the COCO format to the YOLO format to enhance object detection model training. Roboflow generated YOLO specific annotations which include normalized bounding box parameters, the images were parsed and linked with the annotations automatically. The conversion process also generated a .yaml file, which outlines the dataset configurations such as paths to the training and validation datasets, the number of classes, and class names.
https://github.com/raulsteinmetz/soy-segmentation-ds

More Information about this research can be found here : 
Thivakaran, Asvini, and Vani Kandasamy. "AI-driven method for weed detection in soy plants using YOLO instance segmentation model." Applications of Machine Learning 2025. Vol. 13606. SPIE, 2025.
