# Algorithmic Problem Solving Portfolio

![Header Image](header.png)

## 📘 Course Information

- **Course Name:** Algorithmic Problem Solving
- **Course Code:** 23ECSE309
- **Name:** Karthik Jodangi
- **University:** KLE Technological University, Hubballi-31

## 📝 Overview

This portfolio explores the functionalities of Over-The-Top (OTT) platforms, analyzing existing features and proposing new functionalities to enhance user experience and operational efficiency. The document covers market analysis, business use cases, potential challenges, suitable algorithms, and performance analysis.

## 📑 Table of Contents

1. [Introduction](#introduction)
2. [Business Cases](#business-cases)
   - [Existing Functionalities](#existing-functionalities)
   - [Proposed Functionalities](#proposed-functionalities)
   - [Detailed Business Use Cases](#detailed-business-use-cases)
3. [Performance Analysis](#performance-analysis)
4. [References](#references)

## 📊 Introduction

### Market Analysis

OTT platforms have significantly transformed the content consumption landscape. The global OTT market, valued at USD 121.61 billion in 2021, is projected to grow at a CAGR of 29.4% from 2022 to 2030. Major players include Netflix, Amazon Prime Video, Hulu, and Disney+. The growth is driven by increasing internet penetration and the adoption of smart devices.

### Objectives

- Identify and analyze existing OTT platform functionalities.
- Propose new functionalities to enhance the domain.
- Explore business use cases, challenges, and benefits.
- Suggest suitable algorithms and design techniques.

## 💼 Business Cases

### Existing Functionalities

1. 📺 Content Streaming
2. 🔄 Personalized Recommendations
3. 📱 Multiple Device Compatibility
4. 📥 Offline Viewing
5. 📂 Content Categorization
6. 👤 User Profiles
7. 📜 Content Licensing and Rights Management
8. 💰 Content Monetization
9. 🌐 Content Delivery Network
10. 🗣 Social Integration

### Proposed Functionalities

1. 🔍 Content Discovery Tools
   - Advanced Filtering Options
   - Personalized Playlists
   - Mood-Based Recommendations
2. 🛡 Measures Against Piracy and Unauthorized Access
3. 🕶 AR and VR Technologies
4. 👥 Social Viewing Experiences
   - Virtual Watch Parties
   - Real-time Chat
5. 🎯 Personalized Advertising
6. 🏠 Integration with Smart Home Devices
7. 🌎 Content Localization
   - Volume Adjustment for BGM, Voice, and Songs
   - Multi-language Support
   - AI-generated Subtitles and Dubbing
8. 📊 Interactive Content
   - Quizzes, Polls, etc.

### Detailed Business Use Cases

1. **Advanced Filtering Options**
   - **Challenge:** Efficiently filtering a large dataset of content.
   - **Algorithm:** Trie Data Structure.
   - **Use Case:** Autocomplete search, keyword-based filtering.
   - **Description:** A Trie is a tree-like data structure used to store a dynamic set of strings where keys are usually strings. It is useful for search and filter functionalities where prefix matching is needed.
   - Find the sample code [here](https://gist.github.com/calmhandtitan/7872405)


2. **Personalized Playlists**
   - **Challenge:** Creating playlists based on user preferences.
   - **Algorithm:** Collaborative filtering.
   - **Description:** Collaborative Filtering algorithms, such as user-based or item-based approaches, are well-suited for recommending playlists based on similarities between users or between playlists themselves.
   - Find the sample code [here](https://github.com/asif536/Movie-Recommender-System)

3. **Mood-Based Recommendations**
   - **Challenge:** Accurately identifying user mood.
   - **Algorithm:** Sentiment analysis using NLP techniques.
   - **Description:** Utilizing sentiment analysis techniques to analyze user reviews, comments, or social media interactions related to content can provide insights into mood and preferences.
   - Find the sample code [here](https://github.com/SkyThonk/Movie-Reviews-Sentiment-Analysis)
     
4. **Measures Against Piracy**
   - **Challenge:** Preventing unauthorized access and distribution.
   - **Algorithm:** Watermarking and encryption.
   - **Description:** Strong encryption algorithms like AES (Advanced Encryption Standard) to protect the content itself from being accessed without authorization. This can prevent unauthorized reading or modification of the content.
   - Find the sample code [here](https://github.com/gabrielmbmb/aes)

5. **AR and VR Technologies**
   - **Challenge:** Creating immersive content experiences.
   - **Algorithm:** 3D rendering and real-time processing.
   - **description:** Rasterization: Commonly used for real-time rendering in VR and AR applications. It involves converting 3D objects into 2D images suitable for display.
   Ray Tracing: Provides more realistic lighting and shadows by tracing the path of light rays through a scene. Though computationally intensive, it's increasingly feasible in real-time applications with advancements in hardware.

6. **Virtual watch parties**
   - **Challenge:** Synchronizing content playback for multiple users.
   - **Description:** Virtual watch parties in OTT platforms utilize synchronization algorithms like vector clocks and consensus algorithms, data structures such as distributed hash tables, and streaming protocols like WebRTC. These ensure real-time communication, playback synchronization, and efficient session management, providing a seamless, synchronized viewing experience for all participants.

7. **Real-time Chat**
   - **Challenge:** Seamless user interaction.
   - **Description:** Real-time chat in OTT platforms employs message queues for orderly message delivery, the pub/sub pattern facilitated by hash maps for efficient message broadcasting, and WebSockets to maintain persistent, low-latency communication channels between clients and servers. These technologies ensure responsive and scalable real-time chat experiences, integral to enhancing user interaction during virtual events and streaming sessions.

8. **Personalized Advertising**
   - **Challenge:** Targeting ads effectively without intruding on user experience.
   - **Algorithm:** Machine learning algorithms.
   - **Description:** Decision Trees and Random Forests: Can predict user preferences based on demographic data, viewing history, and contextual information.
   - Find the sample code [here](https://github.com/milaan9/Python_Decision_Tree_and_Random_Forest)

9. **Integration with Smart Home Devices**
   - **Challenge:** Seamlessly connecting with smart home ecosystems.
   - **Algorithm:** MQTT (Message Queuing Telemetry Transport)
   - **Description:** MQTT (Message Queuing Telemetry Transport): This lightweight messaging protocol is ideal for IoT (Internet of Things) environments. It ensures efficient, reliable communication between OTT platforms and smart home devices, supporting real-time updates and commands while optimizing bandwidth and battery life.
   - Find the sample code [here](https://github.com/dotnet/MQTTnet)
     
10. **Volume Adjustment**
   - **Challenge:** Segregated audio for BGM, voice and songs.
   - **Description:** Algorithms such as Finite Impulse Response (FIR) filters and dynamic range compression are utilized for adjusting volume levels independently for background music (BGM), voice, and songs. These algorithms operate on data structures like arrays or linked lists to manage and process audio samples effectively. Real-time audio processing techniques, including digital signal processing (DSP) and multithreading, ensure seamless integration and dynamic adjustment of audio levels, enhancing the user experience by maintaining clear audio separation and consistent sound quality across various media streams.

11. **Multi-language Support**
    - **Challenge:** Availability of different languages for the same viewing content.
    - **Description:** To enable multi-language support in OTT platforms, algorithms like hash tables for efficient storage and retrieval of language-specific content, along with trie data structures for fast text search, are employed. Language detection utilizes n-gram models and statistical methods to identify and switch between languages dynamically. Content localization techniques, such as resource bundles and dynamic loading, ensure seamless presentation of localized content based on user preferences, enhancing accessibility and user engagement across diverse linguistic audiences on streaming platforms.

12. **AI-generated Subtitles and Dubbing**
    - **Challenge:** Real-time automated dubbing and subtitles feature.
    - **Description:** To automate AI-generated subtitles and dubbing in OTT platforms, algorithms like sequence alignment (e.g., Needleman-Wunsch), tokenization, and parsing are employed for accurate synchronization and linguistic analysis. Machine learning models such as sequence-to-sequence (Seq2Seq) and speech recognition algorithms facilitate real-time translation and transcription tasks. Data structures like hash maps support efficient storage and retrieval of textual data, enabling seamless integration of AI-driven technologies for multilingual content accessibility and enhanced viewer engagement on streaming platforms.
    - Find sample code for Needleman-Wunsh [here](https://github.com/blievrouw/needleman-wunsch)
    - Find sample code for Seq2Seq model [here](https://github.com/google/seq2seq)

12. **Interactive Content**
    - **Challenge:** Enhancing user engagement through interactive features.
    - **Description:** To enable interactive content such as quizzes and polls in OTT platforms, algorithms like hash tables and HashMaps are essential for efficient storage and retrieval of questions, options, and user responses. Graph algorithms play a role in generating interactive pathways and ensuring logical consistency within quizzes, while real-time data processing algorithms handle dynamic user inputs and concurrency control to maintain data integrity during simultaneous interactions. Implementing these data structures and algorithms facilitates seamless integration of interactive features, enhancing user engagement and interaction on OTT platforms through responsive and engaging content experiences.

## 📚 References

