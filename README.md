Optimizing Container Transport for Mining Exports

Simulation Study of Chifeng Gold Operations

📌 Overview

This project presents a discrete-event simulation model of a multimodal container transport system for mining exports. The system models the movement of rare earth ore containers from a mine to a final shipping destination via trucks, trains, and ships.

The goal is to evaluate and optimize resource allocation (trucks, cranes, buffer storage) to reliably meet a monthly export target of 2,000 FEU (Forty-foot Equivalent Units).

🎯 Objectives
Simulate a real-world mining logistics supply chain
Model system behavior using discrete-event simulation
Analyze resource constraints and bottlenecks
Optimize allocation of:
Trucks
Container cranes
Buffer storage
Evaluate system performance under variability
Identify a cost-effective and reliable configuration

⚙️ System Components
Entities
Containers (FEU)
Trucks
Container cranes
Trains
Ships
Stages
Mine → Truck transport
Railway terminal → Train transport
Port → Ship transport
Final delivery (Hamburg)

📊 Key Features of the Model

Poisson arrival process for container generation

Exponential service times

Queue-based modeling (M/M/n and M/M/m/B systems)

Event-driven simulation logic

Resource-constrained scheduling

Buffer storage handling

Scheduled departures (trains and ships)


🧪 Simulation Scenarios

The model evaluates performance under:

Minimal variability

Increased variability

Full 30-day operational cycles

📈 Key Results

Optimal configuration:
13 trucks
2 cranes
20 FEU buffer
System reliability: ~99.1%
Monthly throughput: ~97–99% of target
Daily capacity: up to ~105–106 FEU
Stable performance under variability conditions
💡 Insights
Trucks are the primary bottleneck resource
Cranes are sufficiently provisioned at 2 units
Buffer storage provides resilience against variability
System performance plateaus after a certain fleet size
Trade-off exists between cost and reliability

🏗️ Implementation Notes
Simulation follows discrete-event modeling principles
Queueing theory used for system approximation
Resource utilization constraints applied to avoid overloading
Event scheduling used for arrivals, departures, and processing

📁 Suggested Project Structure

/project-root
│
├── data/
├── models/
├── simulation/
├── results/
├── figures/
├── notebooks/
├── README.md
└── requirements.txt

🚀 Future Improvements

Multi-objective optimization (cost + emissions)
Dynamic scheduling algorithms
Real-time adaptive resource allocation
Integration with additional transport routes
Sensitivity analysis with more variables

📚 References

Discrete-event simulation methodologies
Queueing theory (M/M/n, M/M/m/B systems)
Multimodal logistics optimization studies

👤 Author
Vishal Chaudhary


