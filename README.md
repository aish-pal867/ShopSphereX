# ShopSphereX-India Delivery Network & Shopping Management System

\<p align="center">   \<b>A C++ Data Structures and Algorithms Project\</b>   \<br>   Graph Algorithms | Shortest Path | Minimum Spanning Tree | AVL Trees | Linked Lists \</p>

---

## Project Overview

The **India Delivery Network & Shopping Management System** is a C++ application that combines an online shopping and order management system with a graph-based delivery network.

The project uses fundamental Data Structures and Algorithms to manage customer orders, calculate delivery distances, and represent connectivity between different cities and their local areas.

It implements graph algorithms such as **Dijkstra's Shortest Path Algorithm** and **Prim's Minimum Spanning Tree Algorithm**, along with AVL Trees and Linked Lists for efficient order management.

### India Delivery Network Visualization

The following graph represents the connectivity between the warehouse and different delivery cities, with edge weights representing distances in kilometres.



---

## Key Features

- **Product Catalogue:** Displays available products and their prices.
- **Takeaway Order Management:** Places, searches, retrieves and deletes takeaway orders.
- **Home Delivery Management:** Maintains customer delivery orders using a Linked List.
- **Shortest Path Calculation:** Uses Dijkstra's Algorithm to calculate shortest delivery distances from the warehouse.
- **Minimum Spanning Tree:** Uses Prim's Algorithm to identify minimum-cost connectivity between local areas.
- **Dynamic Order Management:** Uses an AVL Tree to maintain balanced order records.
- **Delivery Charge Calculation:** Calculates delivery charges based on distance.

---

## Data Structures & Algorithms Implemented

| Concept              | Application                                                    |
| -------------------- | -------------------------------------------------------------- |
| Adjacency Matrix     | Represents the India delivery network and regional graphs      |
| Dijkstra's Algorithm | Calculates shortest distances from the warehouse               |
| Prim's Algorithm     | Finds minimum spanning trees for regional networks             |
| AVL Tree             | Manages takeaway orders using order IDs                        |
| Linked List          | Maintains home delivery customer records                       |
| Tree Rotations       | Maintains AVL tree balance through LL, RR, LR and RL rotations |

---

## 1. Graph Representation – Adjacency Matrix

The delivery network is represented using an adjacency matrix, where each vertex represents a city and each non-zero edge weight represents the distance between connected cities.

<img width="1018" height="608" alt="11" src="https://github.com/user-attachments/assets/abb5851a-8711-4c26-a754-a1b2ba95794c" />


## 2. Shortest Path – Dijkstra's Algorithm

Dijkstra's Algorithm calculates the shortest distance from the central warehouse to different delivery cities.

The warehouse acts as the source vertex, and the algorithm determines the minimum distance required to reach each destination.

<img width="780" height="608" alt="33" src="https://github.com/user-attachments/assets/223b7502-5178-4236-a597-0677f1cb2b85" />


## 3. Minimum Spanning Tree – Prim's Algorithm

Prim's Algorithm is implemented to find a Minimum Spanning Tree (MST) for regional delivery networks.

It connects all vertices with minimum total edge weight without forming cycles.

<img width="780" height="397" alt="22" src="https://github.com/user-attachments/assets/c2b86ad8-634c-4375-824d-67a189603ee6" />


The algorithm is implemented for the Delhi, Chandigarh, Mumbai and Shimla regional networks.

### Example: Delhi Regional Network

<img width="1170" height="845" alt="66" src="https://github.com/user-attachments/assets/829e4365-ed9a-4471-b03b-e19c8b8e65c6" />


---

## 4. Regional Delivery Network Visualizations

The project also represents connectivity between different local areas within selected cities.

### Delhi Delivery Network

<img width="1170" height="845" alt="66" src="https://github.com/user-attachments/assets/12e5722c-f760-4fea-a95a-a8281697c65f" />


### Chandigarh Delivery Network

<img width="1170" height="845" alt="77" src="https://github.com/user-attachments/assets/0a56c3a4-f978-421c-900f-497011a7f0b9" />


### Mumbai Delivery Network

<img width="1170" height="845" alt="88" src="https://github.com/user-attachments/assets/8f73d7fe-885a-4a08-b24d-2278167254b6" />


### Shimla Delivery Network

<img width="1170" height="845" alt="99" src="https://github.com/user-attachments/assets/44f2e376-6904-4566-8c09-2a12949c4807" />


---

## 5. Product Catalogue & Shopping System

The application provides a product catalogue containing different camera models and their original prices.

Customers can select products, specify quantities and place takeaway or home delivery orders.

<img width="1045" height="608" alt="44" src="https://github.com/user-attachments/assets/c4158c0b-a696-4856-b124-ab9fb30f5f70" />


---

## Technologies Used

- **Programming Language:** C++
- **Core Concepts:** Data Structures and Algorithms
- **Graph Representation:** Adjacency Matrix
- **Graph Algorithms:** Dijkstra's and Prim's Algorithms
- **Tree Structure:** AVL Tree
- **Linear Data Structure:** Singly Linked List
- **Compiler:** GCC / G++

---

## How to Run the Project

### Prerequisites

- GCC or G++ compiler
- Visual Studio Code, Code::Blocks or any C++ IDE

### Steps

**1. Clone the repository**

```bash
git clone https://github.com/YOUR-USERNAME/India-Delivery-Network.git
```

**2. Navigate to the project directory**

```bash
cd India-Delivery-Network
```

**3. Compile the source code**

```bash
g++ -std=c++17 project.cpp -o project
```

**4. Run the application**

Linux / macOS:

```bash
./project
```

Windows:

```bash
project.exe
```

---

## Project Structure

```text
India-Delivery-Network/
│
├── images/
│   ├── 11.png
│   ├── 22.png
│   ├── 33.png
│   ├── 44.png
│   ├── 55.png
│   ├── 66.png
│   ├── 77.png
│   ├── 88.png
│   └── 99.png
│
├── project.cpp
└── README.md
```

---

## Learning Outcomes

Through this project, I gained practical experience in:

- Implementing graph-based algorithms for network analysis.
- Understanding shortest path and minimum spanning tree problems.
- Applying AVL Trees for balanced order management.
- Managing dynamic records using Linked Lists.
- Combining multiple data structures and algorithms into a single application.
- Developing a menu-driven C++ application.

---

## Author

**Your Name**

C++ | Data Structures & Algorithms | Graph Algorithms

---

*This project was developed as part of a Data Structures and Algorithms semester project.*
