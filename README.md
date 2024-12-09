# Traffic Light System Team
We are a team of developers and engineers working on a smart traffic light system using Arduino Yun and Grove Shield. Our project aims to simulate real-world traffic management with pedestrian crossing functionality.
## Project Overview
This project demonstrates a basic traffic light control system. It uses three LEDs (red, yellow, and green) to mimic the behavior of a real traffic light, and includes a push button to simulate a pedestrian crossing feature.

**Technologies:**
- Arduino Yun
- Grove Shield
- Arduino IDE
- LEDs (Red, Yellow, Green)
- Push Button
## Team Members
- **Ben** - Developer & Documentation
- **Dimitri** - Code Architect & Testing
## Key Features
- Simulates a real-world traffic light with LEDs.
- Push button to trigger pedestrian crossing and change light sequence.
- Adjustable light duration using code functions (delay()).
- Grove Shield for easy hardware connections.
## How to Use
1. Clone this repository:
https://github.com/BenGavin16/IOT.git
2. Open the Arduino IDE and connect the Arduino Yun via USB.
3. Upload the code to the board and connect the components (LEDs, Push Button).
4. Press the push button to simulate pedestrian crossing.
## Future Improvements
- Add real-time monitoring via Wi-Fi module.
- Implement advanced traffic light control algorithms based on traffic density.
- Enhance pedestrian button functionality.
## Contributing
Contributions are welcome! Please feel free to submit issues or pull requests to improve the project.

# Traffic Light System Project

## Updated Assignment 2 Changes

### Challenges Faced:
1. **WiFi Connectivity Issues**: Configuring the Arduino Yun to connect to WiFi proved challenging and consumed significant time. This issue primarily affected the integration of IoT functionalities like real-time status updates via the Blynk app.
2. **Button Functionality**: Initially, the pedestrian push button did not work as expected. Debugging required checking the physical connections and ensuring proper code alignment with the button's virtual pins.
3. **Compilation Errors**: Errors during code upload via the Arduino IDE, mostly related to library usage and board settings, slowed progress. While many errors were resolved through troubleshooting, some issues persisted, impacting testing.

### Lessons Learned:
1. **Hardware-Software Integration**: This project highlighted the importance of ensuring compatibility between hardware components and software libraries.
2. **Rigorous Testing**: IoT projects demand continuous testing at every stage to identify and resolve issues early, particularly for connectivity and real-time updates.
3. **Collaborative Problem-Solving**: Working as a team allowed us to divide tasks effectively, addressing both physical and software-related challenges more efficiently.

### Current Status:
- **Machine Learning Potential**: A section has been added discussing how machine learning could improve traffic light efficiency by analyzing real-life data like traffic patterns and times of day.
- **Testing and Debugging Updates**: Testing focused on verifying LED sequence timing, ensuring the push button interrupted the system correctly, and confirming the Blynk app received updates in real-time.
- **WiFi Connectivity**: Despite efforts, unresolved WiFi issues prevented full functionality of real-time traffic updates.

### Future Steps:
1. **Debugging**: Focus on resolving the WiFi connectivity issues with the Arduino Yun to ensure seamless integration with the Blynk app.
2. **Finalize Testing**: Verify the functionality of all components, including the push button and virtual pins.
3. **Alternative Platforms**: Consider exploring other IoT platforms for better integration and reliability in future iterations.
4. **Machine Learning Implementation**: Investigate the use of machine learning to dynamically adjust traffic light timings based on traffic patterns and conditions.

