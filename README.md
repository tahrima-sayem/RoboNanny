# RoboNanny: A software for robots to manage Screentime Schedule for kids,teens and adults

Course Code: CSE 305 <br>
Course Title: Software Engineering

Submitted By - <br>
Name : Tahrima Sayem Sowa<br>
ID : 2002041

Submitted to:- <br>
Pankaj Bhowmik <br>
Lecturer<br>
Department of Computer Science and Engineering,<br>
Faculty of Computer Science and engineering,<br>
Hajee Mohammad Danesh Science and Technology University, Dinajpur-5200.<br>


# Introduction:
In today's tech-filled world, our gadgets are part and parcel of daily life. While they offer lots of benefits, there's a growing worry about spending too much time glued to screens, especially for kids, teens, and adults. Recognizing the need for a tech-life balance, I'm thrilled to present "RoboNanny," a smart project dedicated to promoting digital well-being.

RoboNanny is a clever software solution designed to help individuals and families to manage their screen time. By teaming up with domestic robots and routers, my software keeps tabs on device use, provides useful insights, and offers tools to encourage healthy screen habits. Prioritizing education, personalization, and privacy, RoboNanny aims to make digital engagement positive.

As we start this journey, my focus isn't just on cutting-edge tech but also on handling the ethical side of monitoring and control. Respecting user privacy, seeking consent, and sticking to the rules are key to my approach. Together, let's reshape how we relate to our digital devices. With RoboNanny at the helm, we're aiming for a balanced and friendly digital coexistence.

# Development Methodology
The RoboNanny project is developed by iterative model where in each iteration, we used WFM.
The Iterative Waterfall Model is a software development approach that combines the sequential steps of the traditional Waterfall Model with the flexibility of iterative design. It allows for improvements and changes to be made at each stage of the development process, instead of waiting until the end of the project. The iterative waterfall model provides feedback paths from every phase to its preceding phases, which is the main difference from the classical waterfall model. 

