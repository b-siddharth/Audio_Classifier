# Audio_Classifier


**Bird Audio Classifier Project**


This project is designed to classify bird noises, with a specific focus on distinguishing Capuchinbird calls from other sounds. The dataset is organized into three categories: forest recordings, Parsed_Capuchinbird_Clips, and Parsed_Not_Capuchinbird_Clips.

Summary:


  Installation:


  Dependencies, including TensorFlow and matplotlib, can be installed using the provided pip command.


  Data and Model:



  Loaded audio data using TensorFlow.


  Created TensorFlow datasets for positive (Capuchinbird) and negative (non-Capuchinbird) samples.


  Built a deep learning model for classification using TensorFlow and Keras.



  Preprocessing:
  
  
  Calculated the average length of a Capuchinbird call.
  
  
  Developed a preprocessing function to convert audio clips into spectrograms.
  
  
  Training and Evaluation:
  
  
  Created a TensorFlow data pipeline.
  
  
  
  Split the dataset into training and testing partitions.
  
  
  Trained the model and visualized loss, precision, and recall.
 
  
  Making Predictions:
  
  
  Made predictions on single audio clips.
  
  
  Parsed forest recordings, converting MP3 files to spectrograms.
  
  
  Grouped consecutive detections and exported the results.


  Results:
  

  
  Exported classification results to 'results.csv'.

