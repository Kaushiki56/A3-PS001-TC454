# AIORI-3-HACKATHON-PROJECTS
This repository will contain the code and resources for the AIORI-3 hackathon that will be developed during the AIORI-3

# Team Ransom Radar

## AIORI-3 Hackathon

**Team Code:** A3-PS001-TC454

**Problem Statement:**  
PS-001 — Android Ransomware-Like Activity Early Warning in a Controlled Lab

## Team Introduction Video

[Watch our team introduction video on YouTube] https://youtu.be/0wo6uhUGYaI?si=-_rQ1NGfszk4kQuk

## About Our Team

Meet Team Ransom Radar, participating in the AIORI-3 Hackathon.

In our team introduction video, we explain the problem of Android ransomware-like activity and present our proposed approach for detecting suspicious behaviour before widespread file damage occurs.

## Team Members

| Name | Role |
|Dr. Prithwineel Paul | Faculty Mentor |
| Kaushiki Chowdhury | Detection Research and Threat-Model Design |
| Soutri Bose | Android Implementation and Evaluation |

## Problem Understanding

Android ransomware-like applications may rapidly modify, encrypt, delete, or lock access to files. If these activities are detected too late, users may lose important data.

Our goal is to identify suspicious behaviour at an early stage and generate an understandable warning before extensive file damage occurs.

## Proposed Approach

We plan to develop an Android early-warning prototype using:

- Canary files to act as early indicators of suspicious activity
- `FileObserver` monitoring for unusual file changes
- File-operation and system-call analysis
- File entropy checking to identify possible encryption activity
- Explainable risk scoring
- Early alerts and activity logging

## Controlled Laboratory Environment

Testing will be performed safely in a controlled laboratory environment using:

- A rooted Android emulator
- Dummy and non-sensitive files
- Safe, authorized test applications
- Simulated ransomware-like file operations

No real ransomware or unauthorized applications will be used.

## Project Objective

Our objective is to achieve:

1. Early detection of ransomware-like activity
2. Explainable security alerts
3. Minimal file damage during suspicious activity
4. Safe and reproducible evaluation in a controlled lab

## Keywords

AIORI-3, Ransom Radar, Android Security, Cybersecurity, Ransomware Detection, Early Warning System
