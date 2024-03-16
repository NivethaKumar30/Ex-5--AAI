<H3>ENTER YOUR NAME: NIVETHA .K </H3>
<H3>ENTER YOUR REGISTER NO.212222230102</H3>
<H3>EX. NO.5</H3>
<H3>DATE:16-03-2024</H3>
<H1 ALIGN =CENTER> Implementation of Kalman Filter</H1>
<H3>Aim:</H3> To Construct a Python Code to implement the Kalman filter to predict the position and velocity of an object.
<H3>Algorithm:</H3>
Step 1: Define the state transition model F, the observation model H, the process noise covariance Q, the measurement noise covariance R, the initial state estimate x0, and the initial error covariance P0.<BR>
Step 2:  Create a KalmanFilter object with these parameters.<BR>
Step 3: Simulate the movement of the object for a number of time steps, generating true states and measurements. <BR>
Step 3: For each measurement, predict the next state using kf.predict().<BR>
Step 4: Update the state estimate based on the measurement using kf.update().<BR>
Step 5: Store the estimated state in a list.<BR>
Step 6: Plot the true and estimated positions.<BR>
<H3>Program:</H3>





<H3>Output:</H3>

![image](https://github.com/NivethaKumar30/Ex-5--AAI/assets/119559844/f8bdb057-5f6a-4969-aeaa-b2cb000a8657)


<H3>Results:</H3>
Thus, Kalman filter is implemented to predict the next position and   velocity in Python



