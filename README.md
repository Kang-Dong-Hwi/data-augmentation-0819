# data-augmentation-0819

<br>

### [test_data.ipynb](https://github.com/Kang-Dong-Hwi/data-augmentation-0819/blob/master/test_data.ipynb)
final_main.mat
,contest_labeling_취합.xlsx 파일에서 magnitude, phase, label값 .npy 로 저장
<br>

### [validation_dataset.ipynb](https://github.com/Kang-Dong-Hwi/data-augmentation-0819/blob/master/validation_dataset.ipynb)
magnitude, pahse, label값  변환 후 x_data.pt, y_label.pt로 저장

***************

### Screenshots
<!--
https://github.com/Kang-Dong-Hwi/data-augmentation-0819/blob/master/aug2_2(42.4).png
https://github.com/Kang-Dong-Hwi/data-augmentation-0819/blob/master/aug_noise(38.2).png
https://github.com/Kang-Dong-Hwi/data-augmentation-0819/blob/master/aug_noise2(34).png
-->

<table>

  <tr> 
      <td ><br><br>  
        
   [data_augumentation_0818](https://github.com/Kang-Dong-Hwi/data-augmentation-0818) 
        
   timestretch + reversed data  </td>
   
   <td ><br><br> std:0.001 gaussian noise data 1000개 추가 학습  </td>
   <td ><br><br> std:0.0001 gaussian noise data 1000개 추가 학습 </td>
   
   
   
  </tr>
  
  

  <tr>
    <td> <img src="https://github.com/Kang-Dong-Hwi/data-augmentation-0819/blob/master/aug2_2(42.4).png", height=400px, width=350px>  </td>
    <td> <img src="https://github.com/Kang-Dong-Hwi/data-augmentation-0819/blob/master/aug_noise(38.2).png", height=400px, width=350px>  </td>
    <td> <img src="https://github.com/Kang-Dong-Hwi/data-augmentation-0819/blob/master/aug_noise2(34).png", height=400px, width=350px>  </td>
 </tr>
  
  <tr> 
      <td> accuracy: 42.4% <br> </td>
      <td> accuracy: 38.2% <br> </td>
      <td> accuracy: 34.0% <br> </td>
  </tr>
  
  
    
  
  
</table>
