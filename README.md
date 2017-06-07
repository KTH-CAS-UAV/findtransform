# findtransform

Find a transformation between an odometry source and a rigid body by moving the
rigid body.

The program `findtransform` is fairly self-explanatory, just run it and it will
tell you what you need to know and do. Once you've found the transformation and
started publishing it in TF, you can use `pose_transformer` to republish the
odometry source's poses into the rigid body's frame.
