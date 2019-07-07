## The Auckland Road System
![Screenshot from image](docs/AucklandRoads-screenshot-01.png)
### Purpose - Create a map of the Auckland road system, implement pathfinding and identifying non redundant intersections

### Features
+ Reads tab seperated data files to import the roads
+ Displays the map with zoom, panning
+ Able to highlight a road when searching for the road by name
+ Implements a Trie structure for fast road name searches
+ Looks up connected roads by clicking on an intersection
+ Performs A* search with a heuristic that can be easily modified. Currently has a heuristic that is based on distance, with a modifier that can allow for more/less exploration
+ Paths are output in the nice format in text and highlighted on the map
+ Displays explored paths for easy debugging or modification of heuristic
+ Articulation points are discovered and highlighted when loading a map
+ The Pathfinding heuristic has a boolean for time/distance and a set of buttons for changing between time and distance
