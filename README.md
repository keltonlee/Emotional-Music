# Emotional Music ![music](https://user-images.githubusercontent.com/68526411/214819784-0945bdd1-2901-4342-997f-174902ac9e02.png)


In this fiercely competitive society, pressures stemming from works, finance, or families is bound to be a problem that everyone needs to face. We know that everyone manage their stress differently, and we provide suitable music's according to the current emotions of users who love music to substantially mitigate their stress.




## Approach
Using Kaggle FER2013 dataset to train our model by Tensorflow Keras. Furthermore, after detecting the user's face by our model, we can do some webcrawler to get some fantastic musics!!! 

<img width="550" alt="截圖 2023-01-26 下午7 38 58" src="https://user-images.githubusercontent.com/68526411/214826652-de37334f-0e2d-4b3f-97f2-4cf2afaf54e7.png">

## Details
(1) If the music ends?  
  A: The music will keep on moving to the next one by detecting the length of the music to pre-load the next music into our application.
  
(2) If the user changes the emotion?  
  A: It will not opportunely download the music from YouTube since the user's emotion may not been settled yet or the model have made a unclear prediction. Therefore, the model needs to detect the user's emotion has been changed and is stable at least 5 seconds to  ensure that the user has really changed the emotion. Then it will automatically download the music!
  
## Awards
- Merit Award of 2022 AI Cloud Contest (2022年AI智能雲端運算應用競賽), presented by Taiwan Space Agency (財團法人國家實驗研究院-國家太空中心)

## What did I learned
This is the first time I use Tensorflow Keras and CNN to build the model, it's pretty fun! And also, boundary conditions and exeption handling is essential in this project.
