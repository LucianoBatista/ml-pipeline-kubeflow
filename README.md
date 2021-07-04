# EyeSpy

Provides security solutions for university campuses, office buildings, and sensitive installations.

**Core product**:
- EyeSpy LittleEye 360

**Objective**:
Powers security camera products that are used primarily for facial recognition and intruder detection.

**New demand**:
Automatic livence plate recognition (ALPR). Checking the license plate of every vehicle entering a building is very manual, we want automate this.

**Modeling**:
Extract the bounding boxes from license plates and applying OCR to remove the plate content.

**Issues without MLOps:**
1. The code only runs on the team's respective laptops
2. Training the model involves many steps and is error-prone
3. There's no fixed storage location for the models and other artifacts.
4. There's no way to compare models done by other ds outside the company
5. There's no easy way to experiment with different network architectures and configs.
6. Its not clear how to perform retraining of the model when new data comes in
7. Oftentimes code has been duplicated, since little of the code has been made reusable, resulting in wasted time and effort.
8. There's no easy way to visually see how the model performs.



