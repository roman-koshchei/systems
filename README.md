Developing autonomous systems to neutralize long range drone threats. 

My current focus is to train object detection AI model and create real-time object tracking system running on Single Board Computer.

---

Demonstration of my first model. Results of training show that it's overfitting and there seem some blunders in the initial dataset.

For tracking in the video, I use pure model output without any additional techniques that I plan to introduce later.

Click on the [link to video](https://www.youtube.com/watch?v=BvAa8w46dtk).

<iframe width="560" height="315" src="https://www.youtube.com/embed/BvAa8w46dtk?si=hzgGpZQ70anCTmFZ" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

Open-Source tools I developed along the way:

- [YOLO Auto Annotation](https://github.com/roman-koshchei/yolo-auto-annotation) creates YOLO dataset from specified images using Moondream AI model to find bounding boxes for your classes. It reduces time required to go through images and annotate them yourself.

- [YOLO Dataset Visualizer](https://github.com/roman-koshchei/yolo-dataset-visualizer) allows to scroll through dataset and see bounding boxes on images. You can remove image from dataset if bounding boxes are incorrect. I use it after Auto Annotation to remove occasional mistakes.
