# Face-landmarks-detection-benchmark
Face landmarks(fiducial points) detection evaluation.

Attention! It's comparision of specific implementations, not algorithms by itself, so if you know how to improve results let me know.


Name| Rot. | Exp. | Lang | Doc.
------------------ | --- | --- | --- | ---
[Stasm](http://www.milbo.users.sonic.net/stasm/)|no|no|C|yes
[CLM-framework](https://github.com/TadasBaltrusaitis/CLM-framework)|?|?|?|?
[Dlib](http://dlib.net/)|?|?|?|?


Metric: 
~~~
"The average point-to-point Euclidean error normalized by the inter-ocular distance (measured as the Euclidean distance between the outer corners of the eyes)"
http://ibug.doc.ic.ac.uk/media/uploads/competitions/compute_error.m

"RMSE is very common and is a suitable general-purpose error metric. Compared to the Mean Absolute Error, RMSE punishes large errors"
https://www.kaggle.com/c/facial-keypoints-detection/details/evaluation
~~~

To look at:
~~~
Kaggle Facial Keypoints Detection
https://github.com/mrgloom/Kaggle-Facial-Keypoints-Detection-Solutions

To try first list:
https://github.com/soundsilence/FaceAlignment

https://github.com/delphifirst/FaceX
https://github.com/ci2cv/face-analysis-sdk
https://github.com/uricamic/flandmark
http://cmp.felk.cvut.cz/~uricamic/flandmark/
http://cmp.felk.cvut.cz/~uricamic/clandmark/
https://github.com/uricamic/clandmark
https://github.com/dnouri/kfkd-tutorial
https://github.com/FaceDetect/jointCascade_py
https://github.com/zhusz/CVPR15-CFSS
http://mmlab.ie.cuhk.edu.hk/archive/CNN_FacePoint.htm
http://mmlab.ie.cuhk.edu.hk/projects/TCDCN.html
http://ibug.doc.ic.ac.uk/resources/fiducial-facial-point-detector-20052007/
http://ibug.doc.ic.ac.uk/resources/facial-point-detector-2010/
http://www.humansensing.cs.cmu.edu/intraface/
https://github.com/kylemcdonald/FaceTracker
http://www.cl.cam.ac.uk/research/rainbow/projects/clmz/
Coarse-to-Fine Auto-Encoder Networks (CFAN) for Real-Time Face Alignment
http://vipl.ict.ac.cn/resources/codes
http://ibug.doc.ic.ac.uk/resources/drmf-matlab-code-cvpr-2013/


ASM/AAM
http://www.milbo.users.sonic.net/stasm/
https://github.com/cxcxcxcx/asmlib-opencv

constrained local models
https://github.com/TadasBaltrusaitis/CLM-framework

"One Millisecond Face Alignment with an Ensemble of Regression Trees"
http://blog.dlib.net/2014/08/real-time-face-pose-estimation.html
http://www.csc.kth.se/~vahidk/face_ert.html

http://www.ics.uci.edu/~xzhu/face/
https://github.com/TadasBaltrusaitis/CLM-framework


https://github.com/yulequan/face-alignment-in-3000fps
https://github.com/jwyang/face-alignment

https://github.com/patrikhuber/superviseddescent

Deep learning:
?

FANN:
https://github.com/olddocks/facialkeypoints

Javascript:
https://github.com/auduno/clmtrackr

Too simple algorithm, not worth considering it:
https://github.com/sdcoca/facex
~~~

Other(blog posts, SO, etc.):
~~~
http://www.researchgate.net/post/Which_facial_landmark_detection_tracking_software_is_publically_available_for_research
~~~


Facial points datasets:

Name| N images| N points |N individuals | Lighting | Age | Race| $ | Auth.
------------------ | --- | --- | --- | --- | --- | --- | --- | ---
[MUCT](http://www.milbo.org/muct/)|3755|76|624|yes|yes|yes|no|no

~~~
http://www.milbo.org/muct/other-databases.html
[LFPW](http://neerajkumar.org/databases/lfpw/)|1432|29|
[HELEN](http://www.ifp.illinois.edu/~vuongle2/helen/)|2330|192
[AFW]()|?|?
[AFLW](https://lrs.icg.tugraz.at/research/aflw/)|?|?
[IBUG]()|?|68
[PUT]()|?|?
[XM2VTS](http://www.ee.surrey.ac.uk/CVSSP/xm2vtsdb/)|?|?
[ATVS](http://atvs.ii.uam.es/scfacedb_landmarks.html)|?|?|yes
~~~

Papers:
~~~
"A comparative study of face landmarking techniques"
http://www.busim.ee.boun.edu.tr/~sankur/SankurFolder/Jour_JIVP_Landmarking.pdf
"Supervised Descent Method and its Applications to Face Alignment"
http://www.ri.cmu.edu/pub_files/2013/5/main.pdf
~~~

Other cool benchmarks:
~~~
https://github.com/soumith/convnet-benchmarks
https://github.com/erikbern/ann-benchmarks
https://github.com/andrewssobral/bgslibrary
~~~
