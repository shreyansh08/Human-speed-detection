Following libraries should be available to you in python for successfully running the file:

1. tkinter
2. os
3. time
4. PIL
5. cv2
6. numpy
7. random
8. collections
9. matplotlib

To run the file, run pre.py.

After video is obtained, the script would transfer it to speed3.py which would detect the humans in the video and detect their speed. The speed would be should in real time on moving humans and at the end a graph would be generated denoting the speed of all humans present in the video over time.      


Working of the Project:      
It would ask you the option to select a file from your local disk or capture a video using your webcams. This gives you option to process a pre-captured video which would be helpful in finding speed of humans which is previously known for checking if it is working as expected. Other option is to capture a live video which does not work clearly as good since the frame rate is limited which means humans can be stopped from tracking. One great feature is if there are multiple humans, it shows each human in different colored rectangular boxes which is easy to distiguish. The graphs also generated has same color composition for better understanding. 
