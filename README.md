# Image-Search-System-with-Automatic-Weighting
Abstract : The existing image search system often faces difficulty to find a appropriate retrieved image corresponding to an image query. The difficulty is commonly caused by that the users’ intention for searching image is different with dominant information of the image collected from feature extraction. In this paper we present a new approach for content-dependent image search system. The system utilizes information of color distribution inside an image and detects a cloud of clustered colors as something - supposed as an object. We applies segmentation of image as content-dependent process before feature extraction in order to identify is there any object or not inside an image. The system extracts 3 features, which are color, shape, and texture features and aggregates these features for similarity measurement between an image query and image database. HSV histogram color is used to extract color feature of image. While the shape feature extraction used Connected Component Labeling (CCL) which is calculated the area value, equivalent diameter, extent, convex hull, solidity, eccentricity, and perimeter of each object. The texture feature extraction used Leung Malik (LM)’s approach with 15 kernels.  For applicability of our proposed system, we applied the system with benchmark 1000 image SIMPLIcity dataset consisting of 10 categories namely Africans, beaches, buildings historians, buses, dinosaurs, elephants, roses, horses, mountains, and food. 


Reference : https://emitter.pens.ac.id/index.php/emitter/article/view/361
