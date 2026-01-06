# SCOOTER ORCHESTRATOR

GoMi is a scooter orchestrator concept that would enable the citizens to move freely and environmentally friendly to their destinations. It will as well  provide City administrators the intelligence and real time traffic data on the city streets, reduce the carbon footprint and effectively enforce scooter zoning regulations.

## SYSTEM ARCHITECTURE

### Context

The Municipal scooter service system allows citizens to order and use scooters located at various designated parking spots. Users can engage with the system via a smartphone application to order, view location of scooters, manage and track their rides and make payments.

Municipality scooter team and on-site technicians utilize specialized interfaces and mobile devices to handle requests, manage the scooter fleet and perform operational duties.

![](https://github.com/AllanMogley/17-IT-Project-Management/blob/main/Context%20Diagram.png?raw=true)

### Components

The system employs a microservices architecture where each component operates as an independent microservice, operating within containers on the Amazon Web Services (AWS) platform and overseen by Kubernetes orchestration.

This design facilitates autonomous updating and scaling of individual services including functions like request handling, fleet management, notifications and user processes.

![](https://github.com/AllanMogley/17-IT-Project-Management/blob/main/System%20Components%20Architecture.png?raw=true)

## SECURITY FRAMEWORK

Security in the smart city micro-mobility context is a broad area, with three separate vectors, including the physical hardware (IoT scooters), the mobile apps (citizen data), and the cloud infrastructures (city administration). Failure in this ecosystem may not only lead to financial loss or theft of data but also physical safety hazards to the citizens who are using the vehicles.

The system combines a threat modeling approach called STRIDE to systematically find vulnerabilities and provides details on the precise cryptographic and architectural controls it takes to secure the platform.

 

![](https://github.com/AllanMogley/17-IT-Project-Management/blob/main/Security%20framework.png?raw=true)