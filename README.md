Attire Classifier
-Arunchandra Boini
 
About the model:
The model which I have build classifies the attire into formal or casual by giving an image of a person as an input.
Note: The model only classifies western wear as the formal or casual for now as the scope of the dataset is bounded to western only.


Dataset:
      	The dataset contains the images that are classified into formal and casual
          	Please follow the link below to download the dataset:
          	https://drive.google.com/file/d/125ZfzE0TsvGs_2HBEC0W6WYlox2wBBnl/view?usp=share_link
           
           
Environment:
●	I have used Google colab to run my code with GPU hardware accelerator
●	Python version python==3.7.15
●	The python packages which I have user are:
             keras==2.9.0
             Keras-Preprocessing==1.1.2
             keras-vis==0.4.1
             matplotlib==3.2.2
             matplotlib-venn==0.11.7
             numpy==1.21.6
             opencv-contrib-python==4.6.0.66
             opencv-python==4.6.0.66
             opencv-python-headless==4.6.0.66
             tensorflow==2.9.2
             tensorflow-datasets==4.6.0
             tensorflow-estimator==2.9.0
             tensorflow-gcs-config==2.9.1
             tensorflow-hub==0.12.0
             tensorflow-io-gcs-filesystem==0.27.0
             tensorflow-metadata==1.11.0
             tensorflow-probability==0.17.0

Accuracy metrices: Can be viewed via plots after training the model.
 
Steps to run the model:
1.	Download and upload dataset to google drive
2.	Open the attire_classifier.ipynb in google colab
3.	Change the runtime to GPU accelerator
4.	Run the cells one by one by changing the paths appropriately
5.	After compiling and saving the model upload any image to google drive or colab and provide the path to load_image() in the After training and saving model section to predict the label.
