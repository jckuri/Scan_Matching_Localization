# Scan Matching Localization

Self-Driving Car Engineer Nanodegree<br/>
https://www.udacity.com/course/self-driving-car-engineer-nanodegree--nd013

# Installation

Go to the Udacity workspace of the project "Scan Matching Localization" of the Lesson 3 "Localization" of the Self-Driving Car Engineer Nanodegree.

Copy the contents of the file [code/c3-main.cpp](code/c3-main.cpp) into the file `/home/workspace/c3-project/c3-main.cpp` in the Udacity workspace of the project "Scan Matching Localization". You can do it by copying and pasting the contents of the file [code/c3-main.cpp](code/c3-main.cpp) .

# Usage

Press the blue button "Desktop". Start one terminal. Run the Carla simulator by using these Unix commands:

```
su - student # Ignore Permission Denied, if you see student@ you are good
cd /home/workspace/c3-project
./run_carla.sh
```

Start another terminal. Compile the project by using these Unix commands:

```
cd /home/workspace/c3-project
cmake .
make
```

Run the project with the NDT algorithm by using Unix command:

```
./cloud_loc
```

Or run the project with the ICP algorithm by using Unix command:

```
./cloud_loc 2
```

Once the project is running, tap the UP key 3 times, with delays of 1 second between taps. If the green car gets left behind, run the project again and tap the UP key 3 times again. The second run usually produces better results than the first run does. **IMPORTANT: Never stop the Carla simulator.**


# Video Demonstrations

**Scan Matching Localization with LIDAR Point Clouds - Algorithm 1: Normal Distributions Transform NDT<br/>
https://youtu.be/EOKKcwuBtzo**
![NDT_Passed.png](/images/NDT_Passed.png)

**Scan Matching Localization with LIDAR Point Clouds - Algorithm 2: Iterative Closest Point (ICP)<br/>
https://www.youtube.com/watch?v=hZeZAm4jvW4**
![ICP_Passed.png](/images/ICP_Passed.png)
