1. Introduction : 
In recent years, autonomous driving technology using LiDAR and cameras has been actively researched and developed. Road segmentation, crucial for vehicle autonomy, is also essential in automotive engineering and civil engineering road-related projects. Initially, LiDAR-based technologies were predominant, but their high cost limited widespread industrial application. The emergence of RGB camera-based lane detection and distance measurement technologies expanded their use across various industries. However, incidents like Tesla's trailer collision, misidentified as a lane, decreased the reliability of RGB camera-based technologies. To address this, efforts to improve distance measurement accuracy using LiDAR led to the development of LiDAR-Camera fusion technology. Multi-modality fusion enhances accuracy by leveraging complementary characteristics of different data sources, thereby increasing user trust.
This study evaluates various LiDAR-Camera fusion algorithms using real driving datasets to identify the most accurate one. We conducted experiments with three machine learning algorithms: USNet, SNE-RoadSeg, and a Co-Training Algorithm. 
![image](https://github.com/Leejunsik-sju/-/assets/173447105/9b846cdc-3b70-4c5a-b750-567aba2ad953)

3. Model :
USNet, SNE-RoadSeg, Co-Training Algorithm

4. Result :
The experiments utilized the KITTI dataset, consisting of labeled road data captured by vehicle-mounted LiDAR and cameras. Performance metrics included MaxF, PRE, and REC, with USNet demonstrating the highest accuracy (MaxF: 97.31%, PRE: 97.20%, REC: 97.42%), followed by SNE-RoadSeg, and the Co-Training Algorithm showing the lowest performance. The findings confirm USNet as the most effective algorithm for LiDAR-Camera fusion in road segmentation, providing high accuracy and computational efficiency.

