# Portfolio
---
## Monitoring, Controlling and Cost Management of Energy, Water and Gas consumption

### IoT Solution by LoRaWAN for [***McDonald’s restaurants***](https://www.mcdonalds.ro/restaurante)

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/arifulmrislam/McDonalds-Project)

<div style="text-align: justify">Since last year, we have been working on a proof of concept. It was offered to McDonald's that they reduce their energy consumption. In addition, they consume other resources such as water, gas, etc. In one of their restaurants, we installed the LoRaWAN network. As a first step, we used five Eastron energy meters to collect energy-related data and observe the average consumption over twenty-four hours. By setting a threshold, if the energy consumption exceeds the limit, a mail notification will be sent if the consumption exceeds the limit. Customers will be informed about their unnecessary consumption by receiving this notification. By doing this, they can save 15% to 20% on their total energy costs. We use Thingsboard as a platform for the Internet of Things and LoRaWAN as a technology for sensor communications. In this year, they approved our proof of concept, and we are now working with their other restaurants in Romania</div>
<br>
<center><img src= "images/Mcdonalds dashboard.png"/></center>
<br>

---
### Textile Medicale Project

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/arifulmrislam/Project-of-Textile-Medicale/tree/main)

<div style="text-align: justify">A full-stack IoT solution bridging hardware and cloud to monitor environmental and electrical parameters in real time. At the edge, Node-RED retrieves telemetry (via Modbus RTU) from sensors and energy meters. That data flows through a MikroTik gateway into a ThingsBoard Edge instance—securely synchronized with a ThingsBoard Cloud backend. In the cloud dashboard, I build visualizations, alerts, and device groups for easy monitoring and control.

Below is the system architecture that illustrates data flow from device to dashboard:
</div>
<br>
<center><img src="https://github.com/arifulmrislam/Project-of-Textile-Medicale/blob/main/IMG/project-of-Textile-Medicale.png"/></center>
<br>

---
### Datalogging with ChirpStack, Node-RED, InfluxDB, Grafana using Docker Container

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/arifulmrislam/Datalogging-with-ChirpStack-Node-RED-InfluxDB-Grafana-with-Docker)

<div style="text-align: justify">Rather than relying on cloud computing, I build a local solution for our customers. My first step was to install ChirpStack network server, Node-RED, Influx DB & Grafana as Docker containers on the Dell server. InfluxDB is used to create a database. I connect the Grafana web application to this database, which is an open-source analytics and monitoring solution. The ChirpStack network server receives all sensor values through a Microtik gateway. Through a topic provided by ChirpStack, Node-RED collects data from NS. I forward those values to the InfluxDB database after collecting them. I built a simple web dashboard in Grafana to visualize the values in graphs, charts, and alerts for critical situations using these data.</div>
<br>
<center><img src="images/Node-Red, Grafana, Docker and Telegraf with Influxdb.png"/></center>
<br>

---
### Advantech LoRaWAN WISE-6610 gateway and WISE-2410 wireless condition monitoring sensor solution

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/arifulmrislam/Advantech-LoRaWAN-WISE-6610-gateway-and-WISE-2410-wireless-condition-monitoring-sensor-solution)

<div style="text-align: justify">To perform predictive maintenance, I used WISE-2410 to transmit sensor data to WISE-6610 (via LoRaWAN) or a 3rd party LoRaWAN gateway (via LoRaWAN). In addition to Ethernet connectivity, the WISE-6610 supports Modbus TCP and RESTful Web APIs for integration. With the WISE-6610, VPN tunnels can be created using a variety of protocols that ensure safe communication. A network server encrypts and converts LoRaWAN data in the device, while its redundancy-enhanced functions prevent loss of connections. An application server is built into it. With the help of this application server, I built a dashboard in Node-RED to visualize the WISE-2410 values.</div>
<br>
<center><img src="images/System Architecture.png"></center>

<center><img src="images/Dashboard.png"></center>
<br>

---
## DataBase

### Deploy PostgreSQL fully manageable database for Thingboard

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/arifulmrislam/Deploy-PostgreSQL-fully-manageable-database-for-Thingboard)

<div style="text-align: justify">ThingsBoard uses the database to store entities (devices, assets, customers, dashboards, etc) and telemetry data (attributes, timeseries sensor readings, statistics, events). In this project, I am preparing to deploy a PostgreSQL fully managed database. PostgreSQL is a free and open-source object-relation database management system (ORDBMS). ThingsBoard customers successfully use Azure Database for PostgreSQL to minimize efforts on database setup, backups and support.</div>
<br>
<center><img src="images/standalone.png"/></center>
<br>

---
### TEMPERATURE-MEASUREMENT-OF-SHEET-PACKAGES-AT-AXLE-ASSEMBLY

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/arifulmrislam/TEMPERATURE-MEASUREMENT-OF-SHEET-PACKAGES-AT-AXLE-ASSEMBLY)

<div style="text-align: justify">We have done a temperature measurement project for Cummins Generator Technologies Romania SA. During this project, we need to read the temperature range of the electric rotor between 100 °C and 200 °C. We use two sensors one is the position/distance sensor, and another one is the temperature sensor. When each rotor passes through the rays of the position/distance sensor, the temperature is checked. The green lamp illuminates when the temperature level is in the set range. In addition, the PLC logs data while the HMI shows the values.</div>
<br>
<center><img src="images/Picture1.png"> <img src="images/Picture2.jpg"></center>
<br>
  
--- 
## Filmed by me

[![View My Films](https://img.shields.io/badge/YouTube-View_My_Films-grey?logo=youtube&labelColor=FF0000)](https://www.youtube.com/channel/UCED68cm6nHaAlAk0h9I3yAQ)

<div style="text-align: justify">Beside Engineering, I have a great passion for photography and videography. Below is a list of the videos I have created for sharing my knowledge.</div>
<br>

- [How to install Node-RED on Ubuntu 20.04 with username and password authentication??](https://www.youtube.com/watch?v=Y2ttfN9mOyQ&t=10s)
- [Enable SSH on Ubuntu 20.04 step-by-step instruction and connect by Putty.](https://www.youtube.com/watch?v=_Rt7UzRbeV8)

---
<center>© 2025 Ariful Islam Arif.</center>
