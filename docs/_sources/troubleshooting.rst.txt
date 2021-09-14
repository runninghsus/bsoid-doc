Troubleshooting
===============

The most common problems for B-SOiD users come from the input data. First, while the output videos may look pretty good, oftentimes the pose estimation is actually quite jittery. We recommend checking for large jumps in estimated position before using B-SOiD, and removing those points either through pose estimation model improvement, or if necessary, replacing jumping points with an interpolated position. Second, B-SOiD clusters behavior based upon the available inputs. As such, do not use input features that aren’t useful. For instance, if studying facial expressions, the position of the ears or elbows should be excluded as these are uninformative or unrelated body parts. Similarly, redundant points should be eliminated, such as multiple points along a solid bone or along the belly. (All examples should be taken with a grain of salt, as specific experiments or animal models may not fit).More information as we hear about new challenges. Join our slack_ for more help from the community.

.. _slack: https://join.slack.com/t/b-soid/shared_invite/zt-dksalgqu-Eix8ZVYYFVVFULUhMJfvlw
