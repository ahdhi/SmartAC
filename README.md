# Smart Air Conditioning System for Large Buildings

## Project Overview

This project aims to develop a smart, scalable air conditioning solution for large commercial buildings. The solution leverages IoT technologies, real-time data analytics, and cloud computing to optimize energy consumption, enhance occupant comfort, and reduce operational costs.

## Key Features

- **Real-Time Monitoring:** Monitors temperature, humidity, and occupancy in multiple zones.
- **Automated Adjustments:** Automatically adjusts AC settings based on real-time data and predefined rules.
- **Energy Optimization:** Utilizes predictive algorithms and machine learning for energy consumption optimization.
- **Remote Control:** Provides remote monitoring and control capabilities for facility managers.
- **Predictive Maintenance:** Sends alerts to prevent system failures.
- **Scalability:** Designed to accommodate buildings of various sizes and complexities.
- **Security:** Ensures secure data transmission and storage.

## System Architecture
![image](https://github.com/user-attachments/assets/9e4ad4ea-3103-42ed-9cef-61e80e97a198)


## Installation

### Prerequisites

- Node.js
- Node-RED
- AWS Account
- MQTT Broker

### Steps

1. **Clone the Repository:**
    ```bash
    git clone https://github.com/yourusername/smart-ac-system.git
    cd smart-ac-system
    ```

2. **Install Dependencies:**
    ```bash
    npm install
    ```

3. **Setup Node-RED:**
    - Install Node-RED globally:
      ```bash
      npm install -g node-red
      ```
    - Start Node-RED:
      ```bash
      node-red
      ```
    - Import the provided Node-RED flow from `flows/smart_ac_flow.json`.

4. **Configure AWS Services:**
    - Set up AWS IoT Core for device management and MQTT communication.
    - Deploy AWS Lambda functions for data processing.
    - Set up AWS Timestream for time-series data storage.
    - Configure AWS DynamoDB for configuration data.
    - Use AWS S3 for storing aggregated analytics data.

5. **Run the Application:**
    ```bash
    npm start
    ```

## Usage

1. **Monitoring Dashboard:**
    - Access the Node-RED dashboard to monitor real-time data from sensors.
    - View temperature, humidity, and occupancy metrics.

2. **Control Panel:**
    - Use the control panel to adjust AC settings manually if needed.
    - Configure rules for automated adjustments based on real-time data.

3. **Alerts and Notifications:**
    - Receive notifications for predictive maintenance and system alerts.

## Project Documentation

- **Project Plan:** Detailed project plan including system design, architecture, and implementation strategies. (will be uploaded later)

## Contributing

We welcome contributions to enhance the Smart Air Conditioning System. Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Commit your changes (`git commit -m 'Add some feature'`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.
