
# MediAssist AI
## Multimodal Healthcare Assistant using NLP, OCR and Speech AI

## Project Overview
MediAssist AI is an AI healthcare assistant that accepts multiple input formats:

- Text input → BERT based Question Answering
- Image input → OCR extraction → NLP processing
- Voice input → Whisper Speech Recognition → NLP response → Text To Speech

## Current Development Progress

Completed:
- Exploratory Data Analysis for text data
- Exploratory Data Analysis for image data
- Exploratory Data Analysis for audio data
- BERT based Question Answering experiment
- Whisper STT + BERT + TTS experiment

## Project Structure

```
MediAssist_AI/
│
├── notebooks/
│   ├── QnA_using_BERT.ipynb
│   ├── STT_BERT_TTS.ipynb
│   ├── Exploratory_Data_Analysis.ipynb
│   ├── Exploratory_Data_Analysis(Image).ipynb
│   └── Exploratory_Data_Analysis(Audio).ipynb
│
├── src/
│   ├── text_processing/
│   │   └── bert_qa.py
│   ├── image_processing/
│   │   └── ocr_pipeline.py
│   ├── audio_processing/
│   │   ├── whisper_pipeline.py
│   │   └── tts_pipeline.py
│   └── utils/
│       └── config.py
|
├── app.py
└── requirements.txt
```

## Future Development Roadmap

1. Convert notebook experiments into production modules
2. Add medical dataset and fine tune models
3. Add multilingual support
4. Add prescription understanding
5. Add medication reminder system
6. Deploy using FastAPI and mobile application

## Installation

```bash
pip install -r requirements.txt
python app.py
```

## Technology Stack

Python  
BERT / Transformers  
Whisper ASR  
OCR  
PyTorch  
NLP  
Speech Processing  
