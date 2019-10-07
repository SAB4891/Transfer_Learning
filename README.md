 Transfer Learning project with VGG19 model 
-retreive the VGG19 pre-trained weights/model without the output layer, and specify your desired input shape
-pass all picture through that model and extract their features 
-build and compile a new model that can assimilate same input dimension from the previous stage
-pass the extarcted features from the VGG19, into the new model
-take advantage of verbose to choose the best batch size and epochs number to avoid ovverfitting
-finally, classify a new image (your image) and retrieve its prediction probability 

-A step further, resize your image that it would fit into the VGG19, 
-pre-process your image as per the VGG19 specs 
-build an intermediate model that would take on VGG19 inputs like, and output the first conv. layer
-retrieve the output (conv layeer) & visualize the first conv. filters 
