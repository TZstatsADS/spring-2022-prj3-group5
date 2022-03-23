# Project 3: Weakly supervised learning -- label noise and correction

<img src="figs/noisy_labels.png" width="500">

### [Full Project Description](doc/project3_desc.md)

Term: Spring 2022

+ Team: Group 5
+ Team members:
	+ [Marcus Loke](https://www.linkedin.com/in/lokemarcus/) (ml4636)
	+ [Sarah Kurihara](https://www.linkedin.com/in/sarahkurihara/) (sqk2003)
	+ [Shintaro Nakamura](https://www.linkedin.com/in/shintaro-nakamura/) (sn2904)
	+ [Yinan Shi](ys3387@columbia.edu) (ys3387)
	+ [Yixuan Zhang](yz4081@columbia.edu) (yz4081)

+ Project summary: Weakly supervised learning is a topic that addresses the issue of noisy and imperfect labels, much like the image above where many labels do not correspond correctly with the images. In this project, we created various models that performs image classification on a large dataset of 50,000 images with noisy labels. A baseline multinomial logistic regression model is created in the starter code and we developed two models that improves on that: Model 1 uses a convolutional neural network (CNN) that's trained on noisy labels while Model 2 employs a label correction network before training the same CNN on the cleaned labels.

+ Technologies used: Python and R (Keras/TensorFlow)
	
**Contribution statement**: ([default](doc/a_note_on_contributions.md)) 
<br>
All team members attended all meetings and contributed to research and planning of the project.
<br>
+ <b>Marcus Loke (ml4636)</b> developed the entire project in R and cross-validated all work in a different programming language. He also created a unique model I which was selected as the group's model I based on the model's high performance. He performed Cross Validation on his unique models to assess performance.
+ <b>Sarah Kurihara (sqk2003)</b> worked in Python to create a unique model I for comparison to the rest of the group but was not selected as the group's model I. She translated the Model I from R into Python and performed Grid Search Cross Validation to optimize the selected model I and determine the appropiate parameters.
+ <b>Shintaro Nakamura (sn2904)</b> worked in Python to create a unique model I and label correction/model II used in model development phase for comparison (not selected). He performed Cross Validation on his unique model I to assess performance. He also creted the code for file reading for evaluation phase for the group.
+ <b>Yinan Shi (ys3387)</b> worked in Python to create a unique model I used in model development phase (not selected) and contributed to the label correction algorithm of model II. She is also the presenter for the project.
+ <b>Yixuan Zhang (yz4081)</b> worked in Python to create a unique model I used in model development phase (not selected) and contributed to the label correction algorithm of model II. Her label correction algorithm was selected for the project based on the model's highest performance. 


Following [suggestions](http://nicercode.github.io/blog/2013-04-05-projects/) by [RICH FITZJOHN](http://nicercode.github.io/about/#Team) (@richfitz). This folder is orgarnized as follows.

```
proj/
├── lib/
├── data/
├── doc/
├── figs/
└── output/
```

Please see each subfolder for a README file.
