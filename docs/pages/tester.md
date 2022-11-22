#### 1. Prepare
Before starting the quiz, you should pepare the following software and hardware.

**HW**: 
</br>&emsp;1. Work PC 
</br>&emsp;2. Android Phone

**SW**: 
</br>&emsp; 1. Download the [Unispectral Android APP v2.0 for Testing.apk](https://github.com/Unispectral-SW/uns-recruitment-quiz/releases/download/quiz_v1.0/uns-camera-release-v2.0.20221121_test.apk) 
</br>&emsp; 2. Download the [Spectral dataset.zip](https://github.com/Unispectral-SW/monarch-preprocess-app-docs/releases/download/unispectral_sdk_v1.0.0/SDK_dataset.zip)
</br>&emsp; 3. Python 3.8.10 
</br>&emsp; 4. uiautomator2 

#### 2. Quiz:
Please follow the pytest's rules and style to manage your testing scripts.
##### 1. Q1
Write a script "*test_q1.py*" which can realize the following functions:
</br>&emsp; 1. install the uns-camera-release-v2.0.20221121_test.apk on your android phone.
</br>&emsp; 2. open the "Monarch" App, you will see this page. 
</br>&emsp; 3. click the following button to enter spectral analysis page.
> <img src="https://user-images.githubusercontent.com/98015835/203248135-00aea9a5-4486-4199-92f0-547127c6a998.png" width="700" height="340">

> <img src="https://user-images.githubusercontent.com/98015835/203248471-7ca9d014-0fbb-43c4-bcc5-8507c2edd4a7.png" width="700" height="340">
##### 2. Q2:
Write a script "*test_q2.py*" which can realize the following functions:
</br>&emsp; 1. use python script to push SDK_dataset\raw_cubes\* to uns/SavedImages/

> <img src="https://user-images.githubusercontent.com/98015835/203261421-ce74ef16-8482-45c5-a14f-ac07289e8222.png" width="700" height="340">

</br>&emsp; 2. open "Monarch" APP, enter "Pseudo RGB" page.
</br>&emsp; 3. select cube "cube_20220826_145339"
</br>&emsp; 4. change "Pseudo Green at" to "920"
</br>&emsp; 5. click button "Apply Changes", you can see the analysis result.

> <img src="https://user-images.githubusercontent.com/98015835/203262756-84e08fc6-3196-4306-9108-1051d07f304a.png" width="700" height="340">

</br>&emsp; 6. if there is anything wrong with the algorithm, the analysis result will be different.<font color="red"> So, you should think about how to check if the analysis result is correct automatically.</font> 


#### 3. Feedback:
when you finishing the quiz, you have to packing the following data and send to us:
1. all python scripts.
2. screen recording which can show the whole process of running the two scripts. 

contact: super.feng@unispectral.com if you have any questions or want to submit your answers.