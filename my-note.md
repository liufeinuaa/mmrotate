# 我自己的跟踪mmrotate 官方工程更新的分支
# 自行增加一些cfg， 方便在我自己的机子上进行测试


File "/home/liufei/PyProjects/my_proj/mmrotate/mmrotate/core/bbox/coder/delta_midpointoffset_rbbox_coder.py", line 7, in <module>
    from mmdet.structures.bbox import HorizontalBoxes, get_box_tensor
ImportError: cannot import name 'get_box_tensor' from 'mmdet.structures.bbox' (/home/liufei/PyProjects/mmdetection-3.0.0rc1/mmdet/structures/bbox/__init__.py)



没有
from mmdet.structures.bbox import get_box_tensor
的bug还是存在。。。


