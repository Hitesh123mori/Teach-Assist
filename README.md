﻿# Lords Of Westeros

### Team Members
- **Niraj Chaudhari**
- **Hitesh Mori**
- **Jishan Thobhani**
- **Ankit Pandor**

---

## Problem Statement: Customizable Classroom Management for Teachers

Our project focuses on developing a **Customizable Classroom Management Tool** designed to assist teachers in managing their classrooms more efficiently. This tool includes features for attendance tracking, homework assignment management, lecture summarization, and AI-powered resource suggestions for student improvement.

### User Roles:
- **Student**
- **Teacher**

---

📸 **App Screenshots**  
Take a look at the key features and interface of TeachAssists in action.

🔗 [Click here to view the TeachAssists screenshots](https://drive.google.com/file/d/1aOhKV4qbhwLtuCDw4JAINEMU6N-kjR4R/view?usp=sharing)

## Features Implementation Status

### 1. Attendance Tracking Using Geolocation
- **Student Attendance:** Geolocation is used to track whether students are within the designated area during class hours. If a student remains within the geofenced area for a specified duration, they are automatically marked present; otherwise, they are marked absent.
- **Custom Geofence:** Each class can have a different geolocation range, customized according to the teacher's requirements. This prevents proxy attendance and ensures accurate tracking.
<div style="display: flex; justify-content: space-between;">
    <img src="https://assets.leetcode.com/users/images/9e55188b-b261-4e85-aaff-99f1107db3c4_1727537066.6194813.jpeg" alt="Geolocation Example 1" width="32%" />
    <img src="https://assets.leetcode.com/users/images/fd06be5b-ce9a-4e63-8763-414352629acd_1727536352.180298.jpeg" alt="Geolocation Example 2" width="32%" />
</div>

### 2. Lecture Summarizer & Self-Evaluation
- **Automated Text Notes:** After the completion of a video lecture, the system automatically generates text notes for students to better understand the content.
- **Self-Evaluation Tests:** After the lecture, students can access auto-generated tests to evaluate their understanding of the material covered.

### 3. Homework Assignment Management
- **Assignment Upload:** Students can upload their assignments digitally onto the platform.
- **AI-Based Evaluation:** Assignments are evaluated using AI, with corresponding marks awarded to the student.
- **Manual Verification:** Teachers can manually verify the AI evaluation if needed.

### 4. Announcements and Notifications
- **Student Notifications:** Students receive notifications for upcoming online tests, low attendance warnings, and pending assignment submissions.
- **Teacher Notifications:** Teachers are notified when a student has not submitted an assignment within the due date.

### 5. Customizable Dashboard
A personalized dashboard is available for both students and teachers, providing an overview of progress, upcoming events, and notifications.
# Teacher's Screen
<div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 10px;">
    <!-- First Row -->
    <img src="https://assets.leetcode.com/users/images/42408edc-0f3e-45ad-969b-7da92d470d24_1727537329.8275836.jpeg" alt="img2" width="32%" />
    <img src="https://assets.leetcode.com/users/images/f237f477-0110-4ebc-b25f-24c4c9491bb2_1727537330.0615456.jpeg" alt="img3" width="32%" />
    <img src="https://assets.leetcode.com/users/images/670ffbe3-66cb-4186-85b3-02407e52d873_1727537330.156631.jpeg" alt="img4" width="32%" />
    
</div>
<div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 10px;">
<img src="https://assets.leetcode.com/users/images/1c774adb-8945-4ebc-8b20-cd758282c63e_1727537330.2552488.jpeg" alt="img5" width="32%" />
    <img src="https://assets.leetcode.com/users/images/867bf085-9c24-494b-813f-44e239315637_1727537330.4748924.jpeg" alt="img6" width="32%" />
    <img src="https://assets.leetcode.com/users/images/f89eae11-701d-4eb1-80aa-26a7e8a93994_1727537330.4857228.jpeg" alt="img7" width="32%" />
</div>

# Student's Screen
<div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 10px;">
    <!-- First Row -->
    <img src="https://assets.leetcode.com/users/images/4aec9c74-806d-4660-ad61-1e8a7f50a15c_1727609278.3169372.jpeg" alt="img2" width="32%" />
    <img src="https://assets.leetcode.com/users/images/e82b12d5-1a08-4457-ab88-5308fcb99be6_1727609413.9710813.jpeg" alt="img3" width="32%" />
    <img src="https://assets.leetcode.com/users/images/9e97cca0-4081-4710-9035-8f52b905f781_1727609445.2808425.jpeg" alt="img4" width="32%" />
    
</div>

# Course Screen
<div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 10px;">
    <!-- First Row -->
    <img src="https://assets.leetcode.com/users/images/f701c803-5bfe-44b0-914a-c8c0b51acc82_1727609811.0174894.jpeg" alt="img2" width="32%" />
    <img src="https://assets.leetcode.com/users/images/96afd57b-4c88-4010-8a48-440ede47ab84_1727609838.439835.jpeg" alt="img3" width="32%" />
    <img src="https://assets.leetcode.com/users/images/3c2520e3-5765-4f22-aecf-19274854b0ed_1727609829.8812668.jpeg" alt="img4" width="32%" />
    
</div>

# General Screen
<div style="display: flex; flex-wrap: wrap; justify-content: space-between; gap: 10px;">
    <img src="https://assets.leetcode.com/users/images/77418263-0f75-4a6e-8427-23b6a0ee6412_1727609509.7963517.jpeg" alt="img5" width="32%" />
    <img src="https://assets.leetcode.com/users/images/46d9e33e-c237-471f-b595-7354b4a3f580_1727609518.4813654.jpeg" alt="img6" width="32%" />
    <img src="https://assets.leetcode.com/users/images/7624ebeb-239c-40f7-b865-797151900ae1_1727609527.1446333.jpeg" alt="img7" width="32%" />
</div>


### 6. Student Profile & Resource Suggestions
- **Student Overview:** Teachers can analyze a student's profile, including marks, performance, and attendance records.
- **AI Resource Suggestions:** Based on performance analysis, the system suggests relevant study materials for students who are struggling in particular subjects.

---

## What's Next?
- Improving the AI Assignment Evaluation Model to handle more complex assignments.
- Enhancing the Lecture Summarizer with more detailed summaries and key point extraction.
- Further Testing of Geolocation Attendance to ensure accuracy and reliability in different environments.
- **UI/UX Refinement** to improve user experience and dashboard functionality.

---

## Challenges Encountered
- **Geolocation Accuracy:** Some difficulties have arisen in tracking precise student locations during classes, especially in urban areas with signal interference.
- **AI Self-Evaluation:** Fine-tuning the AI to evaluate a wide range of assignment formats effectively.

---

## Conclusion
We are making steady progress in the development of our customizable classroom management tool, focusing on features that reduce manual work for teachers and enhance student engagement through automated tools.

---

For Video Demonstration: [Watch the video](https://youtu.be/xHnUr8TNTiI?si=nuxka5wOtdPg-tAJ).



