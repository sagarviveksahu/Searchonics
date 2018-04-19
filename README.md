# Searchonics
 Interactive Image Search Engine
 
# Inspiration
Searchonics is a fast and interactive Image Search Engine, a step ahead of traditional text based search which returns a set of relevant images which are queried. To strectch our creative muscle in Machine Learning and Computer Vision, we were inspired by the idea of visual inspiration ignition engine.

# What it does
Searchonics uses concepts of Machine Learning, Deep learning, Computer Vision and Cloud Computing to search an array of closely related images which belong to every domain based on how closely it matches with the features of pretrained image dataset using keras with Tensorflow. It also searches the unique images discarding the repetitive data, the concept of Image Hashing is implemented. Lastly, an image can be snipped/cropped to obtain area of interest and queried to get the results.

# How we built it
We used Keras with Tensorflow for feature extraction to evaluate weights of an image dataset. OpenCV2 is used along with Python Image Library. For the front end HTML5, AJAX and JavaScript is used. We Stored data on S3, and used EC2 instance to host our website using AWS lambda as API functions.

# Challenges we ran into
This application deals with pixel feature mapsLearning to work with pixel data and calculating the feature maps and other property for images to find the metrics of finding similarity. EC2 hardware configuration. Finding the way to crop the region of interest on the image hosted on a webpage.

# Accomplishments that we're proud of
To think, implement and test the idea which could be used by a user to get the details of the surrounding or the object they don't know but would want to look up where text searching wouldn't be much helpful. Image search enginecan be extensively used with a myriad of use-cases using the concept of algorithms, computer vision, machine learning and human-computer interaction.

# What we learned
We learnt image hashing, pixel feature mapping, development of histogram evaluation mapping, extensive use of AWS api's. Interesting algorithm to find the scores between two images to signify the relevance.

# What's next for Searchonics
Bookmarking the retrieved images, getting the tags and connecting the query result with e-commerce platform for instant access even if the person is not aware what the object is. Using AI to make it much more interactive to generate and a grid of semantically related images.

# Built With
python-3.x
opencv
tensorflow
amazon-web-services (EC2 , S3, AWS Lambda function)
keras
machine-learning
html5
javascript
