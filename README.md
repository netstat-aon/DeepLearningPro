# DeepLearningPro

### Introduction :
        In today's world, the illicit introduction of weapons into public spaces poses a grave security concern. Conventional security measures such as metal detectors and bag checks often prove inefficient and invasive. To address this urgent need, the 'Neural Guardian' project leverages Deep Neural Networks to swiftly and accurately detect concealed weaponry, enhancing safety and security in high-risk areas where firearms and other weapons are strictly prohibited


### Problem Description : 
        1. In a rapidly evolving world fraught with increasing security threats, the surreptitious introduction of weapons into public spaces has emerged as a formidable and pressing issue. Locations such as banks, educational institutions, and other high-profile venues have been confronted with a growing challenge: how to detect concealed or sophisticated weaponry efficiently, without causing unnecessary inconvenience to individuals entering these spaces. Traditional methods, including manual security measures like metal detectors and bag checks, often fall short in addressing this complex problem. They not only struggle to identify concealed weapons but also disrupt the flow of people, leading to inefficiencies and discomfort. In response to this urgent need for advanced and non-intrusive weaponry detection, the "Neural Guardian" project emerges as a beacon of innovation and security. By harnessing the power of Deep Neural Networks, this project aspires to swiftly and accurately identify any form of weaponry, providing the foundation for immediate intervention and prevention of potential harm or loss of life. "Neural Guardian" is poised to redefine the landscape of security, guaranteeing the safety and protection of the public in areas where firearms and other dangerous weapons are unequivocally prohibited.

        2. The Neural guardian also tries to automate the process of informing the authorities,		 removing the need for a manual intervention via a phone or other forms of radio.


### Possible project objectives - 
        1 - To Detect possible weapons
        2 - To differentiate people with authorized access and the ones without it.
        3 - To approach the problem with different loss functions , optimizers and networks 
        4 - To automatically notify appropriate authorities based on the intents/actions of the weapon owner.


### A Brief intro to Yolo - 
        Firstly the name "You only look once" comes from the fact that the algorithm uses 1x1 convolutions, meaning that size of the prediction map is gonna be exactly same as the feature map before it.

        The You only look once was mainly created by Joseph Redmon and Ali Farhadi in 2016.
        It was implemented using keras and opencv libraries.
        they've mainted the algorithm for 1-3 versions and gave up later on , due to their personal values.

        However, others tookover the project by forking it and made version 4-8.

        The yolo algorithm is the mixture of regression and classification.
        the object detection operation is treated as a regression problem
        where as the classification is achieved using a convolution neural network behind the scenes.

        we acheive the x,y,w,h co-ordinates of a bounding box using regression.
        and classify/tell whether we have our desired object in those co-ordinates or not using CNN.  

        additionally , we achieve x,y,w,h co-ordinates of each bounding box by clustering the dimensions
        of the ground truth boxes from the original dataset to find the most commons shapes and sizes.

        The alternatives to Yolo include R-CNNs , fast R-CNNs and Mask R-CNN.
        out of which fast R-CNN is the only algorithm which is fast enough to match the speed of yolo. 





### Preliminary Plan -
        1 - Data Acquisition : Assemble a varied dataset of images/videos with diverse weapon types
        2 - Data Preprocessing : Annotating the weapons, normalizing images and data augmentation
        3 - Set up a development environment.
        4 - Implement YOLO V7 Algorithm : Construct the model using YOLO V7, divide the dataset for
        training, validation, and testing.
        5 - Fine Tuning : Modify the model architecture for best performance.
        6 - Evaluation : Assess model reliability and accuracy using appropriate metrics and optimize to
        minimize false detections in various conditions.
        7 - Integration : Develop an alert mechanism to notify the concerned authorities immediately upon
        weapon detection.



