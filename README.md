# SentinelWatch

SentinelWatch is a real-time file integrity monitoring solution designed to continuously track file changes, monitor system health, and alert users to potential security risks or performance issues. Developed by a team of three students from the University of the District of Columbia's Department of Computer Science and Information Technology, this project aims to offer a comprehensive approach to file security and system monitoring.

## Key Features

- **Real-Time File Integrity Monitoring**: Uses the Watchdog library to monitor directory changes and checks file integrity using SHA-256 hashing.
- **Z-Score Based File Analytics**: Analyzes file sizes to detect anomalies that may indicate security issues.
- **Real-Time Alerts**: Generates alerts for hash changes or anomalous file sizes, displayed in real-time on the dashboard.
- **System Health Monitoring**: Tracks CPU usage, memory consumption, and disk I/O using the psutil library.
- **File Activity Analytics**: Categorizes files and tracks their activity to provide insights into file usage patterns.
- **User-Friendly Dashboard**: Provides a dynamic and accessible interface for real-time monitoring data.

## Technology Stack

- **Backend**: Python, Flask
- **Libraries**: Watchdog, psutil
- **Frontend**: HTML, CSS, JavaScript, AJAX


## Usage

- Specify the directory to monitor in the configuration file.
- Start the application to begin real-time monitoring.
- View system health metrics and file activity in the dashboard.
- Respond to alerts for file integrity issues or system performance concerns.

## Contributions

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## Acknowledgements

- University of the District of Columbia Professor Yu for his reccomendations and support! 
- Open-source libraries: Watchdog, psutil

---

Happy monitoring!

   
   
   
