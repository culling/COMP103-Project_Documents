## Emergency Room Simulator
![Screenshot from image](docs/EmergencyRoomSimulator-screenshot-01)
### Purpose - Simulate an emergency room

### Introduction
The EmergencyRoom program is a tick-based simulation of patients in the emergency room of a hospital. Patients arrive, and then move through a series of treatments in different departments - X-ray, MRI, Operating Theatre, etc. When they have finished all their treatments, they are discharged.

Each department only has facilities to treat a fixed number of patients at any one time; if there are more patients than that, they have to wait in the waiting room of the department until a current patient has finished their treatment.

Patients can have different priorities, which are assigned when they arrive at the emergency room.

### Details
Given a simple and incomplete implementation of an Emergency room simulator I implemented the additional functions.
+ Created constructors for different departments
+ Using a priority queue to simulate how patients should be prioritized and how this would impact wait times
+ Create custom departments to be added to the simulation
+ Created reports based on the performance of the simulated emergency room