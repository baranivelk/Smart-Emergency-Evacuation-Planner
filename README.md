# Smart-Emergency-Evacuation-Planner
 EvacuSafe is a smart evacuation planning and simulation project that uses dynamic route planning, traffic congestion analysis, and shelter-capacity management to improve emergency evacuation efficiency and fairness.
EvacuSafe 🚦

Evacuate Faster. Evacuate Fairly. Replan Live.

EvacuSafe is a simulation-based evacuation planning prototype designed to explore how people can be evacuated more efficiently during emergencies using road-network routing, shelter-capacity constraints, and dynamic replanning.

🎯 Problem Statement

Traditional evacuation plans may struggle when multiple vehicles use the same roads, shelters reach capacity, or traffic conditions change during an emergency.

EvacuSafe explores a smarter approach: plan evacuation routes while considering traffic congestion, shelter capacity, and changing conditions.

💡 Proposed Solution

EvacuSafe combines evacuation staging, capacity-aware route selection, shelter assignment, and dynamic replanning into a unified simulation workflow.

✨ Key Features

- Staged Departures: Organizes departures into zones to reduce traffic congestion.
- Capacity-Aware Routing: Selects routes while considering road congestion and travel time.
- Shelter Capacity Management: Considers shelter limits when assigning evacuees.
- Dynamic Replanning: Updates routes and assignments as simulated conditions change.
- Fairness-Aware Planning: Explores fairer evacuation outcomes across zones and vulnerable groups.
- Baseline Comparison: Compares a baseline evacuation scenario against the proposed planning approach.
- 3D Simulation Visualization: Illustrates vehicle movement, congestion, and shelter activity.

📊 Demonstration

The current demo presents a synthetic evacuation scenario with illustrative performance comparisons, including:

- A reported 32% reduction in clearance time.
- A reported 40% reduction in average evacuation time.
- A change in peak shelter load from 213% to 100%.

Note: These figures are specific to the illustrative simulation shown in the demo. They are not validated real-world performance results and should be independently reproduced and verified.

🧠 How It Works

1. Stage: Divide the evacuation area into zones.
2. Route: Select routes based on congestion and travel-time estimates.
3. Assign: Allocate evacuees to shelters while considering capacity.
4. Replan: Update routes and assignments when simulated conditions change.
5. Evaluate: Compare evacuation time, clearance time, congestion, and shelter utilization against a baseline.

🎥 Demo Video

See ""docs/demo.mp4"" (docs/demo.mp4) for the project walkthrough.

🛠️ Technology Stack

The final technology stack and implementation details will be documented as the prototype develops.

🚀 Future Improvements

- Integration with realistic road-network datasets.
- More detailed traffic and pedestrian-flow models.
- Emergency-event and road-closure scenarios.
- Reproducible benchmarks and automated testing.
- Live data integration, where reliable data sources are available.
- Evaluation of evacuation fairness and accessibility.

⚠️ Disclaimer

EvacuSafe is an experimental simulation prototype intended for research and educational purposes. It is not a certified emergency-management system and should not be used for real-world evacuation decisions without extensive validation.

🤝 Contributions

Contributions, feedback, and suggestions are welcome.

📄 License

A license will be selected before public reuse and distribution.
