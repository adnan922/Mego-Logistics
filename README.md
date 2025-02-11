# Mego Logistics: Nationwide Delivery Route Optimization

## Introduction
Mego Logistics is a leading logistics company specializing in delivering high-quality clothing shipments across India. The company operates from its central warehouse at Mumbai Dock, Maharashtra, ensuring seamless distribution to 28 state capitals and 8 Union Territories.

This project aims to optimize the delivery route for a single vehicle, starting from Mumbai Dock, traveling across India, delivering shipments tailored to each region, and returning to Mumbai Dock. The goal is to minimize travel distance while maintaining efficient delivery schedules.

Each destination receives shipments suited to its climate, culture, and customer preferences, ensuring a region-specific approach to logistics.

## Objective
The key objectives of this project are:
- **Comprehensive Coverage**: Ensure all 28 state capitals and 8 Union Territories are covered efficiently.
- **Tailored Deliveries**: Deliver clothing items based on each region’s cultural and climatic needs.
- **Route Optimization**: Identify the shortest and most efficient route.
- **Efficient Resource Utilization**: Maximize the truck’s productivity by completing all deliveries in one loop.
- **Accurate Execution**: Ensure precision in loading, delivery, and tracking to avoid errors and delays.

## How the Logistics Work
1. **Central Loading**: The truck is loaded at Mumbai Dock with shipments for all destinations.
2. **Route Execution**: The truck travels across India, making stops at every state capital and Union Territory.
3. **Delivery at Each Stop**: Shipments are unloaded with accuracy at each location.
4. **Return to Base**: The truck completes its journey by returning to Mumbai Dock.

## Delivery Points and Tailored Shipments
Each destination receives shipments based on regional preferences, such as:
- **Amaravati, Andhra Pradesh**: Traditional sarees
- **Shimla, Himachal Pradesh**: Heavy-duty winter gear
- **Panaji, Goa**: Summer and beachwear
- **Jaipur, Rajasthan**: Designer lehengas and sarees
- **Chennai, Tamil Nadu**: Light cotton wear

(See the full list in the project documentation.)

## Technology Stack
This project leverages:
- **Python (NumPy, Pandas, Matplotlib)**: Data processing and visualization.
- **Deep Reinforcement Learning (PPO)**: Route optimization.
- **PyTorch**: Model training and evaluation.
- **GPS Tracking**: Real-time vehicle monitoring.

## Implementation Details
### Distance Calculation
The **Haversine formula** is used to calculate the shortest path between destinations, ensuring route efficiency.

### Deep Reinforcement Learning
A **Proximal Policy Optimization (PPO)** algorithm is trained to:
- Optimize route selection.
- Minimize travel distance.
- Avoid unnecessary detours.

### Visualization
The optimized route is plotted using **Matplotlib**, displaying the shortest and most efficient delivery path.

## Team Roles and Responsibilities
- **Route Planning Team**: Designs the optimal route.
- **Shipment Allocation Team**: Ensures accurate loading and unloading.
- **Documentation Team**: Maintains records and reports.

## Conclusion
This project enhances Mego Logistics’ operational efficiency by ensuring faster, cost-effective, and accurate deliveries across India. Using advanced route optimization and deep learning, the project streamlines the supply chain while meeting diverse customer needs.

**Efficient, Accurate, and Optimized Logistics for India!**

