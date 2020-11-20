# *Concepts and Components Involved*

### Support Vector Machine/Classifier

  * It is one of the Supervised Learning Methods, where the objective is to find the Vector (n-Dimensional, depending upon the feature types of Input), so the it has wider margin from closely-situated Input vectors. It can be used for both purposes,i.e as Classifier and Regressor too. For different mathematical functions, Support Vector Classifiers are also of different type, such as Linear,Polynomial,RBF,sigmoid,etc.
  
  ![SVM](https://user-images.githubusercontent.com/54277039/99832276-4a792f00-2b86-11eb-846e-3c5f0f3b4d85.JPG)
  
  * For understanding it, refer this documentation https://scikit-learn.org/stable/modules/svm.html#svm-classification

### Histogram of Oriented Gradients

  * One of the tools for Computer Vision and Image processing, which involves Normalization of Pixels for better accuracy, division of Image into portions called cells and then calculation of gradient magnitudes with gradient directions using Block segmentation with concatenation at final stage. With faster computational speed and lesser bulky, it is suitable for detection purposes.

![HOG](https://user-images.githubusercontent.com/54277039/99832368-6d0b4800-2b86-11eb-8187-afe1c6d52a89.png)

  * For understanding it, refer this documentation https://www.learnopencv.com/histogram-of-oriented-gradients/

### Sliding Window Mechanism

  * One of the prominent methods used for Image segmentation, which involves extraction of image segment Matrix, varying step size according to dimension of image,etc. Although time consuming, but an optimised time-growing step size can be implemented too for smooth and faster image segmentation.
  
  ![Sliding](https://user-images.githubusercontent.com/54277039/99832419-83190880-2b86-11eb-8f0f-d35acee08ea7.JPG)
  
  * For understanding it, refer this documentation https://www.pyimagesearch.com/2015/03/23/sliding-windows-for-object-detection-with-python-and-opencv/

### Principal Component Analysis

  * A well known Concept in the field of dimensionality and dataset manipulation, where the purpose is to find n-dimensional Vector Space so that Input points lying around it has minimum Orthognal Distances. Although confused with regression method, it invloves high level of linear algebra alongside Matrix manipulation. It is used as Feature tuner for balancing bias-variance trade-off and maintaining Generalization for Machine Learning models.
  
  ![PCA](https://user-images.githubusercontent.com/54277039/99832489-9c21b980-2b86-11eb-86c5-17ebf49362eb.JPG)
  
  * For understanding it, refer this documentation https://scikit-learn.org/stable/modules/generated/sklearn.decomposition.PCA.html

### Radial Basis Function

  * Inspired from one of the well-known Mathematical Distributions, Radial Basis Function involves parameters like mean,variance and Euclidean Vector Distance (Norm of Vectors).It is used most of the time, because of its probabilistic and normalized approach for less errors and better accuracy.
  
  ![RBF](https://user-images.githubusercontent.com/54277039/99832512-a774e500-2b86-11eb-9756-6c05c5e2c82f.JPG)
  
  * For understanding it through an example, refer this documentation https://towardsdatascience.com/most-effective-way-to-implement-radial-basis-function-neural-network-for-classification-problem-33c467803319

### Non-Maximum Suppression

  * One of the Handy tools, used in Computer Vision and Image Processing. It helps to eliminate least probable detected areas and increase accuracy for Region of Interest to be highlighted. It involves calculating ratio of Intersection area and union area between multiple detected segments and tuning Confidence level accordingly.
  
  ![NMS](https://user-images.githubusercontent.com/54277039/99832550-b5c30100-2b86-11eb-9515-1b59a459013d.JPG)
  
  * For understanding it, refer this documentation https://www.pyimagesearch.com/2015/02/16/faster-non-maximum-suppression-python/
