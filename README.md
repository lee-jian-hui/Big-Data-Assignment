# Big-Data-Project
Aims to stream dummy real-time high-velocity data -> process the stream in real-time -> stored in database OR displayed as a real-time visualization
This is my assignment for the unit FIT3181: big data processing and management as part of my undergrad studies.
The tech stack used: python, apache spark, apache kafka, mongoDB


As you've noticed, these files are notebook files, I am not quite sure if it is version dependent however. 
So, to run these files, you are recommended to run them in a jupyter noteboook environment, VS-code can be an alternative as well.

**Instructions for trying to run the program: (order is not important, however these are recommended steps)**
1. Run the producer files first, to start the streaming of data to replicate that of real-time sensors that pump on high-velocity, high-variety data streams
the files: Assignment_PartB_Producer1, Assignment_PartB_Producer2, Assignment_PartB_Producer3

2. then run the streaming jupyter notebook: Assignment_PartB_Streaming_Application

3. finally, you can run the consumer notebooks: Assignment_PartB_Data_Visualisation

