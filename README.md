# minimum_branching-stereo-matching
minimum_branching-stereo-matching is a non-local cost aggregation stereo matching algorithm，which depends on minimum branching[1]
(a directed version of minimum spanning tree). we use Tarjan‘s method[2] to construct minimum branching, and the process of construction
can segment an image to fragments, which helps us to distinguish the texture and textless region of the image.
![Image text](https://raw.githubusercontent.com/zssjh/git_img/master/1__.png)

experimental result：
We test the algorithm on Middlebury Stereo including 2005,2006 and 2014 version and real scene, and receive better results than non-local[3] and ST method
[4].
2014 Dataset result:
![Image text](https://raw.githubusercontent.com/zssjh/git_img/master/1_dataset.png)
The second column is segment result relaized by our own method, and the following columns in trun are groundtruth, ours, non-local and
ST.

real scene result:
![Image text](https://raw.githubusercontent.com/zssjh/git_img/master/1_scene_2.png)
The second column is segment result relaized by our own method, and the following columns in trun are ours, non-local and
ST.


[1]
[2]
[3]Yang Q. A non-local cost aggregation method for stereo matching[C]//Computer Vision and Pattern Recognition (CVPR), 2012 IEEE Conference on. IEEE, 2012: 1402-1409.
[4]Mei X, Sun X, Dong W, et al. Segment-tree based cost aggregation for stereo matching[C]//Proceedings of the IEEE Conference on Computer Vision and Pattern Recognition. 2013: 313-320.

