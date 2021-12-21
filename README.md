## Human-Face-Classification with machine-learning
---------------
### What I did in this project
I made a code for face image classification using Python.

### Prerequisite
You need to download Anaconda(at this https://docs.anaconda.com/anaconda/user-guide/getting-started/)and sklearn package.

### Training dataset
Dataset I used is from Olivetti faces from AT&T. 
There are ten different images of each of 40 distinct subjects.
For some subjects, the images were taken at different times, varying the lighting, facial expressions such as open or closed eyes, smiling or not smiling, and facial details such as wearing glasses or not. All the images were taken against a dark homogeneous background with the subjects in an upright, frontal position with tolerance for some side movement.

### Algorithm
I choosed logistic regression for classifier and changed hyper-parameters such as max_iter, solver, C, and tol.
I set solver = 'liblinear' because dataset was small. And I set C = 50 to avoid algorithm is regularized too much.

### How to use
You can run this code on Jupyter Notebook.

### Test
The accuracy of this algorithm was 97%.
