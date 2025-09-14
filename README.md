# 🎤 Cold-Calling-Speech-Recognition
Проект по распознаванию тональности в диалогах холодных звонков Клиента и Менеджера (Speech Sentiment & NER Pipeline)

[![Python](https://img.shields.io/badge/python-3.10%2B-blue)](https://www.python.org/)  
[![Whisper](https://img.shields.io/badge/OpenAI-Whisper-green)](https://github.com/openai/whisper)  
[![HuggingFace](https://img.shields.io/badge/HuggingFace-Transformers-yellow)](https://huggingface.co/transformers/)  
[![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange)](https://jupyter.org/)  

## 📌 Описание  
Этот проект предназначен для **распознавания речи и анализа холодных звонков**.  
На вход подаётся запись разговора → на выходе формируется **транскрибированный текст**, в котором:  
- выделяются **ключевые сущности** (*имена, компании, организации, локации*),  
- определяется **тональность речи клиента** (*positive / negative / neutral*).  

Такой подход помогает автоматизировать обработку звонков и выявлять эмоциональное состояние клиента, сохраняя важный контекст.  

## 🚀 Возможности  
- ✅ **Распознавание речи** с помощью [OpenAI Whisper](https://github.com/openai/whisper).  
- ✅ **Оценка тональности холодных звонков** — быстрое определение реакции клиента.  
- ✅ **NER (Named Entity Recognition)** — извлечение имён, компаний и других сущностей из речи.  
- ✅ **Sentiment Analysis** — классификация эмоциональной окраски: положительная, отрицательная, нейтральная.  
- ✅ Возможность масштабирования для построения дашбордов и автоматических отчётов по звонкам.  

## 🛠️ Технологии  
- Python 3.10+  
- Jupyter Notebook  
- [Whisper](https://github.com/openai/whisper) (ASR)  
- HuggingFace Transformers / spaCy / DeepPavlov (NER + Sentiment)  

## 📂 Структура проекта  
- `Whisper_speech.ipynb` → транскрибация аудио в текст.  
- `Sentiment_NER_speech.ipynb` → анализ текста (NER + Sentiment).  

## 🔧 Установка  
```bash
git clone https://github.com/username/speech-sentiment-ner.git
cd speech-sentiment-ner
pip install -r requirements.txt

