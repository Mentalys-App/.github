<h1 align="left">Introducing Mentalys: Empowering Mental Health Through Technology 🧠 - C242-PS333</h1>

## Project Background

Mental health issues in Indonesia are a growing concern, with alarming statistics from the I-NAMHS 2022 showing that 15.5 million adolescents, or 1 in 3, experience mental health disorders. The situation is exacerbated by unequal access to mental health services across different regions, with DKI Jakarta, Aceh, and West Sumatra recording the highest cases. Factors such as bullying, family conflicts, and traumatic experiences further increase the vulnerability of individuals, while early detection and intervention remain limited, especially for marginalized communities.

Mentalys aims to address this pressing issue by offering an innovative, technology-driven solution. Our mobile application leverages cutting-edge tools in machine learning, mobile development, and cloud computing to provide accessible, efficient, and inclusive mental health support.

![Cover](https://github.com/user-attachments/assets/7a56e31f-e927-4e5a-ab01-49123c75a645)

<div align="center">
<a href="https://github.com/Mentalys-Team" style="display: inline-block; margin: 0 10px;">
  <img src="https://img.shields.io/badge/build-passing-brightgreen" alt="Build Status">
</a>
<a href="https://opensource.org/licenses/MIT" style="display: inline-block; margin: 0 10px;">
  <img src="https://img.shields.io/badge/License-MIT-blue.svg" alt="License">
</a>
<a href="https://github.com/Mentalys-Team" style="display: inline-block; margin: 0 10px;">
  <img src="https://img.shields.io/badge/Version-0.8.0-green" alt="Version">
</a>
</div>

## Project Development Journey

### Problem Analysis
- Identified critical mental health challenges in Indonesia:
  - 1 in 3 adolescents (15.5 million) experiencing mental health disorders
  - Unequal access to mental health services across regions
  - Limited early detection and intervention mechanisms

### Research and Brainstorming
- Conducted comprehensive research on mental health technology solutions
- Identified key pain points in existing mental health support systems
- Brainstormed innovative technological interventions

### Solution Design
- Developed a comprehensive mobile application (Mentalys) addressing multiple mental health support needs
- Identified key technological components:
  - Machine Learning for diagnosis
  - Mobile development for user experience
  - Cloud computing for scalable infrastructure
  - AI-powered Personalization

### Technology Implementation
1. **Machine Learning Models**
   - Sourced diverse datasets from Kaggle
   - Developed three specialized models:
     - Questionnaire Analysis (99% accuracy)
       <div align="center">
         <img src="https://github.com/user-attachments/assets/7fecc308-e7e2-4743-8e49-fd0b06f51b28" width="650" alt="Questionnaire Analysis Model Result"/>
       </div>

     - Voice Emotion Detection (94% accuracy)
       <div align="center">
         <img src="https://github.com/user-attachments/assets/0e84f11e-e404-4a72-8352-b16f6d5f5b26" width="650" alt="Voice Emotion Detection Model Result"/>
       </div>

     - Handwriting Analysis (84% accuracy)
       <div align="center">
         <img src="https://github.com/user-attachments/assets/21be713f-9f9f-4cd2-b172-73a0ce7498d9" width="650" alt="Handwriting Analysis Model Result"/>
       </div>

2. **Mobile Development**
   - Used Kotlin and Android Studio
   - Designed intuitive UI/UX
   - Implemented key features:
     - User authentication
     - Mental health diagnosis
     - Mood tracking
     - Emergency support

3. **Cloud Infrastructure**
   - Utilized Google Cloud Platform
   - Implemented secure authentication
   - Created scalable backend services
   - Integrated APIs for seamless functionality

## Team Composition

<div align="center">
  
| Name | Student ID | Learning Path | Contribution/Task |
|------|------------|---------------|--------------|
| I Gede Widnyana | M014B4KY1819 | Machine Learning | I built the questionnaire model with an accuracy of 99% to support the mental health diagnosis feature. I handled the administrative aspects, managed the core idea of the Mentalys project, and guided the team to ensure the successful development and integration of key features. |
| I Nyoman Adi Mahendra Putra | M014B4KY1864 | Machine Learning | I have worked on a machine learning model for audio that can detect a person's emotions. Based on these emotions, it can classify whether someone is experiencing depression or not, aligning with the mental health topic we are addressing. The model currently achieves 94% accuracy. |
| Made Pranajaya Dibyacita | M014B4KY2373 | Machine Learning | ... |
| I Made Agus Budiarta | A403B4KY1851 | Mobile Development | I have developed a mental health test feature that includes a voice test, handwriting test, and questionnaire. Additionally, I implemented mental test history, motivational messages, definitions of mental states along with related articles based on test results,I also developed nearby clinic information using GPS. On the settings page, I included an "About Us" section containing terms of service, privacy policy, and app information. On the education page, I created a dialog displaying details about food content, view all food page, and view all articles page |
| Rezky Aditia Fauzan | A810B4KY3794 | Mobile Development | I created article pages. I created authentication screen. I created dark mode. I created multi-language translation. I created consultation screen. I create the infrastructure of the app. I managed the code. I did the finishing of the code and ui. I made sure the app runs smoothly. |
| Abdi Setiawan | C179B4KY0013 | Cloud Computing | I have created a complete REST API that includes Articles and Food API, Nearby Clinic API, and documentation using Swagger that can be accessed directly through a public URL. This REST API also includes dummy psychiatrist data integrated with Midtrans for payment, user authentication using Firestore, and data storage in Firebase. In addition, I integrated three machine learning models that have been deployed to cloud computing to support AI features, ensuring reliable performance. All APIs are deployed, ready to use with a seamless payment experience. |
| Shevabey Rahman | C179B4KY4138 | Cloud Computing | I collaborate with the team in developing cloud infrastructure and managing cloud resources in Google Cloud. I successfully created a REST API for psychiatrist contacts with security implementation, and documented the API using Postman that can be accessed via a public URL. In addition, I was involved in updating food recommendation article data prepared by the Machine Learning team, as well as managing data storage in Firebase and images in Google Storage to support the needs of the Mobile Development team. I also monitored system performance and performed troubleshooting to ensure system stability and support AI features and endpoints that had been deployed. |

</div>

### Cloud Architecture
<div align="center">
  <img src="https://github.com/user-attachments/assets/6f9251bf-98c6-49d4-bc8b-cd5caa297e4e" width="500" />
</div>

## App Installation Guide

### Prerequisites
- Android smartphone (Version 8.0 or higher)
- Minimum 200MB free storage space
- Active internet connection

### Installation Steps
1. **Download APK**
   - Visit: [Mentalys APK](https://drive.google.com/drive/folders/1r7ULhkAKtTeRaoagPvunXmEoKpZTk2G9?usp=drive_link)

2. **Enable Unknown Sources**
   - Go to Settings > Security
   - Allow installation from unknown sources

3. **Install the App**
   - Locate downloaded APK
   - Follow installation prompts
   - Grant necessary permissions

4. **First-Time Setup**
   - Complete onboarding
   - Create user account
   - Set language preference

### Troubleshooting
- Ensure stable internet connection
- Check device compatibility
- Restart device if installation fails

## Tools

<div align="center">
  <h3>Machine Learning</h3>
</div>
<div align="center">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow"/>
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/Jupyter-F37626?style=for-the-badge&logo=jupyter&logoColor=white" alt="Jupyter"/>
</div>

<div align="center">
  <h3>Mobile Development</h3>
</div>
<div align="center">
  <img src="https://img.shields.io/badge/Kotlin-0095D5?style=for-the-badge&logo=kotlin&logoColor=white" alt="Kotlin"/>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase"/>
  <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=android-studio&logoColor=white" alt="Android Studio"/>
</div>

<div align="center">
  <h3>Cloud Computing</h3>
</div>
<div align="center">
  <img src="https://img.shields.io/badge/Google_Cloud-4285F4?style=for-the-badge&logo=google-cloud&logoColor=white" alt="Google Cloud"/>
  <img src="https://img.shields.io/badge/Express.js-000000?style=for-the-badge&logo=express&logoColor=white" alt="Express.js"/>
  <img src="https://img.shields.io/badge/TypeScript-3178C6?style=for-the-badge&logo=typescript&logoColor=white" alt="TypeScript"/>
</div>

## Project Repositories

| Component          | Repository Link                                                                                                                                               |
|--------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Machine Learning   | [ML Audio](https://github.com/Mentalys-App/Audio-Classification-ML), [ML Handwriting](https://github.com/Mentalys-App/handwritting_detection), [ML Quiz](https://github.com/Mentalys-App/tabular_ml) |
| Mobile Development | [Mobile Repository](https://github.com/Mentalys-App/mentalys-app-android)                                                                                     |
| Cloud Computing    | [Rest API](https://github.com/Mentalys-App/CLOUD-COMPUTING), [API Nearest Clinic](https://github.com/Mentalys-App/API-Klinik-Terdekat), [API Article and Food Library](https://github.com/Mentalys-App/API-Artikel-dan-Makanan) |

## Team GitHub Profiles

<div align="center">
  <a href="https://github.com/GdWidnyana">
    <img src="https://github.com/GdWidnyana.png?size=100" width="100" height="100" style="border-radius: 50%; margin: 10px;" alt="GdWidnyana"/>
  </a>
  <a href="https://github.com/HenPx">
    <img src="https://github.com/HenPx.png?size=100" width="100" height="100" style="border-radius: 50%; margin: 10px;" alt="HenPx"/>
  </a>
  <a href="https://github.com/mdprana">
    <img src="https://github.com/mdprana.png?size=100" width="100" height="100" style="border-radius: 50%; margin: 10px;" alt="mdprana"/>
  </a>
  <a href="https://github.com/IMadeAgus">
    <img src="https://github.com/IMadeAgus.png?size=100" width="100" height="100" style="border-radius: 50%; margin: 10px;" alt="IMadeAgus"/>
  </a>
  <a href="https://github.com/zyrridian">
    <img src="https://github.com/zyrridian.png?size=100" width="100" height="100" style="border-radius: 50%; margin: 10px;" alt="zyrridian"/>
  </a>
  <a href="https://github.com/abdisetiakawan">
    <img src="https://github.com/abdisetiakawan.png?size=100" width="100" height="100" style="border-radius: 50%; margin: 10px;" alt="abdisetiakawan"/>
  </a>
  <a href="https://github.com/Shevabey">
    <img src="https://github.com/Shevabey.png?size=100" width="100" height="100" style="border-radius: 50%; margin: 10px;" alt="Shevabey"/>
  </a>
</div>


## License

This project is licensed under the MIT License - see the [LICENSE](https://opensource.org/licenses/MIT) file for details.
