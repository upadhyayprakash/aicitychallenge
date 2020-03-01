
# Object Detection Challenges:
1. Occlusion
2. Dark Light
3. Wash-out
4. Scale/Rotation/Shift Variance
5. Color/Shape variation (e.g. Face Deformation)
6. Missing Features (Goggles for face, Super Cars or Flying Cars, just in case :P )
7. Multi-Class detection

# Object Recognition Challenges
1. Duplicate IDs to different objects (FRs)
2. Global Recognition ID storage and Sharing consistently across instances of cameras.(Multi-Camera/View recognition)
3. ID longevity(keep the object features saved for longer)
4. Anonymity of Object despite feature storage.
5. De-boarding/Removal of Object from Recognition system (GDPR)

# Object Tracking Challenges:
1. Similar features (almost equal, like twin kids in FR, and Vehicle rally like in republic day parade)
2. Occlusion
4. Changing Lighting(on road or object reflections)
5. Duplicate IDs(tracker ID or going Recognition ID)
6. Speed of moving object (sudden movement or inflow-outflow of object, like fast moving Vehicle)
7. Quick movements (like person moving faster or turning around back and front)
8. Back/Rear view challenge (to be able to keep the tracker robust despite random features missing frequently)
9. Objects from multiple classes occluding each other.
10. Tracker Swapping - DeepSORT for efficient and smooth tracking.

# Misc Challenges:
1. Visualization of the Training progress and features learning life, just like new borns spending their life learning new things and photos are kept to recall the moments in past. (to be able to track them in future)
2. Reasoning a Prediction at particular timestamp. (AI reasoning - GDPR)
3. Model Deployment/Version Management (for testing and performance/accuracy comparison)
