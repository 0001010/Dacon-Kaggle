
# ๐ชGDSC SCH 3๊ธฐ Core Member Project
### โปRecycle-Cycle
<img src="./image/LOGO.PNG" width="150" height="150"><br>
๋ ํฌ์งํ ๋ฆฌ([Repo Link](https://github.com/Recycle-Cycle/Recycle-Cycle))

ํ๋กํ ํ์([Prototype](https://docs.google.com/presentation/d/1vj9ziAh9E7hY3_4KDfkxdO-1WbkcVV0S0qvFkQ86RCA/edit#slide=id.p1))

- "๋ถ๋ฆฌ์๊ฑฐ๋ฅผ ์ํ๊ณ  ํ๊ฒฝ์ค์ผ์ ์ค์ฌ๋ณด์!"๋ผ๋ ์ทจ์ง๋ก ์ฑ ๊ฐ๋ฐ
	- ์ด๋ฏธ์ง ์ธ์(ML Team)
	- ์ฑ์ ์(Flutter Team)
- ์นด๋ฉ๋ผ ๋ชจ๋์ ์ด์ฉํ์ฌ ์ฑ์์ ์ฌ์ง์ ์ฐ๊ณ  ๊ทธ ์ฌ์ง์ด ์ด๋ค ์ข๋ฅ์ ์ฐ๋ ๊ธฐ์ธ์ง ์์ธก(ML) -> ๊ฐ๋จํ ํต๊ณ๊ธฐ๋ฅ๊ณผ ๋ถ๋ฆฌ์๊ฑฐ๋ฅผ ๋ง์ดํ๋ฉด ๋๋ฌด๊ฐ ์๋ผ๋ ๊ฒ์ ๊ตฌํ(Flutter)
### ๐ง  ML Part

- ์ฌ์ฉ๋ชจ๋ธ : Mobile Net V3([describe model Link](https://www.tensorflow.org/api_docs/python/tf/keras/applications/MobileNetV3Small))<br>
   ์ฌ์ฉ๋ฐ์ดํฐ : Recycle_Classification_Dataset([Kaggle](https://www.kaggle.com/jinfree/recycle-classification-dataset))
- Data Set Validation ๊ธฐ์ค 96%์ ์ ํ๋<br>
   class label = 0 : can , 1 : glass , 2 : paper , 3 : plastic

[ML_Prediction Link](https://github.com/0001010/Dacon-Kaggle/blob/main/Recycle-Cycle(gdsc_project)/gdsc_core_toyproject_model_pred.ipynb)
- Issue : Model์ด ์ปค์ ์ฌ์์ด ์ข์์ปดํจํฐ๋ก ํ์ตํ ๋ชจ๋ธ๋ง ๋ฐ๋ก ๋ถ๋ฌ์์ ์์ธก<br></br>
<img src="./image/paper.PNG" width="250" height="300">  <img src="./image/plastic.PNG" width="250" height="300">
    
### โป์ ์ฒด์ ์ธ ๊ทธ๋ฆผ
<img src="./image/p1.PNG" width="350" height="250">  <img src="./image/p2.PNG" width="350" height="250">