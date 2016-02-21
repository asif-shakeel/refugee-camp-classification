# refugee-camp-classification

This is a humanitarian project to help identify refugee camps in
various terrains from high resolution satellite images. The images used are not provided as a repository, but other images can be substiuted.  It uses scikit-learn package to extract edges and
then uses Histogram of Oriented Gradients (HOG) descriptors with Support Vector Machines (SVM) to
idenify the images. It also contains the Random Forests classification as a comparison 
to SVM. It achieves good accuracy on structured camps that are known from UNHCR desgnations.  It is relatively fast. In the future it is to be expanded to 
be able to include more features such as color bands. Ultimate goal is to identify refugee camps that are not previously known.
It is only a demonstration, and not meant for
deployment.
