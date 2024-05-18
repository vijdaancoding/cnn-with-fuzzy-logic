# Fuzzy Logic and CNN ☁️

A project that helps in mask detection and social distancing

## Introduction

Widespread isolation has shown us difficult it is to enforce safety protocols among the public and even more difficult to supervise it. 
The project uses CNN and Fuzzy Logic to identify masks and the state of distance between people. The CNN was able to achieve a high accuracy 
in identify its target while use of Fuzzy Logic although facing limitations was able to output desired results within those confines. 
Overall, the system would be able to help in the identification of people who have broken SOP’s and efficient supervision of safety protocols.

## Workflow 

![image](https://github.com/vijdaancoding/cnn-with-fuzzy-logic/assets/131896316/4c705d84-f2a3-4543-b0f9-224b8c55723b)

## CNN Architecture

![image](https://github.com/vijdaancoding/cnn-with-fuzzy-logic/assets/131896316/85e5b33c-c44d-4a76-b908-f2dd75537c0a)

The image shows the architecture of the CNN used through its ONNX file via the netron.app.

## Bounding Boxes and Fuzzy Logic

![image](https://github.com/vijdaancoding/cnn-with-fuzzy-logic/assets/131896316/d92463ca-820c-49f7-a0ed-f9c2dea4c033)

The initial images show their respective bounding boxes. The second layer shows the localized bounding box density. 
Lastly the third layer shows the membership function of SOP severity. As  the man and woman in the initial picture get closer you can see the 
black line moving from the ‘safe’ zone (green) to the ‘moderate’ zone (orange) and finally at the ‘severe’ zone shaded in blue
