TV News Commercial Detection 

This is the project repository for the semester project in Big Data and Analytics course

This project uses pySpark to build a clasifier to classify a TV news channel frame as either Commercial or Non-Commercial, based on a set of Audio Visual Features.

Goal to automatic identiﬁcation and extraction of commercial blocks in telecast news videos
Extraction of commercials is an important preprocessing step in broadcast media analysis, and evaluation of video analysis is crucial for competitive marketing analysis and advertising planning
News channels do not follow any particular news presentation format, have large variability and dynamic nature
Hence, automatic identification of commercial blocks using machine learning approaches provides a viable alternative
##Step:-

Data Extraction
This data was obtained from UCI machine learning repository . The dataset contained around 20 million data points making it a big data problem.
Preprocessing and Data Engineering The data was in libsvm(sparse) format and it had to be converted into tabular format for analysis and modelling
Modelling and optimization
For the modelling part, three learning algorithms were used. -Logistic regression with elastic net regularization -Random Forest Classifier -Gradient Boosting Machine
Interpretion and Inference
Demo
