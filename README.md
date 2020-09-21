# Python_Yolo_test

 - **YOLO Real_Time Object Detection** :https://pjreddie.com/darknet/yolo/
 
Pour lancer le programme vous devez créer un dossier  contenant les fichiers suivants : 

  - coco.names ==> lien:https://github.com/pjreddie/darknet/blob/master/data/coco.names
  - yolov3.cfg ==> lien: https://github.com/pjreddie/darknet/blob/master/cfg/yolov3.cfg
  - yolov3.weights ==> lien:https://pjreddie.com/media/files/yolov3.weights
  
  **NB**: N'oubliez pas de modifier la ligne suivante pour donner le chemin des 2 fichiers *yolov3.cfg* et *yolov3.weights* 
  
  -`net = cv2.dnn.readNet("yolov3_cfg_path, "yolov3_weights_path")`
