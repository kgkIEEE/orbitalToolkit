# orbitalToolkit

The orbital toolkit is a set of functions that can be used to model satellite orbits and analyze data

The basic functions are
1. Generate simulated observations: Ingest satellite orbital data, including the Two Line Element set (TLE) format, then propagate those orbits to the desired time and based on the simulated sensor characteristics generate observations of satellites 
2. Create a model of the environment using the simulated observations: estimate the orbital parameters of objects from their observations
3. Generate alert messages for new objects and anomalous activity (such as breakups and maneuvers)
4. Generate operator recommendations in response to alert messages.  Operator actions include requesting additional observations of new objects and anomalous activity, documenting status changes (launchs, dockings, etc...)
