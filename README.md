# tf2_study
Understanding tf2 for ros

## Useful commands

**Watch the tf tree live**
```sh
rosrun rqt_tf_tree rqt_tf_tree
```

**MAKE pdf of tf tree**
```sh
# makes frames.pdf and frames.gv 
# in whatever directory you run this
rosrun tf2_tools view_frames.py
evince frames.pdf
```
