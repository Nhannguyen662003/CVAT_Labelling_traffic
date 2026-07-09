# Image & Video Annotation with CVAT

A personal project demonstrating hands-on experience with [CVAT](https://www.cvat.ai/) (Computer Vision Annotation Tool) for labeling image and video data, built to support applications for Data Labelling roles.

## Overview

This project showcases the end-to-end annotation workflow using CVAT across two data types — static images and video frames — including object localization, class labeling, and export to a standard format for downstream use.

## Work Performed

- Manually annotated objects in both images and video frames using CVAT.
- Drew **bounding boxes** around target objects.
- Labeled objects across 6 classes, centered on a traffic theme: **Person, Car, Bike, Motorbike, Traffic Light, Animal** (animal species were kept as a single class to stay focused on the traffic domain rather than fine-grained species classification).
- Reviewed and validated annotations prior to export to catch missing or duplicate labels.
- Exported annotation results in the standard **COCO 1.0 (JSON)** format.

## Image Dataset

- **Source:** Pinterest
- **Size:** 10 images
- **Method:** each image annotated independently with bounding boxes
- **Output:** `image_annotations.json`

## Video Dataset

- **Source:** Pexels
- **Size:** 1 video, 50 extracted frames (frame 0–49)
- **Method:** Shape (each frame annotated independently with bounding boxes)
- **Output:** `video_annotations.json`

## Workflow

1. Sourced images from Pinterest and a video clip from Pexels.
2. Annotated data in CVAT — both images and video frames labeled independently with bounding boxes (Shape method), covering 6 traffic-related classes: Person, Car, Bike, Motorbike, Traffic Light, and Animal.
3. Reviewed annotations for consistency and completeness.
4. Exported annotations to COCO JSON format for both datasets.
