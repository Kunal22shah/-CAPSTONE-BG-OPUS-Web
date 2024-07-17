# CAPSTONE-BG-OPUS-Web
# OPUS Web
The OPUS Web project is a full-stack web enterprise resource planning (ERP) application designed for the translation services market. This project is a [BG Communications](https://bgcommunications.ca/) initiative to replace their existing desktop application originally conceived in 2014. This internal application allows customer relations management, HR management, and project management, per the company’s workflow.

## Technology Stack
[NextJS](https://nextjs.org) - React Framework<br/>
[Spring Boot](https://spring.io/projects/spring-boot) - Java Spring Application Framework<br/>
[Docker](https://docker.com) - Containerization platform<br/>
[Tailwind CSS](https://tailwindcss.com/) - Utility CSS Framework<br/>
[MS SQL Server](https://www.microsoft.com/en-us/sql-server/) - SQL Server from Microsoft


Joe El-Khoury<br/>
Ali Alp Erdinc<br/>
Kunal H. Shah<br/>
Titouan Sablé<br/>
Meet Vora<br/>
Rohan Das<br/>
Hadi Hawi<br/>
Antoine Turcotte<br/>
Haytham Hnine<br/>
<br/>
![image](https://github.com/user-attachments/assets/ad692110-1aaf-4dec-94ca-0e5754019c12 )

## Top Features of the Opus Web Application
- **Multi-Platform Support**: The application seamlessly integrates both web and desktop environments, ensuring a consistent user experience across various platforms.

- **Robust Authentication and Authorization**: Utilizes Microsoft Azure Active Directory for secure authentication and authorization, ensuring that only authorized users can access sensitive data and functionalities.

- **Advanced Data Handling**: Features a sophisticated data management system capable of handling complex CRUD (Create, Read, Update, Delete) operations across two databases, ensuring data consistency and reliability.

- **Real-Time Data Synchronization**: Implements real-time data synchronization between the legacy database system and the new database, minimizing data latency and integrity issues.

- **Incremental Data Migration Strategy**: Employs an incremental migration strategy that allows for the gradual transition of data from the old database system to the new system without disrupting ongoing operations.

- **High Availability and Scalability**: Deployed on a scalable cloud infrastructure that ensures high availability and enhances performance across different geographic locations.

- **Secure Data Connections**: Uses VPNs and secure protocols to ensure that data transmissions between different components of the system are secure from unauthorized access.

- **Comprehensive Monitoring and Logging**: Integrates with tools like Prometheus and Grafana for monitoring system performance and health, alongside Loki for centralized logging, allowing for effective troubleshooting and maintenance.

- **Feature Toggling**: Incorporates feature toggling through FF4j, enabling selective enabling or disabling of application features without deploying new code, facilitating easy A/B testing and phased feature rollouts.
