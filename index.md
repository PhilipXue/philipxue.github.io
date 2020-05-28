## Portfolio

---

### Personal project 

[TensorFlow Speech Recognition Challenge](https://www.kaggle.com/c/tensorflow-speech-recognition-challenge)
<img src="images/kaggle_tf_thumb.png?raw=true"/>
- Speech commands recognition competition held by Google Brain
- Ranked 50th out of 1315 teams / 1593 competitors (Silver Metal / top 4%)
- Build the system with CNN & RNN and coded with Tensorflow / Keras
- Please check [my github repo](https://github.com/PhilipXue/TF-CRNN-kaggle-voice-competition) for code.


---
### Project at work
As an algorithm engineer, my daily responsibility includes searching for State of the art work for computer vision and machine learning tasks like object detection. Understand and reproduce them. And I also train models per client demand, gathering data, train the model, evaluate its performance, and optimize for deployment. At my current team, 1 algorithm engineer is assigned to a project and the engineer will do all the technique related workload for model developing.
In recent times my main focus is on object detection related models. Especially one stage.
Per NER request, I cannot unveil the detail of many client projects.

#### R&D task, Face verification model  
- Developed a facial verification model from scratch.  
- Gathered data, developed a method to semi-automate the annotation.  
- Successfully trained models that reach SoTA level at the time and models are deployed into product developed for other clients
  
#### R&D task, Object detection train from scratch
- Use techniques like learning rate schedule, normalization to train a one-stage object detection model on COCO from scratch.
- Trained a range of models from lightweight (MobileNet based ssdlite) to large ones (ResNet based RetinaNet). reaching the performance of corresponding finetuning models. These models are used as a base model for other projects that needs to finetune on small size datasets.
  
#### R&D task, Internal R&D, Edge device for object detection.  
- Test and verify a range of edge devices that can be applied for edge cases. Benchmark running speed of them.  
- Quantized the lightweight developed in project 2, and able to get 2x inference speed compared with the original one.  
- Package benchmark module for other MLOps pipeline.  
  
#### Client Facing task: Pet surveillance 
- Train and evaluate a lightweight model to detect pet presence
- Optimize inference cost

<p style="font-size:11px">Page template forked from <a href="https://github.com/evanca/quick-portfolio">evanca</a></p>
<!-- Remove above link if you don't want to attibute -->
