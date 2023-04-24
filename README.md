# A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms

## Tools Used:

* Python Programming Language
* Google's COLAB

## Libraries Used: 
* Numpy
* Matplotlib
* Pillow
* openCV

## Objective: 
The primary objectives or targets for any social media, banking applications, websites, or other similar products are security and privacy. Images are transmitted over public networks or channels, just like text data is. This presents potential security risks and opportunities for data visibility to unauthorised individuals with potentially destructive intent—assailants/hackers. Here, encryption becomes crucial. Encryption's primary goal is to ensure that it is only accessible to those who are authorised to access it.  

Here we have tried to study the most used Image Encryption approaches. First we study and implement the RSA (Rivest Shamir Adelman) algorithm. The RSA Algorithm has largely been in use to encrypt textual data. But it is not only restricted to it. Nowadays, Image encryption is also done using the RSA algorithm. Then we study and implement the performance of Chaos based approaches with the help of Arnold’s Cat Map, Henon’s Chaotic Map and Logistic Maps. We compare the security using plots like Histogram and Adjacent Pixel Correlation. The ultimate aim is to have a deep insight into the encryption algorithm and present a report in a simple and easy to understand way and to visualise the security extent using the above mentioned plots.

## Validation Metrics
* Histograms
* Adjacent Pixel Autocorrelation
* Correlation Coefficient

## Results 
The results generated after encryption using <b>RSA algorithm</b> on the image '1.png' are attached below:  

Original Image            |  Encrypted Image          |  Decrypted Image
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/RSA%20ALGORITHM%20AND%20IMAGES/1.png)  |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/RSA%20ALGORITHM%20AND%20IMAGES/Encrypted_1.png) |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/RSA%20ALGORITHM%20AND%20IMAGES/Decrypted_1.png)

 
The results generated after encryption using <b>Arnold's Cat Map algorithm</b> on the image '1.png' are attached below:  

Original Image            |  Encrypted Image          |  Decrypted Image
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/ACM%20ALGORITHM%20AND%20IMAGES/1.png)  |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/ACM%20ALGORITHM%20AND%20IMAGES/Encrypted_1.png) |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/ACM%20ALGORITHM%20AND%20IMAGES/Decrypted_1.png)

 
The results generated after encryption using <b>Henon's Chaotic Map algorithm</b> on the image '1.png' are attached below:  

Original Image            |  Encrypted Image          |  Decrypted Image
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/HCM%20ALGORITHM%20AND%20IMAGES/1.png)  |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/HCM%20ALGORITHM%20AND%20IMAGES/Encrypted_1.png) |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/HCM%20ALGORITHM%20AND%20IMAGES/Decrypted_1.png)

  
The results generated after encryption using <b>Logistic Chaos Map algorithm</b> on the image '1.png' are attached below:  

Original Image            |  Encrypted Image          |  Decrypted Image
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/LCM%20ALGORITHM%20AND%20IMAGES/1.png)  |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/LCM%20ALGORITHM%20AND%20IMAGES/Encrypted_1.png) |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/LCM%20ALGORITHM%20AND%20IMAGES/Decrypted_1.png)


## Analysis
We analysed the results using Histograms, Adjacent Pixel Autocorrelation and then finally calculated the correlation coefficient between Original and Encrypted image and Original and Decrypted image.

#### 1. Histogram Analysis
For a good image encryption algorithm, the histogram of an encrypted image should be evenly distributed. Moreover, the histogram of original and encrypted image should not be identical. 

For <b>RSA Algorithm</b> the histograms are shown below: 
Original Image            |  Encrypted Image          |  Decrypted Image
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/RSA%20ALGORITHM%20AND%20IMAGES/Histogram_RSA_Original.png)  |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/RSA%20ALGORITHM%20AND%20IMAGES/Histogram_RSA_Encrypted.png) |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/RSA%20ALGORITHM%20AND%20IMAGES/Histogram_RSA_Decrypted.png)

For <b>Arnold's Cat Map Algorithm</b> the histograms are shown below: 
Original Image            |  Encrypted Image          |  Decrypted Image
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/ACM%20ALGORITHM%20AND%20IMAGES/Histogram_ACM_Original.png)  |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/ACM%20ALGORITHM%20AND%20IMAGES/Histogram_ACM_Encrypted.png) |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/ACM%20ALGORITHM%20AND%20IMAGES/Histogram_ACM_Decrypted.png)

For <b>Henon's Chaotic Map Algorithm</b> the histograms are shown below: 
Original Image            |  Encrypted Image          |  Decrypted Image
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/HCM%20ALGORITHM%20AND%20IMAGES/Histogram_HCM_Original.png)  |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/HCM%20ALGORITHM%20AND%20IMAGES/Histogram_HCM_Encrypted.png) |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/HCM%20ALGORITHM%20AND%20IMAGES/Histogram_HCM_Decrypted.png)

