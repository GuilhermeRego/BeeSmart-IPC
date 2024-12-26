# BeeSmart

This project was developed for the Interação Pessoa-Computador (Human-Computer Interaction) 2024-2025 course.

## Phase I – User and Task Analysis

---

### **Table of Contents**

- [**Project’s Idea Description**](#project’s-idea-description)
- [**Related Apps/Devices/Systems**](#related-apps/devices/systems)
- [**Questionnaire Highlights**](#questionnaire-highlights)
- [**PACT Analysis**](#pact-analysis)
  - [People](#people)
  - [Activities](#activities)
  - [Context](#context)
  - [Technologies](#technologies)
- [**Personas**](#personas)
  - [João Silva](#joão-silva)
  - [Lúcia Pereira](#lúcia-pereira)
- [**Activity Scenarios**](#activity-scenarios)
  - [João Silva](#joão-silva-1)
  - [Lúcia Pereira](#lúcia-pereira-1)
- [**Functionalities**](#functionalities)
- [**Annexes**](#annexes)
  - [Questionnaire](#questionnaire)
  - [Summary of Results](#summary-of-results)

---

### **Project’s Idea Description** 

BeeSmart is a mobile application aimed at assisting users in managing their energy consumption to save money while maintaining comfort. The app provides a user-friendly interface to control smart devices, automate tasks, and achieve energy-saving goals. BeeSmart utilizes AI to optimize device usage, offers personalized suggestions for improving energy efficiency, and enables users to manually adjust settings with automatic recalibration to meet predefined targets. The app is designed for users of all ages and technical abilities, contributing to a more eco-friendly world.

---

### **Related Apps/Devices/Systems**

Several existing solutions inspired BeeSmart’s concept:

- **Google Nest**: Offers smart home control and thermostat automation but is limited to Google devices and internet connectivity.
- **Ecobee**: Includes energy monitoring and home management but has a complex setup and high cost.
- **Sense Energy Monitor**: Tracks energy usage but requires additional hardware and lacks automation features.

BeeSmart aims to integrate these strengths while addressing their limitations.

---

### **Questionnaire Highlights**

A questionnaire gathered responses from 20 participants to understand the target audience and their preferences. Key insights include:

1. **Age**: Most participants are 18-24 years old, predominantly university students.
2. **Smart Devices**: Two-thirds own at least one smart device, with nearly half owning four or more.
3. **Device Types**: TVs, lights, and fridges were the most common, guiding development priorities.
4. **Desired Features**: Participants prioritized detailed energy consumption reports and simple device control interfaces. The least popular feature was energy-saving news updates.

Detailed statistics and summaries are provided in the annex.

---

### **PACT Analysis**

#### **People** 
The target audience includes young adults, primarily university students, with medium to high familiarity with technology. However, the app must cater to varying proficiency levels. Users value convenience over active energy monitoring but are interested in solutions that simplify their routines without compromising comfort.

#### **Activities**
Users primarily use smart devices for automation and convenience, with energy savings as a secondary concern. Monitoring energy consumption is rare, typically done monthly or less frequently. The app must balance automation with manual control options.

#### **Context**
BeeSmart will be used in domestic settings, both at home and remotely. It must ensure easy and reliable device control from users’ smartphones.

#### **Technologies** 
The app leverages IoT to manage smart devices like TVs, lights, and fridges. It must feature an intuitive interface, provide energy-saving suggestions, and support automation for predefined goals.

*Note*: The analysis reflects the limited demographic of the questionnaire’s respondents. Broader audiences, such as users aged 25-39 who are more likely to pay energy bills, are expected to show greater interest in BeeSmart.

---

### **Personas** 

#### **João Silva**

- **Age**: 23  
- **Occupation**: Master’s Student in Software Engineering  
- **Lifestyle**: A tech-savvy individual who values automation and comfort. João prefers minimal manual intervention, relying on technology to handle tasks. He spends most of his time studying and gaming at home.  
- **Needs**: Automation of smart devices, energy consumption updates, and a system that ensures comfort without requiring constant input.  
- **Frustrations**: Dislikes manual adjustments and complex setups.

#### **Lúcia Pereira**

- **Age**: 30  
- **Occupation**: Portuguese Teacher  
- **Lifestyle**: A busy mother who prioritizes safety, efficiency, and savings. Although not very tech-savvy, Lúcia uses technology to manage her home and ensure her child’s well-being.  
- **Needs**: Intuitive interfaces, clear notifications, and energy-saving features.  
- **Frustrations**: Struggles with confusing interfaces and technical jargon.

---

### **Activity Scenarios** 

#### **João Silva** 

After a day of online classes, João checks BeeSmart to review energy usage. He notices he’s nearing his monthly consumption target and adjusts settings accordingly. Later, he temporarily disables automation to enjoy gaming, with the app optimizing ambient lighting and temperature to balance energy use.

#### **Lúcia Pereira** 

At work, Lúcia uses BeeSmart to ensure her home is prepared for her daughter’s return. She turns off unused devices, monitors security cameras, and adjusts the thermostat to save energy while ensuring the house is warm upon arrival.

---

### **Functionalities** 

BeeSmart offers the following features:

- **Smart Device Control**: Unified control for multiple devices with AI assistance.
- **Energy Monitoring**: Real-time consumption data.
- **Automated Suggestions**: AI-driven energy-saving recommendations.
- **Goal Setting**: Automation tailored to user-defined energy-saving targets.
- **Alerts and Notifications**: Timely updates on device status and energy use.
- **Readjustments**: Automatic recalibration to meet goals when manual changes are made.

---

### **Annexes** 

#### **Questionnaire** 

Summarized data from 20 respondents regarding demographics, smart device usage, and feature preferences.

#### **Summary of Results** 

Most respondents are young adults, familiar with smart devices but not actively monitoring energy consumption. BeeSmart must focus on simplicity, automation, and energy-saving goals to meet user needs effectively.

---

## Phase II – Lo-Fi Prototype and Heuristic Evaluations

### Overview

BeeSmart is a mobile application designed to manage smart electric devices at home. The app prioritizes intuitive design by avoiding complex features and labels, ensuring ease of use. In this phase of the project, we developed a Low-Fidelity Prototype (Lo-Fi) with high-priority features and evaluated its usability through heuristic evaluations conducted by peers.

The project involved the following key tasks:

1. **Check your profile’s name**: This task validates the intuitiveness of the bottom navigation bar.
2. **Check the Smart TV’s weekly energy spending**: Tests the user’s ability to interpret and navigate the report graphs.
3. **Toggle Automatic Management on the Smart Toilet**: Assesses the ease of interacting with device management features.

---

### Features

- **Simplified Navigation**: Bottom navigation bar for quick access to main pages (Profile, Reports, Home).
- **Interactive Reports**: Weekly energy usage graphs with grouping options by floor, division, or device.
- **Device Management**: Toggle-based automatic management features for smart devices.

---

### Wireflow

The Wireflow illustrates the navigation steps for each task:

#### Task 1: Check Your Profile’s Name
1. Navigate to the Profile page.

#### Task 2: Check the Smart TV’s Weekly Energy Spending
1. Go to the Reports page.
2. Select “Group by” dropdown.
3. Choose “Device” option.

#### Task 3: Toggle Automatic Management on the Smart Toilet
1. Open the Home page.
2. Select the bee icon corresponding to the toilet.
3. Enable automatic management in the popup.

---

### Heuristic Evaluation Results

#### Summary
The prototype was tested by members from Groups 5 and 6. A total of 14 usability issues were identified, categorized using Nielsen’s Usability Heuristics and rated on severity (1-4). Below are key findings and our responses:

1. **Home page device identification is unclear (Severity: 4)**
   - Problem: Bee icons are not intuitive.
   - Response: Agreed. Future iterations will use device-specific icons.

2. **Unbalanced design on Home page (Severity: 2)**
   - Problem: Excessive empty space.
   - Response: Addressing with additional features like floor navigation sliders.

3. **Small and non-intuitive bee icons (Severity: 2)**
   - Problem: Buttons are perceived as too small.
   - Response: Icons will be resized and replaced with device-specific visuals.

4. **Pop-up pages lack labels (Severity: 2.5)**
   - Problem: Unclear interface for device-specific actions.
   - Response: Adding descriptive labels in Phase 3.

---

### Planned Improvements for Phase III

1. Replace bee icons with device-specific visuals (e.g., TV, lamp).
2. Increase size and usability of Profile editing buttons.
3. Add labels and values to pop-ups and reports.
4. Implement a swipe feature for floor navigation.
5. Standardize fonts, colors, and text sizes for consistency.
6. Make the “Group by” dropdown in Reports closable without selection changes.
7. Introduce an AI assistant for personalized energy-saving advice.
8. Adjust bottom navigation bar dimensions and functionality.

---

## Authors
- Gabriel da Quinta Braga (up202207784)
- Gonçalo Nuno Santos Pires Barroso (up202207832)
- Guilherme Silveira Rego (up202207041)
