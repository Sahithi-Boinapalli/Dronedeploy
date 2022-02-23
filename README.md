# Dronedeploy
# Drone Airspace Coding Challenge
* Given a square airspace, 128km x 128km, and N=10,000 drones occupying the
airspace our challenge is to efficiently compute how many drones are flying
too close to one another.
* Drone positions will be provided as an Nx2 array of [x,y] coordinates (in
meters).
* Drones must maintain a horizontal separation of radius 0.5km from other
drones.
* If a drone is within 0.5km of another drone, both are "in conflict".
* Have count_conflicts return the total number of drones that are in a
conflicted state. Not the total number of conflicts.
