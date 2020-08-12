Project layout:

<p><h7> --Naira_Model_Dataset<br>
--Naira Residual Network.ipynp<br>
    --final_output.ipynb<br>

Phase One: 
##### WIP: Augment the images into categorical sub-directories -- this has been completed but the lack of augmentation is due to the current implementation 

Current Succession Build: Compose data directory into training,validation,and testing data for currency detection. the directory can be found <a href="">here</a>. please download into Naira_Model_Dataset directory as it is currently empty.

Phase 2: Implement the use of a Residual Covolutional Neural Network 
1. Save the training model to a hdf5 model for use of final testing of data.<br>
2. Save the hdf5 format into tflite for mobile.<br> 
3. Save neural network graph to Tensorboard host for visual implemenation of the algorithm.<br>

##### optional : uncomment the edge detector algorithm in the Naira Residual Netowrk Ipynb 
-- helper.txt -> tensorboard  
<a href="localhost:6006">localhost</a>