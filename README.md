Build Procedure
===============

Download the source for the dependency
`git clone https://github.com/ipa320/cob_perception_common.git`
Dowload the source for this code
`git clone https://github.com/ipa320/cob_people_perception.git`

Add your path to your `~/.bashrc`. For example, if you cloned the file into your home directory, you would add the following line to you `~/.bashrc`. Make sure it's after the `source` declaration you made when you installed ROS:
`export ROS_PACKAGE_PATH=$ROS_PACKAGE_PATH:$HOME/cob_perception_common` .

At this point your going to have to update your `~/.bashrc` either by closing your current terminal and opening a new one or using the command ` bash --login`

Finally, go to the `cob_people_detection` directory with 
`roscd cob_people_detection`
and build the package and all of its dependencies by typing
`rosmake`

To Run
======
Please see the [wiki](http://wiki.ros.org/cob_people_detection).
