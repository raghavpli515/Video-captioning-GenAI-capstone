# Video-captioning-GenAI-capstone
“Capstone project combining self-supervised learning with generative models to understand and caption human actions in video.”

# Self-Supervised Action Understanding and Caption Generation

> Capstone project that integrates self-supervised learning (SSL) with generative models for understanding and describing human actions in videos.

## 🔍 Project Description
This project explores the fusion of self-supervised video representation learning with generative AI models for generating contextual captions and reasoning over video frames. It is designed to demonstrate advanced techniques in visual computing and GenAI for applications in surveillance, sports analysis, and behavioral scene understanding.

## 🏗️ Architecture
- Video frames are sampled and encoded using SSL-based temporal encoders (VideoMAE, MoCo).
- Keyframe embeddings are passed to BLIP2 / MiniGPT for caption generation.
