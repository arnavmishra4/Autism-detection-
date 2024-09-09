# Autism-detection-

# Object Detection and Autism Detection Model

## Overview
This project focuses on developing a reliable model for detecting children and adults, with a specific application in autism detection. The approach combines various state-of-the-art models to achieve accurate and efficient results.

## Approach

### 1. TensorFlow Object Detection Modules
- *Initial Exploration*: 
  - Started with TensorFlow Object Detection modules to achieve accurate detection.
- *Challenges Faced*: 
  - Encountered limitations in accuracy and efficiency despite extensive experimentation.
- *Decision to Pivot*: 
  - Recognized the need for a more robust solution, prompting a reevaluation of the methodology.

### 2. YOLOv8n Model
- *Strategic Transition*: 
  - Transitioned to the YOLOv8n model, known for its speed and accuracy in real-time object detection.
- *Custom Dataset Creation*: 
  - Curated a diverse dataset featuring children and adults to enhance generalization capabilities.
- *Improved Performance*: 
  - Achieved significantly higher detection accuracy and a streamlined inference process, making it suitable for real-world applications.

### 3. YOLOv8 with DeepSORT
- *Integration for Tracking*: 
  - Combined YOLOv8 with DeepSORT for assigning unique IDs to detected individuals.
- *Efficient Tracking*: 
  - Enabled continuous tracking of individuals throughout video sequences, crucial for autism-related applications.
- *Enhanced Reliability*: 
  - Improved both object detection accuracy and reliability of tracking over time.

### 4. Decision Tree Classifier for Autism Detection
- *Complementary Model*: 
  - Implemented a Decision Tree Classifier to analyze behavior-related data and predict autism.
- *Complex Relationship Modeling*: 
  - Leveraged insights from tracked individuals to model complex behaviors and interactions effectively.
- *Comprehensive Solution*: 
  - Developed a robust solution capable of monitoring and analyzing behaviors of children and adults in various scenarios.

## Conclusion
This multifaceted approach successfully integrates object detection, tracking, and behavioral analysis to create an effective model for monitoring individuals, particularly in the context of autism detection. The results demonstrate improved accuracy and efficiency, highlighting the potential of combining advanced technologies for real-world applications.
