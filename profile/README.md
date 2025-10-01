# MITAKE.COM.TW - Internet Security Hardware KEY BOX Project
A Next-Generation Gadget for Hardware, Firmware, and Software Integration, providing a real-time solution for monitoring, responding, authenticating, and authorizing.

## It is a comprehensive cybersecurity solution that combines a hardware-based endpoint agent with a powerful central management console, designed to provide multi-layered, in-depth security for your organization.

### - 1.Key Features
- Our solution is divided into two core components: the Endpoint Hardware Agent and the Central Management Console. These components work in synergy to deliver a seamless security experience.

### - 2.🛡️ Endpoint Hardware Agent
- This agent is deployed on user endpoints, leveraging ESP32 hardware as a root of trust to provide enhanced authentication and local monitoring capabilities.

- 1.Hardware-Based Authentication: Utilizes an ESP32 as a security core, offering a more reliable hardware-level foundation for authentication compared to software-only solutions.

- 2.Dynamic PIN Authentication: Implements robust two-factor authentication (2FA) by displaying a dynamic PIN on an OLED screen.

- 3.Local Network Monitoring: Performs real-time packet capture and network traffic analysis to intercept threats at the endpoint before they reach the core network.

- 4.Intelligent Network Control: Features a smart, time-based network blocking mechanism for precise access control.

- 5.Intuitive Desktop Client: Includes an easy-to-use Windows GUI application that interacts with the hardware via a stable USB serial connection.

- 6.USB Token Support: Can function as a hardware security key to enhance login security for various services.

### - ⚙️ Central Management Console
- A modern web application that provides comprehensive monitoring, analysis, and management functions, giving administrators a complete overview of the security landscape.

- Advanced Threat Detection:

- Real-time Attack Prevention: Actively detects and defends against network attacks such as brute-force, DDoS, and malicious port scanning.

- Intrusion Prevention System (IPS): Automatically blocks abnormal connections from malicious IPs or those matching suspicious patterns.

- Machine Learning-Based Behavioral Analysis: Employs machine learning algorithms to analyze user and device behavior, accurately identifying potential insider threats.

- Centralized Monitoring & Visualization:

- High-Performance Metrics: Integrates with Prometheus for system metrics collection and Grafana for rich, customizable visualization dashboards.

- Unified Log Management: Uses Loki for log aggregation, enabling rapid log querying and analysis.

- System Performance Tracking: Monitors system resource utilization, including CPU, memory, and network usage.

### -  Management & Operations:

- Device Status Management: Remotely monitors and manages all deployed IoT security devices.

- Flexible Network Control: Allows administrators to execute network blocking and unblocking policies, either manually or automatically.

- Threat Intelligence Integration: Connects with external threat intelligence feeds to broaden the scope and accuracy of threat detection.

- Multi-Channel Alerting System: Delivers real-time security alerts through various channels, including Email, Slack, and Webhooks.

- Modern Architecture:

- Responsive Web Interface: Built with a modern, responsive design to ensure an optimal user experience across all devices.

Real-time Data Updates: Utilizes WebSocket technology for real-time data push to the frontend.

RESTful API: Provides a standardized RESTful API for easy integration with other systems.

### -  System Architecture
- The system consists of three main components:

- ESP32 Hardware Token: Responsible for generating and displaying the dynamic PIN.

- Windows Agent: An application installed on the user's computer that captures network packets, enforces control policies, and communicates with the hardware via USB.

- Backend Console: Gathers data from all agents, performs analysis, provides visualizations, and serves as the central management interface.

### - Technology Stack
- Hardware: ESP32, OLED Display

- Desktop Agent: Python, BAT Scripts

- Backend: Go, Python, Node.js, Docker/Containers

- Frontend: Next.js

- Monitoring & Logging: Prometheus, Grafana, Loki

- Communication: USB Serial, WebSocket, RESTful API

- Database: PostgreSQL, Redis
