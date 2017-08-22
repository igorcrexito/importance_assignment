# importance_assignment
Importance annotations for the paper "Assigning Relative Importance to Scene Elements

Each folder corresponds to one of the annotations used on the paper and described on http://www.ssig.dcc.ufmg.br/importance-annotation-vip-uiuc-pascal-sentence-datasets/.

Boxes:
- vip_boxes/vipboxes.rar: Extract this rar to get the boxes related to each VIP image. Each extracted file (xml) corresponds to one image and contains the coordinates of bounding boxes.
- uiuc_boxes/uiucboxes.rar: Extract this rar to get the boxes related to each UIUC image. Each extracted file (xml) corresponds to one image and contains the coordinates of bounding boxes.

Importance Annotations:
- vip_annotations/vipannotations.txt: This file contains the importance labels resultant from the majority voting of users' annotations performed on the VIP dataset. Each line contains 4 digits: The first one corresponds to the image index, ranging from 1 to 200. The remaining three digits correspond to the label annotation (0 0 1 - first is less important than second, 0 1 0 - elements are equally important, 1 0 0 - first element is more important than second).
- uiuc_annotations/uiuc_annotations.rar: Extract this rar to get the annotations performed by each of the 4 users over the UIUC Pascal Sentence Dataset. Each user is represented by a txt file, containing in each line, the importance label associated to it. Each line contains 4 digits: The first one corresponds to the image index. It can be noticed that some images are not contemplated since they contain only one object. The remaining three digits correspond to the label annotation (0 0 1 - first is less important than second, 0 1 0 - elements are equally important, 1 0 0 - first element is more important than second).