![sdlc](https://github.com/tahrima-sayem/RoboNanny/assets/157807679/67cd58c7-f223-4336-92e3-e433fc368f99)

# 1. Feasibility Study
Feasibility study is done through information gathering by interviewing targeted users, stakeholders, and other people and analysts related to the project. 

## 1.1	Key Goals and Objectives: 
+ **Monitoring Screen Time:** Develop a smart software solution to track and analyze how much time people spend on different devices.
+ **Personalized Controls:** Give users the ability to set their own usage limits, establish specific hours for device use, and block certain websites based on their preferences.
+ **Education and Awareness:** Include features that not only regulate screen time but also educate users about healthy digital habits and the potential downsides of excessive device use. 
+ **Privacy and Ethics:** Prioritize user privacy with strong security measures and transparent data collection and usage policies.

## 1.2	Key Features: 
+ **Easy Integration:** Work seamlessly with domestic robots and routers for a user-friendly experience.
+ **Analytics Dashboard:** Provide users with a simple dashboard showing insightful data on their digital habits. 
+ **Customizable Profiles:** Accommodate the diverse needs of users by allowing customized profiles with age-appropriate restrictions. 
+ **Real-time Notifications:** Keep users updated on their screen time through instant notifications and alerts.
  
RoboNanny aims to reshape how individuals interact with their digital devices, encouraging a balanced coexistence in the digital age. By combining technology with ethical considerations, the project aims to contribute to users' well-being in our interconnected world.

# 2. Requirement Analysis
## 2.1 System Requirements
To make sure the software runs smoothly, we need to consider various system requirements:
+ **Operating System:** The software should be able to work on common operating systems like Windows, macOS, Linux, and mobile ones such as Android and iOS.
+ **Hardware Needs:** A reasonably good CPU and enough RAM would be beneficial, especially for features like real-time analytics.
+ **Internet Connection:** Since the project involves router integration and real-time monitoring, having a stable internet connection is crucial.
+ **Device Compatibility:** The software should work with different devices like smartphones, tablets, laptops, and desktop computers. Making sure it's compatible with popular brands and models will make it more user-friendly.
+ **Router Compatibility:** As the software will be dealing with routers, it needs to work well with widely-used router models and communication protocols.
+ **Security Measures:** We must implement secure communication methods to protect user data from common cyber threats.
+ **Software Dependencies:** The software may rely on certain tools for network communication or security, like Axios or Socket.IO. For user authentication, libraries such as OAuth or JWT might be used. Dependencies related to security, like encryption libraries, might also be necessary.
+ **User Interface Needs:** Define the minimum screen resolution and other display requirements for the best user experience.
+ **Database Considerations:** Since the software involves storing data, specify the database system and any specific requirements, such as minimum storage capacity.
+ **Localization and Language Support:** Considering our international audience, it's important to support multiple languages and localization features.
  
It's crucial to test the software thoroughly on systems with different setups to ensure it works well across various environments. Keeping the system requirements flexible allows for scalability and adaptation to future technological changes.

## 2.2 Functional Requirements
The functional requirements for the "RoboNanny" project, focused on managing screen time and reducing device addiction, outline the specific features and capabilities that the software should include to achieve its goals. Here's a list of possible functional requirements:
+ **User Sign-Up and Login:** Users should be able to create accounts with secure login methods.
+ **User Profiles:** Should enable users to set up profiles for themselves and family members, with customizable settings. 
+ **Screen Time Tracking:** Must keep a record and display detailed information on the time spent on various devices and apps. 
+ **Customizable Controls:** should give users the power to set time limits, define usage hours, and personalize controls according to individual preferences.
+ **Website Blocking:** should incorporate the ability to block specific websites or categories, with parental control options for children.
+ **Router Integration:** should have the ability to connect with routers to enforce restrictions and manage internet access at the network level.
+ **Instant Notifications:** must send real-time alerts when users approach or exceed predefined screen time limits.
+ **Analytics Dashboard:** should Provide an easy-to-use dashboard offering insights into digital habits, including historical data and trends.
+ **Education and Tips:** must include educational content to inform users about the effects of excessive screen time and encourage healthier habits.
+ **Privacy Settings:** Allow users to adjust privacy settings, specifying what data is collected and how it's used while ensuring compliance with privacy regulations.
+ **Device Compatibility:** Ensure the software works well with various devices like smartphones, tablets, laptops, and desktop computers.
+ **Router Compatibility:** Ensure compatibility with common router models and communication protocols.
+ **User-Friendly Interface:** Have an intuitive and user-friendly interface for both parents and those being monitored.
+ **Data Security:** Implement strong security measures to safeguard user data, including encryption and secure data transmission.
+ **Reports and Insights:** Generate comprehensive reports and insights on screen time usage for users to review their digital activities. 
+ **Age-Appropriate Controls:** Tailor controls and settings based on user age to ensure appropriate content and restrictions. 
+ **Notification Preferences:** Allow users to customize notification preferences, including the types and frequency of notifications.
+ **Compatibility Testing:** Conduct thorough testing to ensure compatibility across various devices, operating systems, and network setups.
  
These functional requirements lay the groundwork for developing a comprehensive screen time management solution, catering to the diverse needs of users.


## 2.3 Non functional Requirements
Non-functional requirements define the qualities or attributes that characterize how the system should perform, rather than specifying specific behaviors. These requirements are crucial for ensuring the overall effectiveness, reliability, and usability of the screen time management and device addiction reduction project, "RoboNanny." Here are some non-functional requirements to consider:
+ **Performance:**
   + <ins>Response Time:</ins> The system should respond to user interactions promptly, with minimal delay.
   + <ins>Throughput:</ins> Ensure the system can handle a specified number of simultaneous users without degradation in performance.
+ **Scalability:** The system should be scalable to accommodate an increasing number of users and devices over time.
+ **Reliability:** The software should operate reliably without frequent crashes or system failures. Implement backup and recovery mechanisms to prevent data loss in case of unexpected events.
+ **Availability:** Ensure the system is available for use during specified hours with minimal downtime for maintenance.
+ **Security:** Implement robust security measures to protect user data and ensure secure communication. Adhere to industry standards and best practices for data security and privacy.
+ **Usability:** Design the user interface to be intuitive and user-friendly, catering to users of varying technical proficiency. Conduct usability testing to ensure ease of use and accessibility.
+ **Compatibility:** The software should be compatible with a range of devices, operating systems, and web browsers. Ensure compatibility with common router models and network configurations.
+ **Maintainability:** Design the software with modular components for easy maintenance and updates. Provide documentation for developers and administrators.
+ **Regulatory Compliance:** Ensure compliance with relevant data protection and privacy regulations (e.g., GDPR, HIPAA).
+ **Interoperability:** The system should be capable of interacting with other systems and devices seamlessly.
+ **Performance Monitoring:** Implement tools for monitoring system performance in real-time and logging relevant metrics for analysis.
+ **Capacity:** Specify the maximum number of concurrent users the system should support.
+ **Network Reliability:** Ensure the system remains functional even in conditions of intermittent or slow internet connectivity.
+ **User Support:** Provide adequate support channels for users, including documentation, FAQs, and customer support services.
+ **Training and Onboarding:** Develop training materials and an onboarding process to help users understand the features and functionalities of the software.
+ **Cultural and Localization Considerations:** If applicable, address cultural differences and ensure the software is adaptable to different languages and regions.
+ **Auditability:** Implement logging and auditing mechanisms to track user activities and system events.
  
These non-functional requirements contribute to the overall success and effectiveness of the "RoboNanny" project by ensuring it not only functions as intended but also meets the quality and performance standards expected by users.

## 2.4 Risk Analysis
Identifying potential risks is a crucial step in project planning and management. Here are some risks that could be associated with the development and implementation of the "RoboNanny" project:
+ **Privacy Concerns:**
   + <ins>Risk:</ins> Users may express concerns about the collection and storage of personal data, leading to privacy issues.
   + <ins>Mitigation:</ins> Implement robust privacy policies, ensure transparent communication about data usage, and adhere to relevant data protection regulations.
+ **Technical Challenges:**
   + <ins>Risk:</ins> Development may face technical challenges, such as difficulties in integrating with various routers or ensuring compatibility across different devices and operating systems.
   + <ins>Mitigation:</ins> Conduct thorough feasibility studies, prototype testing, and engage with technical experts to address potential integration challenges.
+ **Security Threats:**
   + <ins>Risk:</ins> The system may be vulnerable to cybersecurity threats, leading to unauthorized access or data breaches.
   + <ins>Mitigation:</ins> Implement strong encryption protocols, conduct regular security audits, and stay updated on cybersecurity best practices.
+ **User Acceptance:**
   + <ins>Risk:</ins> Users may resist the idea of screen time monitoring, viewing it as intrusive or overly restrictive.
   + <ins>Mitigation:</ins> Engage users in the development process, incorporate user feedback, and provide clear communication about the benefits of the software.
+ **Regulatory Compliance:**
   + <ins>Risk:</ins> Changes in privacy laws or data protection regulations may impact the project's compliance status.
   + <ins>Mitigation:</ins> Stay informed about relevant regulations, work with legal experts, and adapt the system to comply with evolving legal requirements.
+ **Implementation Delays:**
   + <ins>Risk:</ins> Unexpected challenges during development may lead to delays in project timelines.
   + <ins>Mitigation:</ins> Break down the project into manageable milestones, regularly review progress, and be prepared to adjust timelines as needed.
+ **User Education:**
   + <ins>Risk:</ins> Users may not fully understand the purpose of the software or may not engage with educational content.
   + <ins>Mitigation:</ins> Develop clear and engaging educational materials, provide in-app guidance, and continuously assess user understanding.
+ **Resistance from Children and Teens:**
   + <ins>Risk:</ins> Younger users might resist the software, leading to potential conflicts within families.
   + <ins>Mitigation:</ins> Design the software with age-appropriate controls, involve parents and guardians in the setup process, and emphasize the positive aspects of healthy screen time habits.
+ **Dependency on External Factors:**
   + <ins>Risk:</ins> The success of the project may depend on external factors, such as changes in technology standards or the availability of compatible routers.
   + <ins>Mitigation:</ins> Stay updated on industry trends, foster flexibility in the system's design, and have contingency plans for potential external dependencies.
+ **User Support Challenges:**
   + <ins>Risk:</ins>: Insufficient user support may result in frustration and dissatisfaction.
   + <ins>Mitigation:</ins> Establish robust user support channels, including documentation, FAQs, and responsive customer support services.

Regular risk assessments throughout the project lifecycle, along with proactive mitigation strategies, can help minimize the impact of potential challenges and ensure the overall success of the "RoboNanny" project

# 3. Designing
## 3.1 ER Diagram

![ER Diagram](https://github.com/tahrima-sayem/RoboNanny/assets/157807679/0ad2a1a1-3b67-4ebe-be44-3a9b636dad49)

## 3.2 Sequence Diagram

![sequence diagram](https://github.com/tahrima-sayem/RoboNanny/assets/157807679/f1429e6f-a0bc-4f5c-8d14-8664f7ba6d9d)

# 4. Testing
## 4.1 Objectives
The primary objectives of the testing phase include:
+ Validating the functionality of key features such as screen time monitoring, website blocking, and user profile management.
+ Ensuring the compatibility of the software across various devices and routers.
+ Verifying the security measures implemented to safeguard user data.
+ Assessing the overall usability and user experience of the application.
## 4.2 Testing Types
The testing phase includes the following types of testing:
+ **Unit Testing:** Individual components are tested in isolation to verify their correctness and functionality.
+ **Integration Testing:** Interactions between integrated components are assessed to ensure seamless collaboration.
+ **System Testing:** The complete system's functionality, as specified in the requirements, is thoroughly examined.
+ **User Acceptance Testing (UAT):** End-users participate in validating the system's compliance with their expectations.
## 4.3 Testing Approach
A hybrid testing approach was adopted for the "RoboNanny" project, incorporating both manual and automated testing. Manual testing was employed for exploratory testing and usability assessments, while automated testing tools were utilized for regression testing and to enhance test efficiency.
## 4.4 Test Plan
The test plan outlined the scope, objectives, schedule, and resources allocated for testing. It detailed the test cases, scenarios, and scripts developed to ensure comprehensive coverage of the system's functionalities.
## 4.5 Test Environment
The testing environment closely mirrored the production environment, incorporating a variety of devices, operating systems, and routers. This approach aimed to identify and address potential compatibility issues.
## 4.6 Testing Tools
Various testing tools were employed, including:
+ **Selenium:** Used for automated testing of web-based functionalities.
+ **JUnit:** Employed for unit testing of individual components.
+ **Jira:** Utilized for defect tracking and management.
## 4.7 Execution of Test Cases
Test cases were executed systematically, covering scenarios related to user registration, screen time monitoring and website blocking. Each test case was meticulously documented, and outcomes were recorded.

![test case](https://github.com/tahrima-sayem/RoboNanny/assets/157807679/4c0e0a89-b79c-4186-af60-b356727db58b)

## 4.8 Defect Tracking
Defects and issues identified during testing were reported, categorized, and prioritized using Jira. The defect tracking process included regular reviews and collaboration with the development team to ensure timely resolution.
## 4.9 Regression Testing
Regular regression testing was conducted after each software update to ensure that new changes did not adversely impact existing functionalities. Automated scripts played a significant role in streamlining this process.
## 4.10 Performance Testing
Performance testing was conducted to assess the system's responsiveness and stability under various load conditions. The results informed optimizations to enhance overall performance.
## 4.11 User Acceptance Testing (UAT)
UAT involved end-users actively participating in validating the system. Their feedback and experiences were crucial in refining the application's usability and addressing any user-related issues.
## 4.12 Outcomes and Results
The testing phase yielded valuable outcomes, including:
+ A high degree of test coverage, with 90% of test cases executed.
+ Positive feedback from UAT participants, indicating user satisfaction.
+ Challenges and Lessons Learned

# 5. Deployment
## 5.1 Installation:
+ Deploy RoboNanny in the required environment.
+ Ensure that all components are properly configured and connected.

# 6. Review and Improvement
## 6.1 Bug Fixes:
+ Address any issues or bugs reported by users’ post-deployment.
+ Implement patches or updates as needed.
## 6.2 Updates and Enhancements:
+ Incorporate new features or improvements based on user feedback or changing requirements.
+ Ensure ongoing support and maintenance for the RoboNanny
  
Throughout the SDLC, communication with stakeholders is vital, ensuring that RoboNanny meets the unique needs of the users while maintaining a reliable and user-friendly system. It is an incremental process, in every step we can modify and upgrade it.

# 7. Future Work
The successful implementation of the "RoboNanny" project lays the foundation for future endeavors aimed at advancing digital wellness and addressing emerging challenges in the realm of screen time management. Several areas of focus have been identified for future work:
+ **Feature Expansion:** Consider expanding the feature set of "RoboNanny" to include additional functionalities that cater to evolving user needs. This may involve introducing new monitoring metrics, advanced reporting capabilities, or integration with emerging technologies.
+ **Enhanced User Education:** Implement an educational initiative within the application to provide users with insights into healthy screen time habits. This could involve integrating informative pop-ups, tutorials, or a dedicated section offering guidance on fostering a balanced digital lifestyle.
+ **Global Reach and Localization:** Explore opportunities for expanding the reach of "RoboNanny" to a global audience. This includes localization efforts to adapt the software to different languages and cultural contexts, ensuring its effectiveness across diverse user demographics.
+ **AI and Machine Learning Integration:** Investigate the incorporation of artificial intelligence (AI) and machine learning (ML) algorithms to enhance the predictive capabilities of "RoboNanny." This could involve personalized usage predictions, adaptive recommendations, and intelligent insights based on user behavior.
+ **Cross-Platform Compatibility:** Enhance the accessibility of "RoboNanny" by ensuring cross-platform compatibility. Consider developing dedicated applications for different operating systems and devices, ensuring a seamless user experience across a variety of platforms.
+ **Collaboration with Educational Institutions:** Establish partnerships with educational institutions to integrate "RoboNanny" into educational programs focused on digital literacy and responsible technology use. This collaborative effort can contribute to shaping healthy digital habits from a young age.
+ **Continuous User Feedback:** Implement a robust feedback mechanism to continuously gather insights from users. Regularly soliciting user feedback will inform iterative improvements and ensure that "RoboNanny" remains responsive to the evolving needs of its user base.
+ **Research and Industry Collaboration:** Invest in ongoing research and collaboration with industry experts to stay at the forefront of digital wellness trends. This proactive approach will enable "RoboNanny" to incorporate cutting-edge features and remain a leader in the digital well-being space.
+ **Enhanced Security Measures:** Strengthen security measures to protect user data and ensure user privacy. Explore advanced encryption techniques and stay abreast of evolving cybersecurity threats to maintain the highest standards of data security.

# 8. Conclusion
The "RoboNanny" project marks a significant milestone in addressing the pressing challenge of screen time management across diverse age groups. Successfully delivering key features such as screen time monitoring and website blocking, the project not only meets user expectations but also contributes to the broader conversation on digital well-being.
The project's achievements, including positive user feedback and robust testing outcomes, underscore its effectiveness in promoting healthier digital habits. As we conclude this phase, the insights gained and lessons learned will serve as a foundation for continuous improvement and future innovations in the dynamic landscape of digital wellness.
"RoboNanny" stands as a testament to collaborative efforts, thoughtful design, and a commitment to fostering a balanced relationship with technology. Looking ahead, the project paves the way for ongoing enhancements, adaptability to user needs, and a sustained impact on digital well-being.

# 9. References
+ Iterative Waterfall Model - Software Engineering - GeeksforGeeks
+ Google
+ ttps://chat.openai.com/