For <b>Logistic Chaos Map Algorithm</b> the histograms are shown below: 
Original Image            |  Encrypted Image          |  Decrypted Image
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/LCM%20ALGORITHM%20AND%20IMAGES/Histogram_LCM_Original.png)  |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/LCM%20ALGORITHM%20AND%20IMAGES/Histogram_LCM_Encrypted.png) |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/LCM%20ALGORITHM%20AND%20IMAGES/Histogram_LCM_Decrypted.png)

#### 2. Adjacent Pixel Autocorrelation
For a good image encryption algorithm, the scatter plot of Adjacent Pixel Autocorrelation of the encrypted image should be well scattered. In original image the scattering is along the diagonal. 

For <b>RSA Algorithm</b> the scatter plots of Adjacent Pixel Autocorrelation are shown below: 
Original Image            |  Encrypted Image          |  Decrypted Image
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/RSA%20ALGORITHM%20AND%20IMAGES/APA_RSA_O.png)  |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/RSA%20ALGORITHM%20AND%20IMAGES/APA_RSA_E.png) |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/RSA%20ALGORITHM%20AND%20IMAGES/APA_RSA_D.png)

For <b>Arnold's Cat Map Algorithm</b> the scatter plots of Adjacent Pixel Autocorrelation are shown below: 
Original Image            |  Encrypted Image          |  Decrypted Image
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/ACM%20ALGORITHM%20AND%20IMAGES/APA_ACM_O.png)  |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/ACM%20ALGORITHM%20AND%20IMAGES/APA_ACM_E.png) |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/ACM%20ALGORITHM%20AND%20IMAGES/APA_ACM_D.png)

For <b>Henon's Chaotic Map Algorithm</b> the scatter plots of Adjacent Pixel Autocorrelation are shown below: 
Original Image            |  Encrypted Image          |  Decrypted Image
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/HCM%20ALGORITHM%20AND%20IMAGES/APA_HCM_O.png)  |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/HCM%20ALGORITHM%20AND%20IMAGES/APA_HCM_E.png) |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/HCM%20ALGORITHM%20AND%20IMAGES/APA_HCM_D.png)

For <b>Logistic Chaos Map Algorithm</b> the scatter plots of Adjacent Pixel Autocorrelation are shown below: 
Original Image            |  Encrypted Image          |  Decrypted Image
:-------------------------:|:-------------------------:|:-------------------------:
![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/LCM%20ALGORITHM%20AND%20IMAGES/APA_LCM_O.png)  |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/LCM%20ALGORITHM%20AND%20IMAGES/APA_LCM_E.png) |  ![](https://github.com/GauravGupta7/A-Comprehensive-Study-of-Standard-Image-Encryption-Algorithms/blob/main/LCM%20ALGORITHM%20AND%20IMAGES/APA_LCM_D.png)

#### 3. Correlation Coefficient:
For a good encryption algorithm, the correlation coefficient between the original and encrypted image should be as low as possible and the correlation coefficient between the original and decrypted image should be as high as possible. It is a ratio and generally lies between -1 and 1. The table below shows the average correlation coefficient for 3 different images for all four of the algorithms:

   Algorithm        |    Original-Encrypted     |    Original Decrypted
:-------------     |    :-----------------:    |    :-----------------:
RSA Algorithm        |    0.03180686           |    0.8110046767
Arnold's Cat Map       |    0.08017079           |    1.0
Henon's Chaotic Map        |    0.00423634           |    1.0
Logistic Chaos Map        |    0.00135732           |    0.8110050


## Conclusions
From the result analysis, we can make the following conclusions: 
* The RSA Encryption scheme which performs exceptionally well for textual data encryption, suffers when implemented on images. 
* The Arnold’s Cat Map is a good encryption algorithm for images. It has a small correlation coefficient value for original vs encrypted image and proper unity value for original vs decrypted image. 
* The Henon’s Chaotic Map is still better than that of Arnold’s Cat Map as it has an even smaller value of correlation coefficient for original vs encrypted images and a proper unity value for original vs decrypted image. 
* The Logistic Map is another strong encryption algorithm. It has the smallest correlation coefficient for original vs encrypted image among all the algorithms implemented. 

The overall conclusion was that all the algorithms had their own pros and cons and each of them had different uses. Though, as per our implementation and study, the Henon’s Chaos Map would be ideal for any type of use case. It is safe and strong in encryption and has strong metrics. 
