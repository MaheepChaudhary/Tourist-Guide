# Tourist-Guide
This model is inspired by the problem of SIH 2020 i.e. Virtual Tourist Guide. The whole problem is that a user can take a picture of a monument and the information will come automatically about that monument on the page of tripadvisor.com. I extracted the pictures using Selenium and did data augmentation them using OpenCV by making them of gray colour, flipping them 180 and also did both when dor some monuments the trained my model for three monuments due to lack of time and availability of arrranged data. The monumets taken are Eiffel Tower, Taj Mahal and Statue of Liberty. The manipulation code that I uploaded is just of State of Liberty. I trained my model on Convolutional Neural Network to obtain optimum performance by taking dataset of approximate 1000 images per monument. Here by using BeautifulSoup you can extract link to the monument and other feature required for the comptetion. 

Information about file names:-
1.) all_data_test.rar and all_data_train.rar contains training and testing data
2.) StatueOfLibertyDataManipulation.ipynb file contains the code before the data was created to increase our data by manipulating the           images in various ways
3.) Virtual_Tourise_Guide_Model.ipynb file contains the code of our training model.
4.) The VIRTUAL TOURIST GUIDE.pptx file conatins the ppt form of the project.
