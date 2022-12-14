# Cotton_Plant_Disease_Detection

<hr>
Dataset Link : https://drive.google.com/drive/folders/1YrSTf1SeUpMPdrpr3zqGQ_7WsFbY0mxv?usp=sharing

<hr>
<h2>Introduction</h2>
Agriculture is essential to the growth of every country, Cotton and other major crops fall into the cash crops. Cotton is affected by most of the diseases that cause significant crop damage. Many diseases affect yield through the leaf. Detecting disease early saves crop from further damage.  Accurate disease identification is important for taking effective measures. Deep learning in the identification of plant disease plays an important role. The proposed model based on Deep Learning is used to identify several cotton leaf diseases accurately. We gathered cotton leaf images from the field for this study. The dataset contains 2385 images of healthy and diseased leaves. The size of the dataset was increased with the help of the data augmentation approach.The model is trained using CNN Architectture.The model gives  98% accuracy on training and validation data set in 500 epochs. 
<br>
<h4>Deep Learning Neural Network Architecture.</h4>
<img align="center" alt="ASD" width = 700 src="https://www.mdpi.com/computers/computers-11-00102/article_deploy/html/images/computers-11-00102-g001.png">
<br>
<h2>Materials & Methods</h2>
<img align="center" alt="ASD" width = 700 src="https://www.mdpi.com/computers/computers-11-00102/article_deploy/html/images/computers-11-00102-g004.png">
<br>
<h2>Model accuracy and loss</h2>
<img align="center" alt="ASD" width = 500 src="https://i0.wp.com/indianaiproduction.com/wp-content/uploads/2020/08/model-accuracy.png?w=386&ssl=1">
<img align="center" alt="ASD" width = 500 src="https://i0.wp.com/indianaiproduction.com/wp-content/uploads/2020/08/model-loss.png?w=376&ssl=1">
<br>
<h2>Tools & IDE</h2>
Google Colab is used for model training, and spyder used for model deployment on the local system.
<h3>Requirements</h3>
Flask<br>
Python<br>
TensorFlow<br>
Keras <br>
NumPy<br>
<h2>How to use App?</h2>
Run ‘aap.py’ file in spyder or you can run it using anaconda prompt. Then you will get localhost address like ‘http://127.0.0.1:5000/‘ enter it in any browser in your system.
<h2>Working of Model</h2>
<h4>Input Image</h4>
 <img align="center" alt="ASD" width = 900 src="https://user-images.githubusercontent.com/88526990/207537691-558902ac-342e-44ad-8713-aa270a6ad13c.png">
 <br>
 <h4>Output Image</h4>
 <img align="center" alt="ASD" width = 900 src="https://user-images.githubusercontent.com/88526990/207537928-fdb71cbf-5342-40cd-a91c-2efcd8371985.png">
