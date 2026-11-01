# Network Topology Visualizer

## Description

Network Topology Visualizer is a beginner-level Computer Networks project developed using Python and Flask.

It is a web-based application that visually represents different network topologies, including Star, Bus, Ring, and Mesh.

## Features

- Visualize Star topology.
- Visualize Bus topology.
- Visualize Ring topology.
- Visualize Mesh topology.
- Display network devices and connections.
- Select different topologies using a dropdown menu.
- Simple and interactive dashboard.

## Technologies Used

- Python
- Flask
- HTML
- CSS
- JavaScript
- SVG

## Project Structure

```text id="v8t2ka"
NetworkTopologyVisualizer/
│
├── app.py
├── requirements.txt
├── README.md
├── .gitignore
│
├── templates/
│   └── index.html
│
└── static/
    └── style.css
```

## Installation and Setup

### Step 1: Clone the Repository

```bash id="qkq4bw"
git clone https://github.com/YOUR_USERNAME/Network-Topology-Visualizer.git
```

### Step 2: Open the Project Folder

```bash id="qkq4bw2"
cd Network-Topology-Visualizer
```

### Step 3: Create a Virtual Environment

```bash id="qkq4bw3"
python -m venv venv
```

### Step 4: Activate the Virtual Environment

```powershell id="qkq4bw4"
venv\Scripts\Activate
```

### Step 5: Install Dependencies

```bash id="qkq4bw5"
pip install -r requirements.txt
```

### Step 6: Run the Application

```bash id="qkq4bw6"
python app.py
```

### Step 7: Open in Browser

http://127.0.0.1:5009

## Available Network Topologies

### 1. Star Topology

All computers are connected to a central switch.

### 2. Bus Topology

All computers share a common communication line.

### 3. Ring Topology

Each computer is connected to two neighboring computers, forming a circular structure.

### 4. Mesh Topology

Each computer is connected directly to the other computers in the network.

## How It Works

1. Open the application in a browser.
2. Select a network topology.
3. JavaScript generates the network diagram using SVG.
4. The diagram displays network devices and their connections.
5. Select another topology to compare network structures.

## Learning Outcomes

- Understand different network topologies.
- Learn network device connections.
- Understand Star, Bus, Ring, and Mesh structures.
- Learn SVG-based visualization.
- Integrate Flask with HTML, CSS, and JavaScript.

## Future Enhancements

- Add Tree topology.
- Add Hybrid topology.
- Allow users to add network devices.
- Display connection information.
- Add interactive network diagrams.

## Disclaimer

This project is developed for educational purposes.

## Author

Computer Science and Engineering Student
