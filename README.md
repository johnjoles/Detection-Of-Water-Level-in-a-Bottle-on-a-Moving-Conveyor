# Quantity-and-Quality-of-Fluid-in-a-Bottle-on-a-Moving-Conveyor

In Industry 4.0, After the fluid is filled in the fluid plant.The Quantity and Quality of the bottle should be determined. So, that the customer ordered product can be satisfied.

Here, the bottle moves on a conveyvor from the Fluid Plant to the Quality Station. After it reaches the station, the quantity and quality analysis is being processed.

For detecting the bottle in the environment, Deep Neutral Network (DNN) Module is being used based on weighpath and configpath in addition to COCO dataset.

configPath = 'ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt';
weighPath = 'frozen_inference_graph.pb'

Warping the Bottle inorder remove unwanted environment in the image background.

Performing Image Processing techniques like threshold, blurring, canning are used to find the fluid present(Level)

<img width="570" alt="Bottle" src="https://github.com/user-attachments/assets/1c5fd97e-f173-41b2-8fc1-d48bd0d34a9c" />

Figure1       Figure2             Figure3

#Note : the Quality processes is yet to be done.






