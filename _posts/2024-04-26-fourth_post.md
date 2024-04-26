### Challenges with Assignment 2
TOC {:toc}

## Question 1
# GUI for fingerprint recognition Jupyter notebook:
- Enrolling a fingerprint and associating a name:

  I think my current implementation fulfills this requirement.
  
- Storing the template in a file/database:

  Need to figure out what exactly is to be stored.
  Does it need to be the template image itself or a tuple of the classifying information
  e.g. fingerprint shape, valid minutiae and local structures.

  My takeaway from comments on my question on the course discussion board:
  - I need to save the enrolled image into a 'database'/folder after I have uploaded it
  - Need to upload the whole original image, not the pre-processed template or a tuple containing classifying information.
    
- Comparison of new fingerprint with others in database:

   Working on this but first need to figure out what exactly is to be stored (as mentioned above).

# System analysis:
- System evaluation:

  Can't do this yet.
- ROC curve: error rates vs. threshold:

  Can't do this yet.
- Estimation of false positive rate when false negative rate is 1%:

  Can't do this yet.

## Question 4
Jupyter notebook to classify images with the same classes as the CIFAR10 dataset 
(i.e. airplane, automobile, bird, cat, deer, dog, frog, horse, ship, truck)

# Collecting data
- Pulling sample images (200) of each of the CIFAR10 classes:

I have adapted the code given within course22/00-is-it-a-bird-creating-a-model-from-your-own-data.ipynb
My adaptation of the original code (only changed the objects within the searches variable) invariably leads
to the error BrokenProcessPool in 'resize_images(path/o, max_size=400, dest=path/o)'

I do not have access to the declaration or definition of 'resize_images()' so it is very hard to debug this problem. 
I am going to try to get all the data I need using the GPU of the lab computer instead, theoretically this shouldn't 
make a difference because the function is only downloading images from the internet but I know that my laptop is slow 
and at this point I am not sure what else to do.

This is only the beginning of the question and it has considerable weight for this assignment. I cannot analyse my data 
using a t-SNE or Confusion matrices if I do not have any data to analyse! Nor can I comment on classification accuracy 
or explain methods used because my methods apparently don't work and I don't know why!

# Analysing system
- Design a multiclass loss function

  Can't do this yet.

- Analyse data using t-SNE and Confusion matrices

  Can't do this yet.

- Report on classification accuracy and explain methods used

  Can't do this yet.

Getting quite nervous now.

**-N**
