Crop Prediction and Analysis using Machine Learning

Locations of important files and datasets:
•	Dataset named “Crop_recommendation.csv” can be found inside the zip file.
•	Jupyter Notebook runnable file is inside ipynb-Jupyter Notebook folder
Library Installation:
•	Install the following libraries using pip install command from anaconda command shell.
Numpy, Pandas, Matplotlib, Seaborn, Sklearn, Pickle, Tkinter


How to run the ipynb file:
•	Install Anaconda Navigator from here: 
https://sparkbyexamples.com/python/how-to-install-anaconda-on-windows
Installation guide for Anaconda Navigator: https://docs.anaconda.com/anaconda/install/

•	From Anaconda Navigator open Jupyter Notebook. After that open the directory where the ipynb file is saved. Now load the file in the Jupyter Notebook text editor. 

•	In line 2 of ipynb file, put the directory where crop_recommendation.csv is saved.


# loading dataframe
crop_df = pd.read_csv('Crop_recommendation.csv')

 
Crop’s Images:
•	All the crop’s images are inside the images folder.
•	In line 44 of code, we are passing the name of the folder “image” to retrieve the particular image. So, if the folder name is changed, it must be updated in the code.

bg_img = Image.open('./images/bg.jpg') # load the background image
bg_label = tk.Label(crop_window)
bg_label.place(x=0, y=0, relwidth=1, relheight=1) # make bg_label to fit crop_window 
bg_label.bind('<Configure>', on_resize) # call on_resize whenever bg_label is resized
 



