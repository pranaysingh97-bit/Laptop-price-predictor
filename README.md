This is a Laptop price predictor which contains below columns.
Company             
TypeName            
Inches              
ScreenResolution    
Cpu                 
Ram                 
Memory              
Gpu                 
OpSys               
Weight              
Price 

Feature engineering is done prior to prediction. Addtional feature like Touchscreen, IPS (screen), X-resolution, Y-resolution, ppi, CPU brand, HDD, SDD, GPU Brand, OS.

Features removed are Screen resoltuion as we have made two columns Touchscreen, IPS, X-resolution, Y-resolution and Inches as there are only three model of screen (13.3,14,15).

Prediction model used are Leniar regressoin, KNN, Decison tree, Random forest, AdaBoost
