# FACIAL EXPRESSION BASED EMOTION DETECTION AND AUTOMATIC PLAYLIST GENERATION

## About
Music plays a very important role in enhancing an individual‘s life as it is an important
medium of entertainment for music lovers and listeners and sometimes even imparts a
therapeutic approach. In today‘s world, with ever increasing advancements in the field
of multimedia and technology, various music players have been developed with
features like fast forward, reverse, variable playback speed (seek & time
compression),local playback, streaming playback with multicast streams. Although
these features satisfy the user‘s basic requirements, yet the user has to face the task of
manually browsing through the playlist of songs and select songs based on his current
mood and behaviour. The introduction of Audio Emotion Recognition (AER) and Music
Information Retrieval (MIR) in the traditional music players provided automatically
parsing the playlist based on various classes of emotions and moods. AER is a technique which deals with classifying a received audio signal, by considering
its various audio features into various classes of emotions and moods, whereas MIR is
a field that extracts some critical information from an audio signal by exploring some
audio features like pitch ,energy,MFCC, flux etc.Though both AER and MIR included the
capabilities of avoiding manual segregation of songs and generation of playlist, yet it is
unable to incorporate fully a human emotion controlled music player. Although human
speech and gesture are a common way of expressing emotions, but facial expression is
the most ancient and natural way of expressing feelings, emotions and mood. The main objective of this paper is to design an efficient and accurate algorithm that
would generate a playlist based on current emotional state and behaviour of the user. The algorithm designed requires less memory overheads, less computational and
processing time, reducing the cost of any additional hardware like EEG or sensors. The facial expression would categorize into 5 different types of facial expressions like
anger, joy, surprise, sad, and excitement. A high accurate audio extraction technique is
proposed that extracts significant, critical and relevant information from an audio
signal based on certain audio features in a much lesser time. An emotion model is proposed that classifies a song based on any of the 7 classes of
emotions viz sad, joy-anger, joy-surprise, joy-excitement, joy, anger, and sad-anger. The emotion extraction module and audio feature extraction module is combined
using an Emotion-Audio integration module.


## Features

Based on the introduction provided, here are some features for your project:

Facial Expression Recognition (FER):
Implement a system to accurately detect and classify facial expressions into predefined emotional states such as anger, joy, surprise, sadness, and excitement.

Real-time Emotion Detection:
Develop algorithms for real-time detection of facial expressions to capture the user's current emotional state as accurately as possible.

Audio Feature Extraction:
Extract relevant audio features such as pitch, energy, MFCC (Mel-frequency cepstral coefficients), and flux from the music tracks to capture their emotional content.

Emotion Model Integration:
Create a model that integrates facial expression recognition results with audio feature extraction to classify songs into emotional categories like sad, joy-anger, joy-surprise, joy-excitement, joy, anger, and sad-anger.

Playlist Generation:
Design algorithms to generate playlists dynamically based on the user's current emotional state and behavior inferred from facial expressions.

Efficient Algorithm Design:
Develop efficient algorithms with low memory overhead, minimal computational complexity, and reduced processing time to ensure smooth real-time performance on various devices.

User Interface (UI):
Create an intuitive user interface that allows users to interact with the system easily, providing feedback on the detected emotional states and the generated playlists.

## Requirements
* Operating System: Requires a 64-bit OS (Windows 10 or Ubuntu) for compatibility with deep learning frameworks and video processing.
* Development Environment: Python 3.6 or later is necessary for coding the animal intrusion alerting system.
* Deep Learning Frameworks: Utilizes OpenCV's DNN module for implementing the YOLO algorithm and TensorFlow for any additional deep learning tasks.
* Audio Processing: Requires Pygame for playing alarm sounds.
* Email Communication: Utilizes SMTP protocol for sending email notifications, requiring smtplib and email.message modules.
* Multithreading: Utilizes threading module for asynchronous email sending to avoid blocking the main thread.
* Video Processing: Requires OpenCV for video capture, processing, and displaying output frames.
* External Libraries: Playsound for playing alarm sounds, imghdr for image attachment verification in email notifications.
* Dependencies: NumPy for numerical computations, scikit-learn for any machine learning tasks, and playsound for audio playback.
* Integrated Development Environment (IDE): Supports any Python-compatible IDE, such as VSCode or PyCharm, for coding, debugging, and version control integration.

## System Architecture
<!--Embed the system architecture diagram as shown below-->

![image](https://github.com/Saran408/Playlist-Generation/assets/75235427/2ecbe41b-8ee6-4473-b214-2830be2d5c6e)



## Output

#### Output1 - Fearful Emotion playlist generation

![image](https://github.com/Saran408/Playlist-Generation/assets/75235427/92b9eb3e-5c61-49f9-813b-320d3fdbeea6)




#### Output2 - Happy Emotion playlist generation

![image](https://github.com/Saran408/Playlist-Generation/assets/75235427/c6ceaced-9454-445f-a597-3c37e00514c1)




## Results and Impact
The Emotion-Based Music Player system embodies a groundbreaking fusion of cutting-edge technology and human emotion, revolutionizing the traditional music listening experience. 

By harnessing the power of facial expression analysis, the
system adeptly deciphers users' emotional states in real-time, allowing for the creation
of dynamically tailored playlists that resonate with their mood and disposition. Through
meticulous model training and validation, coupled with the intelligent mapping of
emotions to music selections, the system ensures a deeply personalized and immersive
music journey for each user. 

Furthermore, the seamless integration of user-friendly
interface design facilitates effortless interaction, empowering users to seamlessly
navigate their emotional landscapes and curate their musical ambiance with
unprecedented ease.

## References
[1] ⦁ Kabani, Hafeez, Sharik Khan, Omar Khan, and Shabana Tadvi. "Emotion based music player." International journal of engineering research and general science 3, no. 1 (2015): 2091-2730.

[2] ⦁ Chankuptarat, Krittrin, Raphatsak Sriwatanaworachai, and Supannada Chotipant. "Emotion-based music player." In 2019 5th International Conference on
Engineering, Applied Sciences and Technology (ICEAST), pp. 1-4. IEEE, 2019.

[3] ⦁ Nathan, Karthik Subramanian, Manasi Arun, and Megala S. Kannan. "EMOSIC—An emotion based music player for Android." In 2017 IEEE International Symposium on Signal Processing and Information Technology(ISSPIT), pp. 371-276. IEEE, 2017.

[4] ⦁ Sahare, R. K., Isha Bhoyar, Diksha Borkar, Amruta Shedame, Achal Deotale, and Sheetal Mistry. "Emotion based music player." (2023). 

[5] ⦁ Gupte, Aditya, Arjun Naganarayanan, and Manish Krishnan. "Emotion based music player-xbeats." International Journal of Advanced Engineering Research and Science 3, no. 9 (2016): 236854.

[6] ⦁ Bali, Vinayak, Shubham Haval, Snehal Patil, and R. Priyambiga. "Emotion based music player." emotion 9 (2019): 8.

[7] ⦁ Kalpande, Sarthak, Ramkrishna Allampallewar, Prathamesh Vyavhare, Arun
Kinwad, and Saurabh Sargaiyye. "Emotion Based Music Player.“
