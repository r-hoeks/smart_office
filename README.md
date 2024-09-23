# README: SmartOffice Case - Day in Data, Tilburg University

Welcome to the SmartOffice project by Capgemini, where we aim to enhance the office experience through data collection, processing, and analysis. Using a network of sensors at our headquarters in Utrecht (Leidsche Rijn), we gather data on space and desk occupancy, as well as environmental comfort levels (CO2, temperature, lighting, humidity). This data allows us to make informed decisions that improve office management, sustainability, and operational efficiency.

## Dataset Overview

### Data Collection Categories:
1. **Space Occupancy**: Monitors how meeting rooms and shared office spaces are utilized.
2. **Desk Occupancy**: Tracks the usage of individual workstations.
3. **Comfort Levels**: Monitors temperature, humidity, CO2 levels, lighting, and sound levels in real-time.

### Goals:
Using this data, the focus is on three key challenges:
1. **Space Optimization and Capacity Planning**: Analyze trends in office and meeting room usage to optimize space allocation and efficiency.
2. **Energy Management and Cost Reduction**: Identify opportunities to reduce energy consumption by adjusting lighting, heating, and cooling based on occupancy.
3. **Predictive Maintenance**: Use data to anticipate when office spaces or equipment require cleaning or maintenance, optimizing schedules and reducing costs.

## Case Descriptions

### Case 1: Space Optimization and Capacity Planning
- **Problem**: Inefficient use of office and meeting spaces, with underutilization of workspaces and overbooking of meeting rooms.
- **Goal**: Develop strategies for better space allocation by analyzing occupancy trends and redistributing spaces based on real-time data.

### Case 2: Energy Management and Cost Reduction
- **Problem**: Energy waste due to lighting, heating, or cooling unoccupied spaces.
- **Goal**: Automate energy controls and predict peak usage times to optimize energy consumption and reduce costs.

### Case 3: Predictive Maintenance
- **Problem**: Inefficient cleaning and maintenance schedules that don’t align with actual space usage.
- **Goal**: Use sensor data to predict when maintenance is needed, ensuring timely interventions and minimizing disruptions.

## Variable Explanation
Here is a summary of the key variables in the dataset:

- **building**: Name of the building where the sensors are located.
- **building_id**: Unique identifier for the building.
- **floorIndex**: Floor level where the sensor is installed.
- **poiType**: Type of sensor; includes occupancy for desks, rooms, and environmental comfort levels.
- **poiTypeId**: Unique identifier for each point of interest (POI).
- **poiName**: The name of the POI.
- **poiTitleEn**: Room number for the POI.
- **capacity**: Maximum capacity of the room.
- **x, y**: Coordinates of the POI on the floor plan.
- **sensor**: Identifier for the sensor monitoring the POI.
- **sensorCnt**: Number of sensors connected to the POI.
- **time**: Timestamp when the data was collected.
- **deviceName**: Identifier for the sensor.
- **fCnt**: Counter to verify sensor functionality.
- **occupied**: Indicates occupancy status (0 for unoccupied, 1 for occupied).
- **tempC**: Temperature measured in Celsius.
- **humidity**: Relative humidity percentage.
- **co2**: CO2 concentration.
- **sound**: Sound level in decibels.
- **lux**: Lighting level in lux.

## Final Presentation Guidelines
For your final presentation, please address the following:
1. **What did you investigate?**
2. **What are your recommendations?**
3. **What data supports your recommendations?**

Good luck, and we look forward to your insights and contributions!
