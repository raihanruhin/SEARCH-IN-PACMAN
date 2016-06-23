# SEARCH-IN-PACMAN
This is an Artificial Inteligence Project.  
In this project, Pacman agent finds paths through his maze world, both to reach a particular location and to collect food efficiently.   
I have build general search algorithms and apply them to Pacman scenarios.  
Algorithms:  
  >> Depth First Search  
  >> Breadth First Search  
  >> Uniform Cost Search  
  >> A* search  
Conditions Handled: 
  >> Finding All the Corners  
  >> Corners Heuristic  
  >> Eating All The Dots  
  >> Suboptimal Search  
  
Language Used: Python 2.7  
__________________________________________________________________
If you wish to test this project in Windows
  1. Make sure you have Python installed. 
  2. Downlod files. 
  3. Open Command Prompt and go to the file location
  4. Copy and paste following commands (Single line each time) in command prompt to see how it works.
     >> python pacman.py --layout testMaze --pacman GoWestAgent
     >> python pacman.py --layout tinyMaze --pacman GoWestAgent
     >> python pacman.py -l tinyMaze -p SearchAgent -a fn=tinyMazeSearch
     >> python pacman.py -l tinyMaze -p SearchAgent
     >> python pacman.py -l mediumMaze -p SearchAgent
     >> python pacman.py -l bigMaze -z .5 -p SearchAgent
     >> python pacman.py -l mediumMaze -p SearchAgent -a fn=bfs
     >> python pacman.py -l bigMaze -p SearchAgent -a fn=bfs -z .5
     >> python pacman.py -l mediumMaze -p SearchAgent -a fn=ucs
     >> python pacman.py -l mediumDottedMaze -p StayEastSearchAgent
     >> python pacman.py -l mediumScaryMaze -p StayWestSearchAgent
     >> python pacman.py -l bigMaze -z .5 -p SearchAgent -a fn=astar,heuristic=manhattanHeuristic
     >> python pacman.py -l tinyCorners -p SearchAgent -a fn=bfs,prob=CornersProblem
     >> python pacman.py -l mediumCorners -p SearchAgent -a fn=bfs,prob=CornersProblem
     >> python pacman.py -l mediumCorners -p AStarCornersAgent -z 0.5
     >> python pacman.py -l testSearch -p AStarFoodSearchAgent
     >> python pacman.py -l bigSearch -p ClosestDotSearchAgent -z .5 
