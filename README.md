# Evolution-of-Modern-Deep-Learning-Methods-of-Object-Detection
A computer vision technique called object detection is used to find occurrences of objects in pictures
or movies. Object detection algorithms commonly employ machine learning or deep learning to get
relevant results. When watching photographs or movies, humans are able to quickly recognise
and pin down objects of interest. Object detection attempts to mimic this intelligence through the use
of computers.
An object detection model can identify the presence of a predetermined set of objects in an image or
video stream as well as where in the image those objects are located. This is more complex than categorization,
which can just specify what an image’s ”main subject” is.Multiple objects in an image may be recognised, classified, 
and localised using object detection. For each object it finds, an object detection model predicts bounding boxes and 
categorization probabilities.
Numerous bounding boxes are commonly predicted by object detection. Each box also receives a
confidence value that shows how likely it is that the object is indeed there, according to the model. We
eliminate the boxes whose score is lower than a predetermined threshold during the post-processing
stage (also called non-maximum suppression).
Object detection is a key component of advanced driver assistance systems (ADAS), which provide
cars the ability to recognise pedestrians or traffic lanes to improve road safety. Object detection is
useful in applications like video surveillance and picture retrieval systems. The goal of object
detection is to locate instances of a current set of object classes (such as ”people, cars, bikes, and
animals”) and to use a bounding box to map out where each object was located inside the image.
Every object class includes distinguishing qualities that make it easier to classify the objects; for
example, all circles are spherical. Detecting the object class is done using these distinctive properties. 
When searching for circles, one can look for objects that are a specific distance from the centreor a point. 
Finding objects with equal side lengths and perpendicular corners is required, much like
looking for squares. Similar techniques are used to recognise faces using characteristics including skin tone, 
the space between the eyes, the eyes, the nose, and the lips.
The two main types of object detection methods are non-neural approaches and neural network-based
methods. It becomes necessary for non-neural approaches to first define features using one of the
methods below, and then carry out the classification using a technique like support vector machine
(SVM). Contrarily, neural techniques, which frequently utilise convolutional neural networks (CNN),
are able to do end-to-end object detection without formally defining characteristics.
On the basis of stages that object detection model takes to identify the object, they are classified into
two categories:
• ONE STAGE OBJECT DETECTION
• TWO STAGE OBJECT DETECTION

# One Stage Object Detection
One-stage object detection Models are a class of one-stage object detection algorithms that
detect objects over a wide range of locations without going through the region proposal stage
that two-stage models do. Modern one-stage detectors typically use a simple fully convolutional design,
and the network outputs classification probabilities and box offsets at each
spatial position (w.r.t. a pre-defined anchor box). Usually, these models can draw conclusions
more quickly (possibly at the cost of performance).
The various examples of one stage are:
1. YOLO
2. Retinanet
3. Single Shot Detector
   ![image](https://github.com/arshadanam07/Evolution-of-Modern-Deep-Learning-Methods-of-Object-Detection/assets/92083279/128d3710-99b7-46b6-af1d-e548252eca0d)
   ![image](https://github.com/arshadanam07/Evolution-of-Modern-Deep-Learning-Methods-of-Object-Detection/assets/92083279/6a1bf9e2-5def-4dcd-9790-f11594e04fb0)

# Two Stage Object Detection
Two stages are used in object detection in two stages; the first stage involves making
suggestions for regions of interest, and the second stage involves performing detection
from the suggested regions of interest[3]. Two-stage detectors first eliminate from the
overall image any regions that are very likely to contain an object with the aid of a region
proposal network. After receiving the proposals, the convolutional network determines
the classification score and spatial offsets[3].
One-stage detectors are more accurate than two-stage detectors by a significant margin[3].
The various examples of two stage detectors are:
1. FASTER RCNN
2. MASK RCNN
3. CASCADED RCNN
   ![image](https://github.com/arshadanam07/Evolution-of-Modern-Deep-Learning-Methods-of-Object-Detection/assets/92083279/2a40ed38-f4d7-41e4-9055-e1c6c4138539)
   ![image](https://github.com/arshadanam07/Evolution-of-Modern-Deep-Learning-Methods-of-Object-Detection/assets/92083279/0ac1d26d-d1c1-4999-a463-c9974a1de697)




