# Arrowhead Data Management Stack

The Arrowhead Data Management Stack is a collection of tools and services for managing and analyzing data. It includes InfluxDB, Grafana, and Node-RED.

# Installation

To get started, you will need to install Git first in order to clone the repository or download it manually. Use the following command to install Git:

```bash
sudo apt install git
```

Once Git is installed, you can clone the repository using the command:

```
git clone https://github.com/CuAuPro/arrowhead-data-mgmt.git
```


# Usage
Before running the stack, you may need to modify the default passwords and other settings. To do this, navigate to the `docker/` folder and review the `.env` files in each subfolder.

After configuring the necessary settings, you can run the stack using Docker Compose. Execute the following command:

```
docker-compose up -d
```


# Services
The Arrowhead Data Management Stack consists of the following services:

## InfluxDB
InfluxDB is a time-series database designed to handle high write and query loads. It is commonly used for storing and retrieving time-stamped data, making it suitable for monitoring and IoT applications.

## Grafana
Grafana is a powerful open-source platform for data visualization and monitoring. It allows you to create interactive dashboards to visualize data from various sources.

## Node-RED
Node-RED is a flow-based programming tool that enables the wiring together of hardware devices, APIs, and online services. It provides a browser-based interface for building and deploying applications.


# Further Configuration
To further customize and configure each service, please refer to their respective documentation:

 - [Grafana Documentation](https://grafana.com/docs/)
 - [Node-RED Documentation](https://nodered.org/docs/)
 - [InfluxDB Documentation](https://docs.influxdata.com/)

Feel free to explore and experiment with the capabilities of each service to meet your specific data management needs.