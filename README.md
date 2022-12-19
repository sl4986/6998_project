# 6998_project
This is my code for creating a .tf model  
and there are four different modle can be generated from these code. 
you just need to chane the conv layer type  
1>VGG19 

2>VGG19_mobile 

3>ResNet52 

4>ResNet52_mobile 

after you get the .tf model: 

save it to the local: ./../saved_model.tf 
and run: 


pip install onnxruntime 

pip installl git+https://github.com/onnx/tensorflow-onnx 

and run this in command line: 

python -m tf2onnx.convert --saced-model ./../saved_model.tf --output conv_model.onnx --opset l1 --verbose 

then you can get a onnx model 

# how to check this project:

cause mobile appliaction load to github only can be opened by Android Studio, I just exported this project and there is a .apk for you to check.

you can use your mobilephone to visit http://shangruli.tk/gusha/gusha.html to download this application
