# ALPR
Automatic License Plate Detection and Recognition System
The focus of the proposed work to apply novel techniques in the 
context of registration number plate identification and realization. In a vast 
country like India, most of the plates are not standard, so a solution is 
needed that targets multiple formats and fonts. Firstly, Number Plate region 
(the Region-of-Interest) is detected using YOLOv5, which is now the most 
advanced object identification algorithm available. It is a novel 
convolutional neural network (CNN) that detects objects in real-time with 
great accuracy. This approach uses a single neural network to process the 
entire picture, then separates it into parts and predicts bounding boxes and 
probabilities for each component. These bounding boxes are weighted by the 
expected probability. and extracted amongst the larger captured image of the 
vehicle. Later, the task is to recognize the numbers and characters present in 
the region of interest. Here optical character recognition (OCR) is applied to 
the new image and it extracts all the characters. These characters may be the 
numbers and alphabets present in the number plate. Then the obtained image 
is converted to text and it is stored in a string variable which will be used to 
obtain the vehicle identification details
