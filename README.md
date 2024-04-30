[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/kzkUPShx)
# a14g-final-submission

    * Team Number: 6
    * Team Name: Logic Ninjas
    * Team Members: Vishnu Venkatesh and Yadnik Bendale
    * Github Repository URL: https://github.com/ese5160/ec01g-mcad-model-t06-logic-ninjas/tree/main
    * Description of test hardware: PCBA, SAMW25


## 1. Video Presentation

Link to video presentation of video: 

## 2. Project Summary

### Device Description
- **Problem Solved**: Briefly describe the problem that your device addresses.
- **Internet Usage**: Explain how you use the Internet to enhance the functionality of your device.

### Inspiration
- **Motivation**: Share what inspired you to initiate this project.

### Device Functionality
- **Design Overview**: Describe how your Internet-connected device is designed. Mention sensors, actuators, and other critical components.
- **Block Diagram**: Include your block diagram to illustrate the setup.

### Challenges
- **Difficulties Encountered**: List the main challenges you faced during the development (firmware, hardware, software, integration).
- **Solutions**: Describe how you overcame these challenges.

### Prototype Learnings
- **Lessons Learned**: Highlight the key lessons learned during the building and testing of your prototype.
- **Improvements**: If you were to build this device again, what would you do differently?

### Next Steps
- **Future Improvements**: Discuss what steps are needed to finish or improve your project.

### Takeaways from ESE5160
- **Course Learnings**: Detail what you learned through the lectures, assignments, and the course-long prototyping project in ESE5160.

### Project Links
- **Node-RED URL**: Provide the URL to your Node-RED instance running on your Azure instance.
- **A12G Repository Link**: Include a link to your A12G code repository. Do not include your code in the A14G assignment's repository.
- **Altium 365 PCBA Link**: Provide the share link to your final PCBA on Altium 365.

### Open Source and Acknowledgements
- **Open Source Use**: Mention any open source code used in your project and ensure it's referenced according to its licensing.
- **Acknowledgements**: Note any tools, websites, or expertise that heavily contributed to your project. Include these in your GitHub Readme.

## 3. Hardware & Software Requirements
#### Hardware Requirements:
HRS 01: The device shall incorporate an external ADC with a sampling frequency exceeding 800kHz, enabling precise and high-resolution data capture.
HRS 02: The device shall ensure at least a single sample per bit for each protocol, with capabilities for multiple samples per bit to adapt to various protocol speeds and baud rates.
HRS 03: The device shall be designed to process the captured signals and transmit this processed data wirelessly to a designated web server, enabling remote data analysis and review.
HRS 04: The device shall feature a user-friendly push button interface for selecting the communication protocol. Each button starts the sampling process and indicates the active protocol via its LED, ensuring clear user feedback.
HRS 05: Integration of a microSD card shall allow for comprehensive data logging for each sampling session, providing a robust data retention solution.
HRS 07: The device shall include a manual power supply switch, granting users direct control over its power state, thereby enhancing usability and energy efficiency.
HRS 08: LED indicators will be incorporated to visually represent various device statuses, such as power on, sampling in progress, and Wi-Fi connectivity status.
HRS 09: The device shall be battery-powered, ensuring portability. An LDO will be utilized to step down the voltage appropriately, maintaining stable operation and prolonging battery life.
HRS 10: The SAMD21 microcontroller shall serve as the cornerstone of the device, handling core processing tasks and wireless communications, ensuring robust and reliable performance.
HRS 11: An integrated real-time clock shall be utilized for precise timestamping of data samples and transactions, crucial for accurate diagnostics and data analysis.
HRS 12: The device's design shall prioritize minimal processing and communication delays, ensuring that the interval from signal sampling to its display on the user interface remains under 2 seconds.


#### Software Requirements:

SRS 01: The firmware shall be developed in bare-metal C, ensuring optimal performance for signal processing, enabling close-to-hardware operations.
SRS 02: An RTOS shall be implemented to efficiently handle multiple concurrent tasks, including sampling, data processing, and communication, ensuring smooth operation and responsiveness.
SRS 03: Algorithms for decoding signals from I2C, SPI, UART, and GPIO protocols shall be incorporated, ensuring the device can interpret various communication standards.
SRS 04: The software shall include a web-based user interface, displaying data in a format that is easy to understand, allowing users to analyze captured signals effectively.
SRS 05: Configurable settings for Wi-Fi credentials, server address, and port numbers shall be provided, ensuring flexibility and adaptability to different network environments.
SRS 06: Error-handling routines shall be included to alert users of any internet connectivity issues or data transmission errors, enhancing the reliability of the device.
SRS 07: OTA update capability shall be supported, allowing the device firmware to be updated remotely, ensuring the device stays current with improvements and bug fixes.
SRS 08: The software shall manage the RTC to provide accurate timestamps for data samples. Microcontroller timers will be used to achieve millisecond precision for interval measurements, crucial for detailed data analysis.

## 4. Project Photos & Screenshots


### Complete Project Showcase
- **Description**: Briefly describe the full setup of your final project, including any casework or interfacing elements like 3D prints, screens, buttons, etc.
- **Images**: Upload images showing the complete setup.

### Standalone PCBA
#### Top View
- **Image**: Upload an image of the top view of your standalone PCBA.

#### Bottom View
- **Image**: Upload an image of the bottom view of your standalone PCBA.

### Thermal Camera Images
- **Description**: Show thermal camera images of the board running under load.
- **Image**: You may use your Board Bringup Thermal image here.

### Altium Board Design
#### 2D View
- **Screenshot**: Include a screenshot of the Altium board design in 2D view.

#### 3D View
- **Screenshot**: Include a screenshot of the Altium board design in 3D view.

### Node-RED
#### Dashboard
- **Screenshot**: Upload a screenshot of your Node-RED dashboard.

#### Backend
- **Screenshot**: Upload a screenshot of your Node-RED backend.

### System Block Diagram
- **Description**: Update and describe the block diagram of your system to reflect any changes made throughout the semester.
- **Diagram**: Upload the updated block diagram.

### Instructions for Viewing
- **Viewing**: Provide instructions or tips for viewing the images and diagrams effectively if needed.

### Additional Notes
- **Notes**: Include any additional notes or comments relevant to the visual documentation of your project.
