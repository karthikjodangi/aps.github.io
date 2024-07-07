<!-- # Algorithmic Problem Solving Portfolio -->

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
   - **Description:** Rasterization: Commonly used for real-time rendering in VR and AR applications. It involves converting 3D objects into 2D images suitable for display.
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

13. **Interactive Content**
    - **Challenge:** Enhancing user engagement through interactive features.
    - **Description:** To enable interactive content such as quizzes and polls in OTT platforms, algorithms like hash tables and HashMaps are essential for efficient storage and retrieval of questions, options, and user responses. Graph algorithms play a role in generating interactive pathways and ensuring logical consistency within quizzes, while real-time data processing algorithms handle dynamic user inputs and concurrency control to maintain data integrity during simultaneous interactions. Implementing these data structures and algorithms facilitates seamless integration of interactive features, enhancing user engagement and interaction on OTT platforms through responsive and engaging content experiences.

## 📊 Performance Analysis

### Advanced Filtering Options

- **Algorithm Used:** Trie Data Structure
- **Time Complexity:** 
  - Insertion: O(L)
  - Search: O(L)
  - Space Complexity: O(ALPHABET_SIZE * L * N)

### Personalized Playlists

- **Algorithm Used:** Collaborative Filtering
- **Time Complexity:** 
  - Depends on the specific approach (e.g., user-based vs item-based).
  - Typically involves matrix operations with complexity ranging from O(N^2) to O(N^3).
- **Space Complexity:** 
  - Depends on the size of the user-item matrix.

### Mood-Based Recommendations

- **Algorithm Used:** Sentiment Analysis using NLP Techniques
- **Time Complexity:** 
  - Depends on the complexity of the sentiment analysis model.
  - Typically involves processing text with complexity ranging from O(N) to O(N^2).
- **Space Complexity:** 
  - Depends on the size of the sentiment analysis model and input data.
- **Limitations:** 
  - Accuracy may vary based on the quality and diversity of training data.

### Measures Against Piracy

- **Algorithm Used:** Watermarking and Encryption
- **Time Complexity:** 
  - Encryption (e.g., AES): O(N)
  - Watermarking: Depends on the watermarking technique used.
- **Space Complexity:** 
  - Depends on the size of the content and the encryption keys.

### AR and VR Technologies

- **Algorithm Used:** 3D Rendering and Real-Time Processing
- **Time Complexity:** 
  - Rasterization: Typically O(N) to O(N^2) depending on scene complexity.
  - Ray Tracing: O(N^3) or higher, depending on scene complexity and desired quality.
- **Space Complexity:** 
  - Memory-intensive for storing 3D models and textures.
- **Limitations:** 
  - Requires powerful hardware for real-time rendering and processing.

### Virtual Watch Parties

- **Algorithm Used:** Synchronization Algorithms (e.g., Vector Clocks)
- **Time Complexity:** 
  - Depends on the specific synchronization algorithm used.
  - Typically involves operations with complexity ranging from O(N) to O(N^2) depending on the number of participants.
- **Space Complexity:** 
  - Depends on the size of data structures used for maintaining session state.
- **Limitations:** 
  - Scalability challenges with a large number of participants.

### Real-time Chat

- **Algorithm Used:** Message Queues, Pub/Sub Pattern, WebSockets
- **Time Complexity:** 
  - Depends on the efficiency of message queue operations and WebSocket connections.
- **Space Complexity:** 
  - Memory usage scales with the number of active chat participants and message history.

### Personalized Advertising

- **Algorithm Used:** Machine Learning Algorithms (e.g., Decision Trees, Random Forests)
- **Time Complexity:** 
  - Training: Typically O(N * M * log N) to O(N^2 * M), where N is the number of samples and M is the number of features.
  - Inference: Depends on the complexity of the model and input data.
- **Space Complexity:** 
  - Depends on the size of the training data and model parameters.
- **Limitations:** 
  - Privacy concerns and regulatory compliance issues.

### Integration with Smart Home Devices

- **Algorithm Used:** MQTT (Message Queuing Telemetry Transport)
- **Time Complexity:** 
  - Depends on the efficiency of MQTT message handling and network latency.
- **Space Complexity:** 
  - Minimal overhead in terms of memory usage.

### Volume Adjustment

- **Algorithm Used:** Digital Signal Processing (DSP), Finite Impulse Response (FIR) Filters
- **Time Complexity:** 
  - DSP operations: Depends on the complexity of signal processing algorithms (typically O(N) to O(N^2)).
- **Space Complexity:** 
  - Memory usage scales with the size of audio samples and processing buffers.

### Multi-language Support

- **Algorithm Used:** Hash Tables, Trie Data Structures, N-gram Language Models
- **Time Complexity:** 
  - Varies based on the specific algorithm (e.g., O(L) for trie operations, O(N) for language detection using N-grams).
- **Space Complexity:** 
  - Depends on the size of language models and data structures used for text storage.
- **Limitations:** 
  - Accuracy may be affected by linguistic variations and context.

### AI-generated Subtitles and Dubbing

- **Algorithm Used:** Sequence Alignment (e.g., Needleman-Wunsch), Machine Learning Models (e.g., Seq2Seq)
- **Time Complexity:** 
  - Depends on the complexity of alignment algorithms (e.g., O(N*M) for Needleman-Wunsch) and training/inference time for machine learning models.
- **Space Complexity:** 
  - Memory-intensive for storing model parameters and processing input data.

### Interactive Content

- **Algorithm Used:** Hash Tables, Graph Algorithms, Real-time Data Processing
- **Time Complexity:** 
  - Depends on the specific algorithm used (e.g., O(1) for hash table operations, O(N^2) for graph traversal).
- **Space Complexity:** 
  - Memory usage scales with the size of interactive content data and active user sessions.

## 📚 References

1. "Streaming Media" Website, [link](https://www.streamingmedia.com/).

2. "What is OTT (Over-The-Top) and How Does it Relate to Apps?" Article, [link](https://clevertap.com/blog/ott/).

