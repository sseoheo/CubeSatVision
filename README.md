# CubeSatVision

AI Processor-Based Vision Navigation System for CubeSats

## Overview

CubeSatVision is an onboard computer vision framework that separates computationally intensive image processing from the onboard computer (OBC).

The AI Processor performs:

- Space Object Detection
- Space Object Tracking
- Star Extraction
- Star Identification
- Plate Solving
- Attitude Determination

The OBC receives processed navigation data and interfaces with spacecraft subsystems such as ADCS and TTC.

## Architecture

Camera

↓

AI Processor

↓

Navigation Solution

↓

OBC

↓

ADCS
