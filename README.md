# Optical_Flow:- 

Optical flow is a per pixel prediction and the main idea is that it assumes a brightness constancy, meaning it tries to estimate how the pixels brightness moves across the screen over time. It assumes that I(x, y, t) = I(x + Δx, y + Δy, t + Δt) in plain english this is the pixel characteristic at time t (i.e. rgb values) is the same as the pixel characteristics at Δt but at a different location (denoted by Δx and Δy ), where the change in location is what is predicted by the flow field. An example of this is that assume we have the following rgb values at 1 second, (255, 255, 255) and at x, y position (10, 10) in the frame, Optical flow assumes that at t = 2 seconds, the same rgb value (255, 255, 255) will still exist in the screen and if there is motion, it will exist at a different part of the frame i.e. (15, 19). Thus the optical flow displacement vector for this motion will be [9, 5 ]. This means if we take the original pixel position and apply to the displacement vector, we should get the new image (this is what warping an image is about, and which we will come to later).

![image](https://user-images.githubusercontent.com/76057253/137062700-3c2dc8e3-1ce6-492c-85e1-d1da146f3a77.png)

![image](https://user-images.githubusercontent.com/76057253/137062799-0932e04d-e1e7-4247-834e-9ba7fea55065.png)

![image](https://user-images.githubusercontent.com/76057253/137062818-28298668-cb56-4da5-9630-19775730fbca.png)
