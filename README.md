# Nanoncf

A nano implementation of Neural Collaborative Filtering (NCF) that runs on CPU.

Welcome! This project provides a minimal, educational Python and React/Next.js demonstration of Neural Collaborative Filtering—a modern approach for building recommender systems. By focusing on practical simplicity, this repo helps you understand the essential ingredients needed to experiment, adapt, and learn from NCF without requiring special hardware or massive datasets.

## Key Features and Benefits

- **Runs on standard CPUs**: No GPU required, making machine learning experimentation accessible for everyone.
- **Nano footprint**: Tiny model and codebase mean easier debugging, faster iteration, and straightforward customisation.
- **Educational clarity**: Each file and function is focused on helping you understand the *why* behind NCF.
- **Synthetic data**: Generates OTT, social media, and media-like recommendations so you can learn even without real data.
- **Modern stack**: Next.js frontend, PyTorch backend, and easily deployable to Vercel for sharing and demos.

## Quick Start

```bash
# Install Python dependencies
pip install -r requirements.txt

# Generate synthetic data
ython scripts/generate_synthetic_data.py

# Train a model (optional, pre-trained weights provided)
python scripts/train_model.py

# Install Node dependencies
npm install

# Start Next.js app
npm run dev
# Then open http://localhost:3000
```

## Project Structure

```
.
├── app/              # Next.js UI (pages, config, API endpoints)
├── lib/              # Python NCF model and data generator
├── scripts/          # Training and utility scripts
├── public/           # Static frontend assets, precomputed recommendations
├── models/           # Saved PyTorch weights (generated locally)
├── data/             # Synthetic training/test data (generated locally)
```

## Demo & Documentation
- [Blog: Neural Collaborative Filtering Explained](BLOG_POST.md)
- [Deployment Guide](DEPLOYMENT.md)

## How to Contribute
We encourage issues, questions, and PRs focused on education, usability, or clarity. You are welcome to fork this project and tailor it for your needs—whether for courseware, workshops, or personal study.

## License
MIT—use freely for learning and teaching.

## About
Created as a practical, approachable resource for learning about recommender systems. Ideal for students, data scientists, and engineers interested in recommendation fundamentals, neural networks, and real-world deployment. If you find this useful, share your learnings and results!
