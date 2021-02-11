## Day 4 Actions Items.

### It's day 4 already!!
### My action items for today are kinda fun as I like to think about how ML can tackle real-world problems rather than optimizing the MNIST dataset.
## Real-Time Face Mask detection during COVID
### Covid-19 is now everywhere and most health institutions including WHO recommends wearing face masks for protection weather in crowded areas, closed areas, walking in the street or dealing with patients as covid transfers even by talking with a positive person. 
### The thing is that people hate wearing masks for long periods and sometimes take it off, other people may not even wear it which is very dangerous!
### One of the approaches that many businesses and places made in order to continue a semi-normal life is mask restriction like malls, restaurants and companies.
### So the problem is how will we know who's wearing a mask and who isn't efficiently and without having to hire someone to do so? obviously AI would do the job for us when it comes to automating stuff.

## The dataset
### Luckily there's an available dataset on Kaggle [here](https://www.kaggle.com/andrewmvd/face-mask-detection), it contains 853 images along with their annotations indicating 3 classes person is _wearing a mask correctly_, _incorrectly_ or _not wearing it_.
![here's a peak into the data](https://github.com/nouranali/SureStart_VAILTraining/blob/master/Day4/Screenshot%20from%202021-02-11%2019-54-38.png)
### This dataset is also suitable as it has images from streets, tv, schools, crowded areas and many places so it's a good one for generalization.

## The Algorithm.

### I think I'd use YOLOv5 (You Only Look Once) it's the most popular object detection convolutional neural network. 
### I chose YOLO as it's fairly easy to use in Tensorflow and I wouldn't create my own architecture to predict both a class and a bounding box around the face mask. It's also easy to understand and produces good results for real time object detection.
