# windows-ssd
SSD configure for windows10 with VS2013
# For compiler 
    One step   : you should caffe-ssd-windows.zip and modify *windows/CommonSetting.pros* for CPU mode, 
    because this reop only built in CPU successful.
    
    Two step   : Open Caffe.sln     
    
    Three step :  In classification.pro, you should remove classificaition.cpp and add ssd_detect.cpp  
    
    
