# SyncChain

## Blockchain Simulation for Supply Chain Management

### Description
The system models a multi-tier supply chain network comprising suppliers, processing units, manufacturers,
distributors, and retailers. Each transaction is mined into a block containing cryptographically hashed metadata, ensuring immutability and traceability. The simulator utilizes Dijkstra’s algorithm to compute optimal routing paths based on cost, time, and distance. Network resilience is evaluated using articulation point detection to identify critical nodes whose failure could disrupt the entire supply chain. <br>
A dynamic web interface allows users to upload custom node and edge data in JSON format, view live updates, and analyze transaction flows through interactive visualizations powered by vis.js and Flask-SocketIO. The system provides actionable insights into both performance optimization and structural weaknesses, making it suitable for educational use, logistics planning, and supply network research.

### Resources
* [Draft Paper](https://github.com/angelavarghese/SyncChain/blob/main/draft-paper-syncchain.pdf)

### Preview
![Landing Page](https://raw.githubusercontent.com/angelavarghese/SyncChain/main/current-project/images/landing-page.png)
![Network Visualization](https://raw.githubusercontent.com/angelavarghese/SyncChain/main/current-project/images/network_50node-200edge.png)
![Transactions Page](https://raw.githubusercontent.com/angelavarghese/SyncChain/main/current-project/images/blockchain_50node-200edge.png)


## Setup Instructions

### 1. Clone the Repository
```bash
git clone https://github.com/angelavarghese/SyncChain.git
cd current-project
```

### 2. Create Virtual Environment
#### Windows
```bash
python -m venv venv
venv\Scripts\activate
```
#### Linux or WSL
```bash
python3 -m venv venv
source venv/bin/activate
```

### 3. Install Dependencies
```bash
pip install flask flask_socketio
```

### 4. Run the App
```bash
python app.py
```
OR
```bash
python3 app.py
```
### Go to [App Link](http://localhost:5000/)
