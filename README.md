# Shreyas Nimbalkar

AI/ML engineer and M.S. Computer Engineering student at the University of Southern
California.

I like building AI that has to work outside a notebook: computer vision on edge
hardware, LiDAR SLAM, and LLM systems that stay reliable when providers fail or
rate-limit. Before starting at USC I spent a year as an AI/ML engineer at RAMS in Pune,
building a pedestrian-safety system for forklifts that runs detection on camera NPUs
and drives brake relays from a Raspberry Pi hub.

[LinkedIn](https://www.linkedin.com/in/shreyas-nimbalkar-713bb9267/) ·
[Email](mailto:nimbalka@usc.edu)

## Projects

**[Switchboard](https://github.com/shreyasnimbalkar/switchboard-llm-gateway)**: an
OpenAI-compatible LLM gateway in Python (FastAPI, asyncio, SQLite). It routes requests
across Groq, OpenRouter, Gemini and a local Ollama model with fallback chains, handles
rate limits per model using Retry-After and a wait queue, caches repeated requests, and
logs tokens, cost and p50/p95 latency for every call. 52 tests, CI on GitHub Actions.

**[Job Fit Agent](https://github.com/shreyasnimbalkar/-job-fit-agent)**: a five-agent
pipeline on the Claude API that scrapes a job posting, matches each requirement to
quoted evidence in a resume, computes an explainable fit score in code, and writes a
tailored resume that a separate reviewer agent and code-level guards check for
invented facts.

**[Smart Scrub](https://github.com/shreyasnimbalkar/Smart-scrub--automated-data-cleaning)**:
a full-stack web app that uses machine learning to automate large-scale data cleaning.
I published a research paper on it and presented it at the Global Conference on
Sustainable and Futuristic Technologies (2023).

Earlier machine learning work:
[Amazon review sentiment analysis](https://github.com/shreyasnimbalkar/Amazon-review-sentiment-analysis),
[stock market prediction](https://github.com/shreyasnimbalkar/Stock-market-predicition-model),
[employee attrition with an ANN](https://github.com/shreyasnimbalkar/Leaving-Company-Deep-learning-ANN-),
[breast cancer detection](https://github.com/shreyasnimbalkar/Breast-cancer-detection-model),
[dog vs. cat CNN](https://github.com/shreyasnimbalkar/dog-v-s-cat-classification),
[wine quality model](https://github.com/shreyasnimbalkar/wine-model).

## Experience

**AI/ML Engineer, RAMS (Rack Asset and Management System)**, Pune, 09/2025 to 08/2026

- Deployed a uint8-quantized YOLOv7-tiny pedestrian detector on the NPUs of a 5-camera
  forklift rig, publishing detections over MQTT to a Raspberry Pi 5 hub that drives
  fail-safe brake and audio-alert relays.
- Raised in-zone operator detection from 8% to 100% of frames by redesigning the
  danger-zone logic, and cut live video latency to about 150 to 250 ms.
- Built 360° blind-spot detection, a bird's-eye surround view using inverse perspective
  mapping, and AWS IoT Greengrass components on NVIDIA Jetson for forklift telemetry.
- Fine-tuned YOLO11n for helmet and safety-vest detection (0.895 mAP50).
- Wrote a 2D LiDAR SLAM system from scratch in Python/NumPy (19 to 28 ms per scan on a
  Raspberry Pi 5) and brought up a Unitree L2 3D LiDAR on ROS 2 with FAST-LIO.

**Machine Learning Intern, Can Will Technologies**, Pune, 06/2024 to 06/2025

- Built Python models for stock-market trend prediction using sentiment analysis,
  time-series forecasting and support/resistance detection.

## Education

**University of Southern California**, Los Angeles
M.S. in Computer Engineering, 08/2026 to 05/2028 (expected)

**Savitribai Phule Pune University** (MMIT), Pune
B.E. in Computer Science, 2021 to 2024

## Skills

**Languages:** Python, C++, Java, SQL, R

**Machine learning and computer vision:** PyTorch, TensorFlow, Keras, scikit-learn,
OpenCV, YOLO (v5/v7/v8/v11), object detection, transfer learning, INT8 quantization,
time-series forecasting, NLP and sentiment analysis

**LLMs and agents:** Claude and OpenAI-compatible APIs, multi-agent pipelines,
structured outputs, prompt engineering and caching, LLM routing and fallback, Ollama,
vision-language models

**Computer hardware and embedded systems:** NVIDIA Jetson Orin Nano, Raspberry Pi 5 and
Pico, ESP32, Realtek AMB82-mini (NPU camera), Sipeed MaixCAM, LiDAR (Unitree L2,
RPLIDAR A2M12, Benewake TF-Luna), Insta360 X4, GPIO relays, I2C, UART, on-device
inference and profiling, OTA firmware updates

**Robotics:** ROS 2, SLAM (FAST-LIO, scan-to-map matching), rosbag, RViz2, MQTT
(Mosquitto)

**Backend, cloud and tools:** FastAPI, REST APIs, asyncio, AWS IoT Greengrass, AWS EC2,
Docker, Linux, Git, GitHub Actions, pytest, SQLite, Pandas, NumPy, PySpark, Matplotlib,
Jupyter

Open to AI/ML engineering internships and roles.
