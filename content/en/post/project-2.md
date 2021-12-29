---
date: 2021-12-18T11:00:59-04:00  
description: "Implementation of Dijkstra's algorithm from scratch for return the shortest path from source airport to destenation based on user inputs"
featured_image: "images/Projects/project2.png"
tags: []
title: "Project 2: Airport Agenda using Dijkstra's algorithm"
---
# Abstract

Reserving air flights can be a complex problem, especially between cities not connected by a direct flight. The goal of this project is to apply Dijkstra’s Algorithm to find the shortest path from starting airport to destination airport, such that minimizes the total travel distance to its destination.

# Tools

* Python json library.
* Python math library.
* Python system library.
* Python pandas library.
* Spyder IDE.

# Dataset
We are given a [json](https://github.com/heba14101998/Airport-Agenda-using-Dijkstra-s-algorithm/blob/main/Airports.json) file contains a list of airports with some geo-information like city, country and location (longitude, latitude) , airport id as well as airport specific designations (a list of destination airports) as shown below:

{{< figure src="/images/Projects/Project2 dataset.png" title="" >}}

# Delivables
## Application ([main.py](https://github.com/heba14101998/Airport-Agenda-using-Dijkstra-s-algorithm/blob/main/main.py))
1. Take inputs from user and avoiding user error as shown
{{< figure src="/images/Projects/Project2 inputs.png" title="" >}}

2. Read and parse the json file.
3. Calling the immplemednted algorithm from its medule
4. Print airport agenda to user as shown:. 
{{< figure src="/images/Projects/Project2 outputs.png" title="" >}}


## Implementation Steps ([dijkstrs.py](https://github.com/heba14101998/Airport-Agenda-using-Dijkstra-s-algorithm/blob/main/dijkstra.py))
1. Create a class called _𝑨𝒊𝒓𝒑𝒐𝒓𝒕_ takes the information of airport (𝐴𝑖𝑟𝑝𝑜𝑟𝑡 𝐼𝐷 𝐿𝑜𝑛𝑔𝑖𝑡𝑢𝑑𝑒, 𝐿𝑎𝑡𝑖𝑡𝑢𝑑𝑒, 𝐷𝑒𝑠𝑡𝑖𝑛𝑎𝑡𝑖𝑜𝑛𝑠) as arguments of its constructor.
2. Create _𝑫𝒊𝒋𝒌𝒔𝒕𝒓𝒂_ class that manages the whole process (e.g. it contains all the Airports in a list etc.,). Moreover, this class contains a function called 𝑓𝑖𝑛𝑑_𝑡ℎ𝑒_𝑠ℎ𝑜𝑟𝑡𝑒𝑠𝑡_𝑝𝑎𝑡ℎ(𝑠𝑜𝑢𝑟𝑐𝑒, 𝑑𝑒𝑠𝑖𝑛𝑡𝑎𝑡𝑖𝑜𝑛)
	- I apply Euclidean distance formula as follows:
{{< figure src="/images/Projects/ED.png" title="" >}}

3. Store the distance between each airport with their destinations in Airport class.
4. Some airports are not existing so that I create a function in _**Graph**_ class to delete any missing airport ID from airport destination

# More Resouces

* For more details see the project [repository](https://github.com/heba14101998/Airport-Agenda-using-Dijkstra-s-algorithm) on github.

* Helpful link for [Dijkstrs](https://datascience.lc/2019/10/26/shortest-path-dijkstra-algorithm/) Algorithm.
