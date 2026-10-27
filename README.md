# Courier Bidding System

A console-based courier management system built using C/C++ and Data Structures & Algorithms (DSA). The project connects users who need deliveries with courier agents through a bidding mechanism, helping identify cost-effective delivery options and organize delivery requests.

## Features

- **Courier Request Management:** Allows users to create delivery requests that are organized and processed using a FIFO queue.
- **Agent Registration:** Supports courier agent registration and authentication.
- **Competitive Bidding System:** Enables agents to bid on delivery requests and uses data structures to identify the lowest bid.
- **Route Optimization:** Uses graph-based pathfinding to help determine efficient delivery routes.
- **File-Based Data Persistence:** Stores user information, agent records, and delivery requests in local files.
- **Console-Based Interface:** Provides a command-line interface for interacting with the system.

## Data Structures & Algorithms

The project applies fundamental data structures and algorithms to solve practical courier management problems.

- **Queue (FIFO):** Organizes delivery requests for processing.
- **Min-Heap:** Supports efficient retrieval of the lowest bid.
- **Binary Search Tree (BST):** Organizes data for searching and bid-related operations.
- **Graphs:** Represent routes and support pathfinding.
- **Hashing:** Supports efficient data lookup and management.

## Tech Stack

- **Languages:** C and C++
- **Core Concepts:** Data Structures & Algorithms, graph-based pathfinding, file handling
- **Storage:** Local text files
- **Interface:** Command-line / console

## How It Works

1. Users create courier delivery requests.
2. Requests are stored locally and organized for processing.
3. Registered courier agents submit bids for available deliveries.
4. The system uses its bidding logic to identify the lowest-cost bid.
5. Graph-based pathfinding helps determine efficient routes for deliveries.

## Project Goals

- Improve the organization of courier requests and agent operations.
- Explore cost-based courier allocation through competitive bidding.
- Apply data structures and graph algorithms to a practical problem.
- Reduce manual effort in managing delivery requests.

## Project Type

Academic project focused on Data Structures & Algorithms and systems programming.

## Future Improvements

- Add a graphical or web-based user interface.
- Introduce a database for persistent data management.
- Implement more advanced route optimization algorithms.
- Add delivery status tracking and reporting.
