# DinoAR Explorer – Marker-Based Augmented Reality Dinosaur Experience

Interactive marker-based mobile AR dinosaur experience built with Unity AR Foundation and Unity Visual Scripting.

---

# Project Overview

DinoAR Explorer is a marker-based mobile Augmented Reality (AR) application developed using Unity 2022.3 LTS and Unity Visual Scripting.

The application allows users to scan physical image markers and visualize animated 3D dinosaur models directly within real-world environments using a mobile device camera.

The system combines:

* real-time image tracking
* interactive UI systems
* animation control
* audio interaction
* educational information panels
* immersive multimedia interaction

Users can select dinosaur species from a menu scene, including:

* T-Rex
* Triceratops

Once the marker is detected, the application displays and aligns the dinosaur model while maintaining stable positioning during camera movement.

The project focuses on:

* mobile XR interaction design
* event-driven interaction systems
* educational AR experiences
* multimedia engagement
* real-time AR rendering

---

# Demo Video

[Watch AR Application Demo](https://drive.google.com/file/d/1emqKenIPEcuUGK0gbaxVRZcLE2ZKkdH4/view?usp=sharing)

---

# Technologies Used

## Engine

* Unity 2022.3 LTS

## Programming & Logic Systems

* Unity Visual Scripting
* C#

## XR Frameworks / SDKs

* Unity AR Foundation
* ARCore
* XR Plugin Management

## APIs / Frameworks

* Unity Animator System
* Unity AudioSource System
* Unity UI System
* Unity Scene Management
* Unity EventSystem
* TextMeshPro

## Platform

* Android Mobile AR

---

# Core Features

## Marker-Based AR Tracking

* Real-time image marker detection
* Stable AR object placement
* Continuous marker alignment during camera movement

---

## Interactive Dinosaur Experience

* Animated dinosaur models
* Dinosaur roar sound effects
* Educational information panels
* Skeleton-to-revived dinosaur transformation interaction

---

## Mobile XR UI System

* Touch-based interaction controls
* Mobile-friendly button layout
* Dynamic information panel system
* Event-driven interaction workflow

---

## Dinosaur Selection System

* Menu-based dinosaur selection
* Multiple dinosaur species support
* Scene transition workflow

---

# XR Interaction Workflow

The application uses a marker-based interaction pipeline:

1. User opens the AR scene
2. Mobile camera scans image marker
3. AR Foundation detects tracked image
4. Dinosaur model appears in AR space
5. Interactive UI buttons become available

Users can then:

* trigger animations
* play dinosaur roar audio
* toggle educational information panels
* activate dinosaur revive transformation
* reset scenes and return to menu

---

# Technical Highlights

* Developed marker-based mobile AR application using Unity AR Foundation and Unity Visual Scripting
* Implemented event-driven interaction systems entirely using Unity Visual Scripting
* Built interactive multimedia workflows including animation control, audio playback, and dynamic UI systems
* Designed skeleton-to-revived dinosaur transformation mechanics for immersive AR interaction
* Created runtime object initialization systems using tag-based reference management
* Engineered responsive mobile XR interfaces optimized for touch interaction
* Optimized AR tracking stability and mobile rendering performance for Android deployment
* Integrated scene management workflows and runtime interaction synchronization systems

---

# AR Tracking System

The application uses Unity AR Foundation image tracking to anchor dinosaur models onto physical markers in real time.

The tracking system supports:

* real-time tracked image recognition
* continuous transform synchronization
* stable object placement
* camera movement alignment

Core AR Foundation components include:

* XR Origin
* AR Session
* AR Camera
* AR Tracked Image Manager
* Reference Image Library

Tracking performance was improved through:

* high-contrast image markers
* marker scale calibration
* lighting condition adjustments
* runtime alignment tuning

---

# Unity Visual Scripting Architecture

The interaction system was implemented primarily using Unity Visual Scripting.

The project includes dedicated interaction graphs for:

* animation control
* audio playback
* information panel toggling
* revive transformation workflow
* scene reset management

The interaction pipeline follows:

User Input → Event Trigger → Visual Scripting Graph → Runtime Component Action

Interaction logic includes:

* Animator speed toggling
* AudioSource playback triggering
* Set Active visibility toggling
* Negate node boolean switching
* Scene Manager scene loading

This architecture enabled modular and event-driven XR interaction workflows without relying heavily on traditional scripting systems.

---

# User Experience & Interaction Design

The application was designed to provide:

* intuitive touch interaction
* responsive multimedia feedback
* immersive educational AR experiences
* accessible mobile XR usability

Design considerations included:

* large mobile-friendly buttons
* simplified interaction layout
* side-screen UI placement
* unobstructed AR object visibility

Immersion was improved through:

* animated dinosaur behavior
* synchronized audio feedback
* interactive transformation mechanics
* real-time AR visualization

---

# Optimization Techniques

The project includes multiple mobile optimization techniques including:

* reduced polygon complexity
* optimized texture sizes
* lightweight Visual Scripting graphs
* controlled multimedia playback
* asset compression techniques
* Android-focused build optimization

AR tracking performance was improved through:

* high-contrast marker calibration
* optimized image tracking setup
* runtime tracking stabilization

---

# Evaluation & Testing

The application was tested for:

* image tracking accuracy
* AR object alignment stability
* animation playback responsiveness
* audio interaction reliability
* mobile touch interaction accuracy
* runtime UI functionality
* scene transition behavior
* Android deployment compatibility

User testing validated:

* intuitive interaction flow
* responsive UI behavior
* effective educational engagement
* stable AR visualization

---

# Resume-Relevant Technologies

* Augmented Reality (AR)
* Extended Reality (XR)
* Unity Development
* Mobile XR
* Marker-Based Tracking
* Unity AR Foundation
* ARCore
* Unity Visual Scripting
* Interactive Multimedia Systems
* Event-Driven Interaction
* Real-Time Rendering
* Mobile UI Design
* Animation Systems
* Educational XR Applications

---

# Future Improvements

Potential future enhancements include:

* additional dinosaur species
* markerless AR support
* multiplayer AR interaction
* voice interaction systems
* cloud-based content updates
* advanced AR environment interaction
* enhanced mobile performance optimization

---

# Disclaimer

This repository is intended as a project showcase and portfolio demonstration.

Implementation details, Unity project assets, and proprietary source code components are intentionally omitted.
