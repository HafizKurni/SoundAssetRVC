# Penerapan Retrieval Voice Conversion untuk Membangun Aset Suara Karakter Monster pada Game

## 📚 **Project Overview**
This project is part of a thesis focused on Retrieval-based Voice Conversion (RVC) to generate monster character voice assets for games.

## 💾 **Dataset Goblin Voice**
The dataset that I use is from scraping audio of anime Goblin Slayer season 1 and 2.
You can access the dataset used for training and evaluation here:

[Goblin Voice Dataset](https://drive.google.com/file/d/1piIAGw8rPlO03f0ywvFIkJwYfYrT5Nln/view?usp=sharing)

## 📊 **Evaluation Metrics**
1. **Mel Cepstral Distortion (MCD):** Measures the quality of voice conversion.
2. **Similarity Percentage:** Calculated using [Sound-Similar Free Application](https://www.virtins.com/VT-Sound-Recognition.html).
3. **FastDTW Alignment:** For better comparison of time-series audio features.

[Evaluation Result](https://docs.google.com/spreadsheets/d/1xEwZtS5WlwOh7m7YUhbK7UmnRgZeuJvCZLxZHC6IKg4/edit?usp=sharing)

## 🎙 **Result Voice Conversion** 
You can listen to sample outputs of the voice conversion here:

[Goblin Voice Conversion](https://drive.google.com/drive/folders/1Y_J2XN6E8X2b0L_Cyd0Md5bK3nvVfNsB?usp=sharing)

## 🚀 **How to Run the Program**
1. Clone the repository.
2. Create virtual enviorment
3. Install dependencies from `requirements-py30819.txt`.
4. Download a model file and put inside assets folder. [Download Model Assets](https://drive.google.com/file/d/1pVKmRoe79pRHC_3qrr574XNogqctdRkv/view?usp=sharing)
5. Just run the app `python -u "infer-webV3Clean.py"`
6. The app will be open as web application.


Program RVC Asset Sound Generation from Hafiz Muhammad Kurniawan
