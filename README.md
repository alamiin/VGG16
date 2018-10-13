# VGG16
Image classification Using VGG16 pretrained model. 


In this model I used VGG16 pretrained model. My gole is classification of palmprint image data. I have used COEP dataset which is publicly available. I have used bottleneck feature. Finally our accuracy was 99.33%.


<h3>Architecture of VGG-16</h3>
<img src="https://user-images.githubusercontent.com/31893242/46908984-064de600-cf4d-11e8-83e5-1666e6e7c856.png" alt="Italian Trulli">


<a href="https://arxiv.org/abs/1409.1556">Paper</a>

<h3>DataSet</h3>
<p>
The database consists of 8 different images of single persons palm. The database consists of total 1344 images pertaining to 168 people.The images were captured using digital camera. the resolution of images is 1600X1200 pixels. <a href="http://www.coep.org.in/page_assets/250/database.zip">Dataset Download link</a> </p>
<h3>Prepossessing</h3>
<p>
The size of our image is 1600X1200 pixels that's why I cropped image to 1200X1200 then resize it. After resizing I have applied mask on the image and just take hand color other color is removed. </p>

<h3>Data Augmentation</h3>
<p>Our dataset is very small that's why i have applied data augmentation technique to increase our dataset.</p>

