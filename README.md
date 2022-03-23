# Project 3: Weakly supervised learning -- label noise and correction

<img src="figs/noisy_labels.png" width="500">

### [Full Project Description](doc/project3_desc.md)

Term: Spring 2022

+ Team: Group 5
+ Team members:
	+ [Marcus Loke](https://www.linkedin.com/in/lokemarcus/) (ml4636@columbia.edu)
	+ [Sarah Kurihara](https://www.linkedin.com/in/sarahkurihara/) (sqk2003@columbia.edu)
	+ [Shintaro Nakamura](https://www.linkedin.com/in/shintaro-nakamura/) (sn2904@columbia.edu)
	+ [Yinan Shi](ys3387@columbia.edu) (ys3387@columbia.edu)
	+ [Yixuan Zhang](yz4081@columbia.edu) (yz4081@columbia.edu)

+ **Project summary**: Weakly supervised learning is a topic that addresses the issue of noisy and imperfect labels, much like the image above where many labels do not correspond correctly with the images. In this project, we created various models that performs image classification on a large dataset of 50,000 images with noisy labels. A baseline multinomial logistic regression model is created in the starter code and we developed two models that improves on that: Model 1 uses a convolutional neural network (CNN) that's trained on noisy labels while Model 2 employs a label correction network before training the same CNN on the cleaned labels.

+ **Results summary**: Tested on 10,000 images with clean labels, the baseline model achieved an accuracy of 23% and model 1 achieved an accuracy of 47%. Tested on 3,000 images with clean labels, model 2 achieved an accuracy of 56%.   

+ **Technologies used**: R and Python (Keras/TensorFlow/PyTorch)
	
**Contribution statement**: ([default](doc/a_note_on_contributions.md)) 
<br>
All team members attended all meetings and contributed to research, planning and execution of the project.
<br>
+ <b>Marcus Loke (ml4636)</b> developed the entire project in R and cross-validated all work in a different programming language as opposed to the starter code in Python. He also created a unique model I which was selected as the group's model I based on the model's high performance. He performed Cross Validation on his unique models to assess expected performance.
+ <b>Sarah Kurihara (sqk2003)</b> worked in Python to create a unique model I for comparison to the rest of the group but was not selected as the group's model I. She translated the Model I from R into Python and performed Grid Search Cross Validation to optimize the selected model I and determine the appropriate parameters.
+ <b>Shintaro Nakamura (sn2904)</b> worked in Python to create a unique model I and label correction/model II used in model development phase for comparison (not selected). He performed Cross Validation on his unique model I to assess performance. He also created the code for reading new images for the evaluation phase for the group.
+ <b>Yinan Shi (ys3387)</b> worked in Python to create a unique model I used in model development phase (not selected) and contributed to a new label correction algorithm using PyTorch for model II (not selected). She is also the presenter for the project.
+ <b>Yixuan Zhang (yz4081)</b> worked in Python to create a unique model I used in model development phase (not selected) and contributed to the label correction algorithm for model II. 


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
