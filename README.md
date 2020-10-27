# TNCITTASK
1)-Travel Route
A tourist wants to travel the world at the lowest possible price regardless of the number of connections required. We are going to build a program that makes it easier for our tourists to choose the best route for their trip.

For this we need to insert the routes through an input file.

Input Example
GRU, BRC, 10
BRC, SCL, 5
GRU, CDG, 75
GRU, SCL, 20
GRU, ORL, 56
ENT, CDG, 5
SCL, ORL, 20
Explaining ##
If you want to travel from GRU to CDG there are the following routes:

GRU - BRC - SCL - ORL - CDG at a cost of $ 40
GRU - ORL - CGD at a cost of $ 64
GRU - CDG at a cost of $ 75
GRU - SCL - ORL - CDG at a cost of $ 45
The best price is from route 1, so the query output should be GRU - BRC - SCL - ORL - CDG.

Program execution
The test will be started by command line where the first argument is the file with the initial route list.

$ mysolution input-routes.csv
Two query interfaces must be implemented: - API interface must receive an input with the route in the "FROM-TO" format and print the best route and its respective value. Example:

please enter the route: GRU-CGD
best route: GRU - BRC - SCL - ORL - CDG> $ 40
please enter the route: BRC-CDG
best route: BRC - ORL> $ 30
Rest interface The Rest interface must support:
Registration of new routes. These new routes must be persisted in the csv file used as input (input-routes.csv),
Consultation of the best route between two points.
It will also be necessary to implement 2 Rest API endpoints, one for registering routes and another to find the best route.

2)- Make a socket which keep on updating in channel the new routes which is entered by the different users it will be public socket where user can see the new routes and there prices socket should keep on emitting any new entries of routes but user can ask the system to show the best possible route .
For Example:
New route added :
KLM-FGW $60

Recommended)-
-Impementation of Redis 
-Python framework Flask and Flask library Socket.io

Recommendations
For a better fluids of our conversation, pay attention to the following points:

Send only the source code,
Structure your application following good development practices,
Implement unit tests following good market practices,
Documentation In a Text or Markdown file describe:
How to run the application,
Structure of files / packages,
Explain the design decisions made for the solution,
Describe your APÌ Rest in a simplified way.
