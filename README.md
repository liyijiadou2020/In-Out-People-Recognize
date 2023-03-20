# In-Out-People-Recognize
Using yolov5 to realize pedestrian detection and deepsort to track, it can better prevent the misidentification of the reid model in the case of occlusion.

I encapsulated yolov5 and deepsort into classes respectively, which are easy to embed into my own project, so as to facilitate the replacement of detection or tracking algorithms.

I replaced the representation extraction model of deepsort with the reid model trained by fastreid. Can improve tracking performance.

Realized the pedestrian counting function, counting the total number of people who have appeared in the camera, and counting the pedestrians crossing the custom yellow line. The effect is as follows(see `person_count.py`):
