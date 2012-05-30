Tiny L-system Generator
======================

L-system fractal generator created for [js1k](http://js1k.com/2012-love/) contest.

The script executes given L-system code and generates fractals on the screen. This is the Hilbert curve:

    iters: 7
    angle: 90
    start: "L"
    L: "-Rf+LfL+fR-"
    R: "+Lf−RfR−fL+"

`iters` if the number of iterations. `angle` is the turning angle in degrees. `start` is the initial axiom. Other lines are the rewrite rules. Supported operators are +− for turning, lowercase letters for drawing, and [] for push and pop.

For more examples, see [here](http://x.vu/237908).
