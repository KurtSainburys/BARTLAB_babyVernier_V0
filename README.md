#BARTLAB BabyVernier V0
An Alternative Non-Contact Anthropometric Measurement System

The BARTLAB BabyVernier V0 is the inaugural version of a specialized anthropometric measurement system developed by BART LAB. It is designed to provide a gentle, non-contact alternative to traditional physical calipers, specifically for children with physical or neurodevelopmental disabilities who may find prolonged physical contact distressing or uncomfortable.

Current Implementation
The current iteration utilizes ArUco markers, which are low-cost, high-reliability fiducial markers, placed at key anatomical points. By tracking these markers via computer vision, the system calculates precise distances between limbs and body segments, significantly reducing the need for manual measurement tools.

Roadmap for Future Development
As the project evolves, we encourage future developers to focus on the following pillars:

Problem-Centric Design: Always prioritize the core clinical problem—minimizing patient distress while maintaining measurement accuracy.

Zero-Contact Evolution: While ArUco markers are effective, future versions should aim to eliminate physical markers entirely to remove the need for any direct skin contact.

Sensor Fusion & ML Integration: We propose integrating Google’s MediaPipe Pose Landmarker alongside a "known distance" reference (like a single static scale marker) to enable markerless 3D skeletal tracking.
