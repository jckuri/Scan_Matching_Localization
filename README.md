# Scan Matching Localization

Self-Driving Car Engineer Nanodegree<br/>
https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013

# Installation

Go to the Udacity workspace of the project "Scan Matching Localization" of the Lesson 3 "Localization" of the Self-Driving Car Engineer Nanodegree.

Copy the contents of the file `code/c3-main.cpp` into the file `/home/workspace/c3-project/c3-main.cpp` in the Udacity workspace of the project "Scan Matching Localization". You can do it by copying and pasting the contents of the file `code/c3-main.cpp`.

# Usage

In the Udacity workspace of the project "Scan Matching Localization", compile the project, after you copied the file `code/c3-main.cpp`. Use these Unix commands:

```
cd /home/workspace/c3-project
cmake .
make
```

Press the blue button "Desktop". Start one terminal. Run the Carla simulator by using these Unix commands:

```
su - student # Ignore Permission Denied, if you see student@ you are good
cd /home/workspace/c3-project
./run_carla.sh
```

# Demos

**Scan Matching Localization with LIDAR Point Clouds - Algorithm 1: Normal Distributions Transform NDT<br/>
https://youtu.be/EOKKcwuBtzo**
![NDT_Passed.png](/images/NDT_Passed.png)

**Scan Matching Localization with LIDAR Point Clouds - Algorithm 2: Iterative Closest Point (ICP)<br/>
https://www.youtube.com/watch?v=hZeZAm4jvW4**
![ICP_Passed.png](/images/ICP_Passed.png)
