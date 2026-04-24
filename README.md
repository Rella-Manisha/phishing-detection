# Phishing Detection in Digital Communication

A machine learning system that detects phishing messages
in digital communication using NLP and URL-based features.

## Problem it solves
Phishing attacks trick users through fake messages and URLs.
This system automatically classifies messages as phishing
or legitimate — protecting users from digital fraud.

## How it works
```
Message/URL Input → Feature Extraction → ML Model → Phishing or Legitimate
```

## Features
- Extracts 20+ textual and URL-based features from messages
- Classifies messages as phishing or legitimate
- Achieved ~94% accuracy on test data
- Evaluated using accuracy, precision and recall metrics

## Technologies
| Technology            | Purpose                        |
|-----------------------|--------------------------------|
| Python                | Core programming language      |
| Scikit-learn          | Machine learning model         |
| NLP                   | Text feature extraction        |
| Feature Engineering   | URL and text analysis          |
| Pandas                | Data processing                |

## How to run

### 1. Clone the repo
```bash
git clone https://github.com/Rella-Manisha/phishing-detection.git
cd phishing-detection
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the detector
```bash
python detect.py
```

## Results
| Metric    | Score |
|-----------|-------|
| Accuracy  | ~94%  |
| Precision | ~92%  |
| Recall    | ~93%  |

## Future improvements
- Add browser extension for real-time URL scanning
- Support detection in multiple languages
- Build a web interface for non-technical users
- Add email phishing detection

## Author
**Rella Manisha**  
B.Tech CSE (Cyber Security) — Vignan's Institute of Engineering for Women  
[LinkedIn](https://www.linkedin.com/in/rella-manisha-597943288) | [GitHub](https://github.com/Rella-Manisha)
