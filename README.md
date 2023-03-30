# [Project Name]

Hacked together by [Team Name]

## Introduction

The goal of this project, inspired by the Byte Into Hardware Hackathon hosted at NJIT in Spring 2023, is to create frames that provide feedback on objects outside the user's peripheral vision, particularly targeted towards an audience with hearing impairments. This will help reduce anxiety by minimizing instances of being caught off guard. The frames will utilize two cameras for object recognition and depth mapping, enhancing the user's awareness of their surroundings.

## Indicator System

The indicator system will consist of a light bar with multiple LEDs to create an effective pixel, indicating the position of the nearest object behind the user. The number of lit pixels can represent the object's distance. As the user gets closer to an object, the indicator system expands, providing an intuitive design and error tolerance.

## Light Bar Placement

The light bar will be placed on the top frame of the glasses to minimize twists in the filament.

## Sensor

The primary sensor data will be obtained using two ESP32-CAMs for object recognition and depth mapping. Capturing images simultaneously from their respective URLs, these cameras will provide information on the position and distance of objects behind the user. Ultrasonic sensors will be considered if space allows and is deemed necessary.

## Features

- LED indicators display position/distance of nearest object
- Object recognition and depth mapping using two ESP32-CAMs
- Adaptable for many use cases

## Use Cases

Besides assisting individuals with hearing impairments, these frames can also be used in surveillance and public safety applications, such as helping law enforcement detect potential threats in crowded areas using object recognition and depth mapping capabilities.

## Contribution Guidelines

We welcome contributions from the open source community to help improve and expand the functionality of the project. To contribute, please follow the guidelines outlined in `CONTRIBUTING.md`.

## License

This project is licensed under the [Apache License 2.0](LICENSE).
