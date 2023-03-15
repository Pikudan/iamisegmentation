# iamisegmentation
&ensp;&ensp;Kaggle - Community Prediction Competition - https://www.kaggle.com/competitions/iamisegmentation/overview.  
&ensp;&ensp;This competition was held as part of a special course "Introduction to medical image analysis" at CMС MSU in spring 2022. It was proposed to solve the problem of segmentation of muscle and fat tissues on CT images. High-quality automated marking of CT images is a very useful tool for doctors when examining a person, and also helps to detect diseases such as, for example, sarcopenia.  

&ensp;&ensp;This repository contains Jupyter-notebook. This segmentation problem is solved using U-NET. DICOM and Label were supplied as input data.In total, the data contains 60 CT images of muscle and fat, divided in a 2:1 ratio into training and test samples.  
The markup contains 4 classes:  

&ensp;&ensp;0 - background. 
&ensp;&ensp;1 - visceral fat, bones, organs. 
&ensp;&ensp;2 - muscles and intramuscular fat, bones. 
&ensp;&ensp;3 - subcutaneous fat. 
