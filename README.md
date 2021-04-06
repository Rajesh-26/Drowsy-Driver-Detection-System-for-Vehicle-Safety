# Drowsy-Driver-Detection-System-for-Vehicle-Safety

Safety comes first when we think about travelling or driving. Mistakes of the
driver can lead to severe injuries and deaths. Recently market has introduced
there many systems like navigation systems, back mirror, various sensors etc. to
reduce the burden of the driver. One of the most common mistake is that human
errors which increases the probability of road accidents. The main reason
occurring from the highway accidents are the drowsiness and sluggishness of
driver while driving. It is important to come with an optimistic algorithm to
detect drowsiness as soon as driver feels sleepy. This could ameliorate the
negative effects of human errors.

METHODOLOGY
1) Face recognition:
Recognition of the face is accomplished by Viola Jones. The principle objective
of face recognition is to decrease the identification of false facial expressions.
The significance of this part is to precisely find the location of the eyes and the
mouth.
2) Skin segmentation:
After the detection of the face, the segmentation of the skin is carried out by
changing the image to YCbCr domain. The greatest advantage of this type of
conversion is that, the impact of luminosity can be reduced by considering just
the chromatic components.
3) Segmentation by K means:
K means segmentation of the objects into K no. of mutually exclusive clusters,
so that objects in each cluster are nearest to each other, and farthest from objects
in other clusters.
4) Recognition of Yawning:
Viola Jones is used to find the area of the mouth, the detected region will be
segmented by using K means clustering and followed with tracking that uses
correlation coefficient template matching.

ALGORITHMS AND FUNCTIONS
1) Viola Jones algorithm
The algorithm has four stages:
1. Haar Feature Selection
2. Creating an Integral Image
3. Adaboost Training
4. Cascading Classifiers
a. Haar Feature selection
b. Creating an Integral Image
2) Edge detection (Sobel edge operator)
