# tensorflow-real-time-detection

In this repository, I am going to show how to run tensorflow object detection model using a web cam.Follow these steps to install tensorflow in windows and these steps will more similar to linux also.

## Step 1:  
            pip install tensorflow (Excute this command in anaconda prompt or terminal)
            
            Chech these packages are been installed
            
            pip install  Cython
            pip install  contextlib2
            pip install  pillow
            pip install  lxml
            pip install  jupyter
            pip install  matplotlib
            

## Step 2:  

[Clone](https://github.com/tensorflow/models/) the tensorflow repository from github

## Step 3:  

[Clone my repository](https://github.com/12345k/tensorflow-real-time-detection) and save it in seprate folder

## Step 4:  
            Now copy the content inside protoc-3.4.0-win32 in my repository and paste it inside the model folder from tensorflow                     repository

## Step 5: 
            Now open cmd or terminal naviagte to tensorflow model. Keep your current directory to models\research.Your current directory             should be under the research folder. 

            Now exceute  this command: protoc object_detection/protos/*.proto --python_out=.
            
            If it is not complie then give full path and then execute.
            
## Step 6: 
            Now copy tensorflow-real-time-detection.ipynb inside my repo and paste under the object detection folder path is                         (models\research\object_detection) and run the ipython notebook file in jupyter to see the output.
            
           
