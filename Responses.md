# Welcome to My SureStart VAIL Training responses section!

In this file, I'll be sharing my reflections, experience, and notes during the training

***

## *  8/2/2021: Day 1
I had such a good time getting to know everyone as a first impression, Taniya is such a kind person and actually, everyone is very nice and helpful. I'm excited to be a part of the training program yet a bit nervous about how will I arrange my schedule as it's during my final exams.
I am sure that the program will boost my skills as was demonstrated in the kick-off presentation but the thing I'm excited most about is working with people from different time zones and countries.

***

## * 9/2/2021: Day 2
* We had our first standup meeting today's noon, where we got to know each other better me and my team and our mentor, we talked about ourselves and what we study.
### Day 2 Action Items: 
1. The difference between supervised and unsupervised learning: 
in supervised learning, the model is trained on examples that are labeled (both the question and the answer) in a pair of (x,y), so the model learns a function f(x)=y and we feed the model both, algorithms: Classification, regression
in unsupervised learning, the model is only given examples x without their associated labels y and it learns to find the mapping or the pattern between the examples which give y, approaches: clustering, PCA.
2. Why it's False that "Scikit-Learn has the power to visualize data without a Graphviz, Pandas, or other data analysis libraries": because scikitlearn is a library for only Machine learning and not plotting data and it's built on top of other python libraries such as NumPy, pandas, and matplotlib so it needs those dependencies to create visualization and can't do this on its own.

***
## 10/2/2021: Day 3
### Day 3 Action Items
1. What are Tensors? A tensor is a generalization of a matrix, a 1D tensor is a vector, a 2 or 3D tensor is a matrix, 0D tensor (a single number) or even higher dimensional structures are tensors, a tensor's dimension is called "rank". A tensor has a dynamical property that makes it special or distinguished from mere matrices, that is if you apply a transformation to entities in the structure in a regular way then the tensor must obey a related transformation rule. a keynote here is any rank-2 tensor can be represented as a matrix, but not every matrix is a rank-2 tensor.
In ML tensors are used to represent data accurately and easily because data can have very high dimensions and tensors make a convenient representation of data.

2. TensorFlow interactive session allocates resources and holds the actual values of intermediate results and variables and in order to run the actual calculations we need to create a session for the graph, then run that session where the variable's value is calculated and allocated. a variable's value is only valid during a certain session. We can also write our code so that the session closes automatically or we close it manually. TensorFlow sessions are now deprecated in versions>2.0

***
## 11/2/2021: Day 4
you can find the action items [here](https://github.com/nouranali/SureStart_VAILTraining/blob/master/Day4/ActionItems.md)

***
## 12/2/2021: Day 5
you can find the action items [here](https://github.com/nouranali/SureStart_VAILTraining/blob/master/Day5/sarcasm-detection.ipynb)
***
## 15/2/2021: Day 8
So today I've worked on the MNIST handwritten digits recognition dataset, I applied a simple CNN architecture and submitted the solution on Kaggle, I had much fun. Also we today had our standup meeting and discussed the difficulties that faced us in the previous action items.

***
## 16/2/2021: Day 9
1. In the design of the game the common concepts of ML were utilized in a simple way. 
Collecting data: this concept was utilized in my selection of accepting/rejecting candidates based on their resumes
Training the model: building the automated hiring algorithm based on historical data that I collected
Model deployment: putting the model into production to do my previous task "recruiting people"
Observing the model: when I was observing the model while recruiting/rejecting people and getting insights and feedback
model canceling: when I stopped the model from working as it was biased and this included human interaction.

2. I think that Facebook algorithms are biased especially the ones regarding hate speech comments and posts, they let so many hateful comments and posts towards non-majority religions and races pass while they filter other words that are totally fine and mark them as "hate speech".
This model would be fair if they collect human feedback about the words without just automating the feedback and report operation, use crowdsourcing to validate the data, and not rely only on another ML model.
I chose this model as I encountered this problem many times and it just hit my mind right now.

3. When Constructing AI projects I avoid biases by making sure that the dataset correctly resembles the real world, if it's not I'd resample it in any way.
I also rely on domain experts knowledge to make sure that the data isn't biased.
***
## 17/2/2021: Day 10
1. The main difference between a CNN and a Fully connected NN is that CNNs enable deep learning for computer vision tasks like: image classification, object detection and so on. while Fully connected NN is a neural nework where all nerons in one layer are connected to all the neurons in the folllowing layer.
2. The layers of a CNN vary: 
  2.1 Convolution layer/ filter : this layer acts as a feature extractor that scans the image pixels to create a feature map.
  2.2 pooling layer / downsampling layer: this layer reduces the amount of info. obtained in feature maps but also maintains the most important features most popular is average pooling and max pooling.
  2.3 input flatteining layer: this layer flattens the output of the previous layers into one vector.
  2.4 first fully connected layer: predict correct label by applying weigths on the feature maps
  2.5 output fully connected layer: predict probability of each layer.
3. layers of the Fully connected neural network: consists of dense layers of neurons
4. for both architectures sometimes a dropout layer is added to avoid overfitting.
5. Some applications of CNN: mainly computer vision tasks
  5.1 : Image classification
  5.2 : Image segmentation
  5.3 : object detection and localization
  5.4 : image construction
6. applications of Fully connected neural networks: it's a generic architecture that doesn't sepcialize in a certain domain like nlp or computer vision and can be used but it has downsides when used in computer vision as they don't give good results and are computationally expensive, prone to overfitting
