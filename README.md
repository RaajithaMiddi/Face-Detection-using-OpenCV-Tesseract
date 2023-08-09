# Face-Detection-using-OpenCV-Tesseract

## Directory Structure

The directory is organized as follows:

1. **Data**: Contains the path to the zip files located on google drive, as the size is large (**accessible and can be downloaded**). It also contains a folder "Output" in which the expected output images are added.
2. **Pillow,Pytesseract,OpenCV.ipynb**: Contains code for the below-mentioned project.

**Note:** In the code, to access the zip file, I didn't mention the google drive path. Rather, I mentioned just the file name. So, you can download the files and change the path. 


## Project Details

Take a ZIP file of images and process them, using a library built into python. A ZIP file takes several different files and compresses them, thus saving space, into one single file. The files in the ZIP file are newspaper images (like you saw in week 3). Task is to write python code which allows one to search through the images looking for the occurrences of keywords and faces. E.g. if you search for "pizza" it will return a contact sheet of all of the faces which were located on the newspaper page which mentions "pizza".

Each page of the newspapers is saved as a single PNG image in a file called images.zip. These newspapers are in English, and contain a variety of stories, advertisements and images. Note: This file is fairly large (~200 MB) and may take some time to work with, use small_img.zip for testing.

Here's an example of the output expected. Using the small_img.zip file, if searched for the string "Christopher", the following image has to be displayed:

![alt text](https://github.com/RaajithaMiddi/Face-Detection-using-OpenCV-Tesseract/blob/main/Data/Output/small_project.png)

If using the images.zip file, searched for "Mark", the following image has to be displayed (note that there are times when there are no faces on a page, but a word is found!):

![alt text](https://github.com/RaajithaMiddi/Face-Detection-using-OpenCV-Tesseract/blob/main/Data/Output/large_project.png)

Note: That big file can take some time to process! Use the small one for testing.
