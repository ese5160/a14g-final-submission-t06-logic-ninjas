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


### Hardware Requirements

**HRS 01**: Incorporate an external ADC with a sampling frequency exceeding 800kHz for precise, high-resolution data capture.

**HRS 02**: Ensure at least a single sample per bit for each protocol, with enhanced sampling capabilities for faster protocols to accommodate various speeds and baud rates.

**HRS 03**: Design the device to process captured signals and wirelessly transmit this data to a web server, facilitating remote data analysis.

**HRS 04**: Include a user-friendly push button interface for protocol selection. Each button activates sampling and indicates the active protocol via its corresponding LED.

**HRS 05**: Integrate a microSD card slot for comprehensive data logging of each sampling session, ensuring robust data retention.

**HRS 07**: Equip the device with a manual power supply switch, giving users direct control over its power state and enhancing energy efficiency.

**HRS 08**: Utilize LED indicators to visually signal various device statuses, including power, sampling activity, and Wi-Fi connectivity.

**HRS 09**: Power the device with batteries, incorporating an LDO to ensure stable operation and extend battery life, enhancing portability.

**HRS 10**: Utilize the SAMD21 microcontroller as the processing core, managing core tasks and wireless communication for reliable performance.

**HRS 11**: Integrate a real-time clock for precise timestamping of data samples and transactions, crucial for accurate diagnostics.

**HRS 12**: Minimize processing and communication delays, aiming for data display on the user interface within 2 seconds of sampling.

### Software Requirements

**SRS 01**: Develop firmware in bare-metal C to optimize performance and precision in signal processing.

**SRS 02**: Implement an RTOS to efficiently manage multiple concurrent tasks, including data sampling, processing, and communication.

**SRS 03**: Include algorithms to decode signals from protocols such as I2C, SPI, UART, and GPIO, ensuring broad communication compatibility.

**SRS 04**: Provide a web-based user interface that displays data clearly and intuitively, enabling effective signal analysis.

**SRS 05**: Offer configurable settings for Wi-Fi credentials and server details to accommodate various network environments.

**SRS 06**: Implement error-handling routines to alert users to any internet connectivity or data transmission issues, enhancing device reliability.

**SRS 07**: Support OTA updates, allowing for remote firmware upgrades to keep the device up-to-date with the latest features and fixes.

**SRS 08**: Manage the RTC to ensure precise data timestamping, using microcontroller timers for millisecond accuracy in interval measurements.


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
