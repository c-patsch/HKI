
# HKI dataset  


We provide the dataset under the following link:  

The dataset has the following structure:  

![image info](images/data_structure.png)
 
 
The feats folder contains the synthetic and real features of the respective backbone models I3D and S3D.  
The gt folder contains the ground truth for the synthetic and real videos, where each line in the respective .txt file indicates the annotation for a frame within the video.  
The vids folder contains all of the synthetic and real videos.  
The splits file contains all the necessary splits to keep the evaluation the same with respect to the results of our paper. The test split remains constant throughout the varying experiments.  
The mapping.txt file maps the label names to the respective line numbers.


