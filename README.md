# Vehicle_Detection_and_Tracking_P5
Detects and tracks other vehicles.

By far the most complex project to date. A large data set of car images and non car images are used to train a neural net. HOGs are created of both sets in multiple color schemes. A classifier is built and trained using the HOG data. Individual images are divided into "windows" that are run thru the classifier to identify them as either car or "not car". The windows identified as cars are then subject to a "heat map" that helps flush out single erroneous windows. At the end of the code a video is processed to identify cars near the drivers car.
