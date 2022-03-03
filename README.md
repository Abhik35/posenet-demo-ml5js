# posenet-demo-ml5js
A posenet demo built using ml5.js
What is PoseNet?
Posenet is a real-time pose detection technique with which you can detect human beings’ poses in Image or Video. It works in both cases as single-mode(single human pose detection) and multi-pose detection(Multiple humans pose detection). In simple words, Posenet is a deep learning TensorFlow model that allows you o estimate human pose by detecting body parts such as elbows, hips, wrists, knees, ankles, and form a skeleton structure of your pose by joining these points.




How does PoseNet work?
PoseNet is trained in MobileNet Architecture. MobileNet is a Convolutional neural network developed by google which is trained on the ImageNet dataset, majorly used for Image classification in categories and target estimation. It is a lightweight model which uses depthwise separable convolution to deepen the network and reduce parameters, computation cost, and increased accuracy. There are tons of articles related to MobileNet that you can find on google.

The pre-trained models run in our browsers, that is what differentiates posenet from other API-dependent libraries. Hence, anyone with a limited configuration in a laptop/desktop can easily make use of such models and built good projects.

Posenet gives us a total of 17 key points which we can use, right from our eye to and ears to knees and ankles
