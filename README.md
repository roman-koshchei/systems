Developing autonomous systems to neutralize long range drone threats. 

My current focus is to train object detection AI model and create real-time object tracking system running on Single Board Computer.

---

Demonstration of my first model. Results of training show that it's overfitting and there seem some blunders in the initial dataset.

For tracking in the video, I use pure model output without any additional techniques that I plan to introduce later.

Click on the [link to video](https://www.youtube.com/watch?v=BvAa8w46dtk).

<iframe style="width:100%;height:auto;" width="640" height="480" src="https://www.youtube.com/watch?v=BvAa8w46dtk" 
frameborder="0" allowfullscreen></iframe>

---

Open-Source tools I developed along the way:

- [YOLO Auto Annotation](https://github.com/roman-koshchei/yolo-auto-annotation) creates YOLO dataset from specified images using Moondream AI model to find bounding boxes for your classes. It reduces time required to go through images and annotate them yourself.

- [YOLO Dataset Visualizer](https://github.com/roman-koshchei/yolo-dataset-visualizer) allows to scroll through dataset and see bounding boxes on images. You can remove image from dataset if bounding boxes are incorrect. I use it after Auto Annotation to remove occasional mistakes.
