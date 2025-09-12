### General Instructions

1. The aim is to introduce the students to the working of the Go-back-N ARQ and how it behaves under the situations such as frame lost or Acknowledgement Lost.  
2. Once redirected to simulation page (default for window size 3), then they are required to choose the frame size for which the simulation is desired.  
3. For the respective frame size, the simulation begins with an array (labeled as Frames) representing the frames on the left side of the page and the instructions prompted on the right side of the page.  
4. The user needs to make the right selections in the array for the simulation to run further.  
5. If the user fails to select the correct frame at any point of simulation, the “Wrong Frame Selected” is prompted on the right side of the screen and until the user successfully selects the correct frame, the simulation does not proceed and the User is given as many retries as needed.  
6. An index is provided to the left of the screen to allow the user to understand which color signifies what behaviour.  

### For a window size of 3, follow these steps:

1. Firstly, select the first three frames to be sent to the receiver, i.e., 1,2,3 and now wait to receive the acknowledgment of the 1st frame.  
2. After ACK 1 received, select the next frame to be sent i.e., 4.  
3. ACK 2 lost in between, retransmit all the frames of the current window i.e., 2,3,4.  
4. After ACK 2 received, select the next frame to be sent i.e., 5.  
5. After ACK 3 received, select the next frame to be sent i.e., 6.  
6. After ACK 4 received, select the next frame to be sent i.e., 7.  
7. ACK 5 not received, retransmit all the frames of the current window.  
8. After ACK 5, 6, 7 received, select the next three frames to be sent.  
9. ACK 8, 9, 10 received, ALL FRAMES SENT!  
10. Input the correct total number of frames transmitted and click the **Submit** button.  
11. Select other window size to perform simulation.  

### For a window size of 4, follow these steps:

1. Firstly, select the first four frames to be sent to the receiver, i.e., 1,2,3,4, and now wait to receive the acknowledgment of the 1st packet.  
2. After ACK 1 received, select the next frame to be sent i.e., 5th and the window will slide having four frames, i.e., 2, 3, 4, 5.  
3. After ACK 2 received, select the next frame to be sent i.e., 6th and the window will slide having four frames, i.e., 3, 4, 5, 6.  
4. Retransmit all the frames of the current window i.e., 3, 4, 5, 6 because packet 3 lost.  
5. After ACK 3, 4 ,5, 6 received, select the next four frames to be sent.  
6. ACK 7 lost, so retransmit all the frames of the current window i.e., 7, 8, 9, 10.  
7. ACK 7, 8, 9, 10 received, ALL FRAMES SENT!  
8. Input the correct total number of frames transmitted and click the **Submit** button.  
9. Select other window size to perform simulation.  

### For a window size of 5, follow these steps:

1. Firstly, select the first five frames to be sent to the receiver, i.e., 1,2,3,4,5, and now wait to receive the acknowledgment of the 1st packet.  
2. After ACK 1 received, select the next frame to be sent i.e., 6th and the window slides containing five frames, i.e., 2, 3, 4, 5, 6.  
3. After ACK 2 received, select the next frame to be sent i.e., 7th and the window slides containing five frames, i.e., 3, 4, 5, 6, 7.  
4. ACK 3 not received because the acknowledgment is lost, retransmit all the frames of the current window i.e., 3, 4, 5, 6, 7.  
5. After ACK 3 received, select the next frame to be sent i.e., 8.  
6. After ACK 4 received, select the next frame to be sent i.e., 9.  
7. After ACK 5 received, select the next frame to be sent i.e., 10.  
8. ACK 6 not received, retransmit all the frames of the current window i.e., 6, 7, 8, 9, 10.  
9. ACK received for all frames, ALL FRAMES SENT!  
10. Input the correct total number of frames transmitted and click the **Submit** button.  
11. Select other window size to perform simulation.  
