# Building the Project

To build this project, you can use colcon build. However, if the build is not successful, please follow these steps:
##### Note: 
This instruction assumes that the user is using a Debian-based Linux distribution where `apt` is the package manager. Make sure to provide instructions tailored to different operating systems or package managers if your project supports multiple platforms.

#### Error:

![Screenshot from 2024-02-17 10-35-56](https://github.com/maduwanthasl/ros2_humble/assets/107339150/fda5e6a8-9c1f-42a6-ad88-c20eb256b381)

First, update the system repositories:
<pre>sudo apt update</pre>

Next, let's ensure that pip is installed:
<pre>sudo apt install python3-pip</pre>

Next list this packages and versios
<pre>pip3 list</pre>

Next type
<pre>pip3 list | grep setuptools</pre>

Change the version of setuptools
<pre>pip3 install setuptools==58.2.0</pre>

now look it is complete
<pre>pip3 list | grep setuptools</pre>

you will see following type massege:

![image](https://github.com/maduwanthasl/ros2_humble/assets/107339150/4c2b11ac-9e4d-4053-95db-4999f1e5e8e6)

Next try this
<pre>colcon build</pre>  





