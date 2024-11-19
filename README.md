# YouTube Video Summarizer with MLOps

An advanced YouTube video summarization tool that leverages Groq's LLM capabilities and MLOps practices to generate high-quality summaries of YouTube videos from their transcripts.

## 🌟 Features

- Extract transcripts from YouTube videos automatically
- Generate concise, accurate summaries using Groq's LLM
- Track and version experiments using MLflow
- Evaluate summary quality using ROUGE scores
- Visualize performance metrics and length comparisons
- Reproducible MLOps pipeline

## 📋 Prerequisites

- Python 3.8+
- Groq API key
- YouTube Data API access (optional)

## 🛠️ Installation

1. Clone the repository:
```bash
git clone [your-repo-url]
cd llmops-youtube-summarizer
```

2. Install dependencies:
```bash
pip install -r requirements.txt
```

3. Set up environment variables:
```bash
cp .env.example .env
```
Edit `.env` and add your Groq API key:
```
GROQ_API_KEY=your_api_key_here
```

## 🚀 Usage

### Quick Start
1. Open and run the `01_PoC.ipynb` notebook for a simple proof-of-concept implementation
2. For the full MLOps pipeline, use `02_MLFlow_implementation.ipynb`

### MLflow Tracking
The project uses MLflow to track:
- Model parameters
- ROUGE scores
- Summary lengths
- Performance metrics

Access the MLflow UI:
```bash
mlflow ui
```

## 📊 Performance Metrics

The project includes several visualization tools:
- `length_comparison.png`: Compare original vs summarized text lengths
- `metrics_distribution.png`: Distribution of various performance metrics
- `rouge_scores.png`: ROUGE score analysis

## 🔧 Dependencies

Key dependencies include:
- youtube-transcript-api >= 0.6.1
- groq >= 0.4.2
- mlflow >= 2.10.0
- pandas >= 2.0.0
- rouge-score >= 0.1.2
- transformers >= 4.30.0

For a complete list, see `requirements.txt`

## 📁 Project Structure

```
.
├── 01_PoC.ipynb                  # Proof of concept implementation
├── 02_MLFlow_implementation.ipynb # MLOps pipeline implementation
├── prompt_template.txt           # LLM prompt engineering template
├── requirements.txt              # Project dependencies
├── mlruns/                      # MLflow experiment tracking
└── example_*/                   # Example outputs and results
```

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## 📝 License

[Your chosen license]

## 🙏 Acknowledgments

- Groq for providing the LLM API
- YouTube for transcript access
- MLflow for experiment tracking