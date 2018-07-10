#### Udacity Artificial Intelligence Nanodegree
### Term 2: Project 6
# Recurrent Neural Networks: Time Series Prediction and Text Generation

##### &nbsp;

<img src="images/timeseries_windowing_training.gif" width="100%" align="top" alt=""  title="Time Series Prediction" />

##### &nbsp;

# Overview
There are two parts to this project. First, we use an RNN to predict Apple's stock price based on time series data. Second, we use an RNN to generate text sequences based excerpts from the book Sherlock Holmes.

The final notebook with all steps and source code can be found here: [.ipynb version](https://github.com/tommytracey/aind2-rnn/blob/master/RNN_project.ipynb), [.html version](https://rawgit.com/tommytracey/aind2-rnn/master/RNN_project.html).

##### &nbsp;

# Project Scope

#### Files Submitted

| Criteria       		|     Meets Specifications	        			            |
|:---------------------:|:---------------------------------------------------------:|
| Submission Files      |  RNN_project.ipynb, my_answers.py --> both the completed notebook  RNN_project.ipynb as well as all completed python functions requested in the main notebook RNN_project.ipynb (TODO items) should be copied into this python script and submitted for grading.		|

#### Step 1:  Implement a function to window time series
| Criteria       		|     Meets Specifications	        			            |
|:---------------------:|:---------------------------------------------------------:|
| Window time series data. |  The submission returns the proper windowed version of input time series of proper dimension listed in the notebook.  |


#### Step 2: Create a simple RNN model using keras to perform regression

| Criteria       		|     Meets Specifications	        			            |
|:---------------------:|:---------------------------------------------------------:|
| Build an RNN model to perform regression. |  The submission constructs an RNN model in keras with LSTM module of dimension defined in the notebook.        |


#### Step 3: Clean up a large text corpus

| Criteria       		|     Meets Specifications	        			            |
|:---------------------:|:---------------------------------------------------------:|
| Find and remove all non-english or punctuation characters from input text data.  The submission removes all non-english / non-punctuation characters.  |


#### Step 4: Implement a function to window a large text corpus

| Criteria       		|     Meets Specifications	        			            |
|:---------------------:|:---------------------------------------------------------:|
| Implement a function to window input text data| The submission returns the proper windowed version of input text of proper dimension listed in the notebook.  |


#### Step 5: Create a simple RNN model using keras to perform multiclass classification

| Criteria       		|     Meets Specifications	        			            |
|:---------------------:|:---------------------------------------------------------:|
| Build an RNN model to perform multiclass classification. |  The submission constructs an RNN model in keras with LSTM module of dimension defined in the notebook.        |


#### Step 6: Generate text using a fully trained RNN model and a variety of input sequences
| Criteria       		|     Meets Specifications	        			            |
|:---------------------:|:---------------------------------------------------------:|
| Generate text using a trained RNN classifier.   | The submission presents examples of generated text from a trained RNN module.  The majority of this generated text should consist of real english words. |

##### &nbsp;

## Submission
Before submitting your solution to a reviewer, you are required to submit your project to Udacity's Project Assistant, which will provide some initial feedback.  

The setup is simple.  If you have not installed the client tool already, then you may do so with the command `pip install udacity-pa`.  

To submit your code to the project assistant, run `udacity submit` from within the top-level directory of this project.  You will be prompted for a username and password.  If you login using google or facebook, visit [this link](https://project-assistant.udacity.com/auth_tokens/jwt_login) for alternate login instructions.

This process will create a zipfile in your top-level directory named rnn-<id>.zip.  This is the file that you should submit to the Udacity reviews system.

##### &nbsp;
---

## Project Setup


### Amazon Web Services

Instead of training your model on a local CPU (or GPU), you could use Amazon Web Services to launch an EC2 GPU instance.  Please refer to the Udacity instructions in your classroom for setting up a GPU instance for this project.  [link for AIND students](https://classroom.udacity.com/nanodegrees/nd889/parts/16cf5df5-73f0-4afa-93a9-de5974257236/modules/53b2a19e-4e29-4ae7-aaf2-33d195dbdeba/lessons/2df3b94c-4f09-476a-8397-e8841b147f84/project)
