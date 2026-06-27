# VigIQ-Vigilance-Intelligence-
AI-powered retail loss prevention system.  Detects shoplifting behavior in real-time using  pose estimation and behavior analysis on existing  CCTV infrastructure. Built for emerging markets.
# VigIQ

> Stop revenue leakage before it walks out the door.

Built for emerging markets where global solutions are 
too expensive and too complex.

## How It Works
- Connects to existing IP cameras via RTSP
- Runs YOLOv11-pose to extract human keypoints per frame
- LSTM classifier analyzes keypoint trajectories over time
- Rule-based filter removes false positives
- Real-time alert sent to staff dashboard with video clip

## Stack
- YOLOv11-pose — human detection + keypoint extraction
- ByteTrack — multi-person tracking
- LSTM — temporal behavior classification
- FastAPI — backend
- Simple HTML/JS — staff dashboard

## Status
✅ Stage 1 — Data Assessment (1408 clips)
✅ Stage 2 — Keypoint Extraction (normalized)
✅ Stage 3 — LSTM Training (82% accuracy)
✅ Stage 4 — Rule Layer
✅ Stage 5 — Real Time Inference Pipeline
🔧 Stage 6 — Alert System + Dashboard
🔧 Stage 7 — Demo
