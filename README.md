# Smart Air Traffic System  
**NLP‑Based Automatic Speech Recognition for Air Traffic Control**

## Overview  
This project integrates advanced **Artificial Intelligence** and **Natural Language Processing (NLP)** techniques to enhance air‑traffic‑control (ATC) communications. It features modules for speech recognition, language understanding, and language generation designed specifically for ATC environments — improving clarity, safety, and workflow efficiency.

## Features  
- Automatic Speech Recognition (ASR) tailored to noisy ATC audio  
- Natural Language Understanding (NLU) for instruction classification  
- Natural Language Generation (NLG) for context‑aware automated responses  
- Real‑time data processing and noise‑cancellation optimised for aviation use  

## Technologies Used  
- Programming Language: **Python**  
- Frameworks / Libraries: TensorFlow, HuggingFace Transformers, XLSR‑Wav2Vec2, PyTorch  
- Notebooks: Data preprocessing, ASR/NLU/NLG modules implemented as Jupyter Notebooks  

## Use Cases  
- Enhancing communications in ATC towers and centres  
- Real‑time safety monitoring and alerting  
- Increased operational efficiency in aviation systems  

## Repository Structure  
```
📁 Smart‑Air‑Traffic‑System/
 ┣ 📄 README.md
 ┣ 📄 CITATION.cff
 ┣ 📄 Data_CSV.zip
 ┣ 📄 Data_preprocessing_anotating_final.ipynb
 ┣ 📄 Speech_Recognition__Module.ipynb
 ┣ 📄 NLU_modif_final.ipynb
 ┣ 📄 NLG_Module.ipynb
```

## Getting Started  
1. Clone the repository:  
   ```bash
   git clone https://github.com/Rawda‑Fathey/Smart‑Air‑Traffic‑System.git
   cd Smart‑Air‑Traffic‑System
   ```  
2. Unzip the `Data_CSV.zip` and place the datasets in the `data/` folder (or adjust paths accordingly).  
3. Launch the notebooks in order:  
   - `Data_preprocessing_anotating_final.ipynb`  
   - `Speech_Recognition__Module.ipynb`  
   - `NLU_modif_final.ipynb`  
   - `NLG_Module.ipynb`  
4. Ensure dependencies are installed:  
   ```bash
   pip install -r requirements.txt
   ```  
   (If you don’t yet have `requirements.txt`, create one listing e.g. `tensorflow`, `transformers`, `torch`, `librosa`, etc.)

## How to Use  
- Run preprocessing notebook to prepare your dataset.  
- Use the ASR module to convert ATC audio to text.  
- Pass the transcribed text into the NLU module to classify the meaning (e.g., clearance, instruction, query).  
- Finally, NLG generates an appropriate, contextual response as required.

## Contribution  
Contributions are welcome!  
Please open an issue if you find a bug or have a feature request. Pull requests will be reviewed.


---

## 📚 Citation  
If you use this code or refer to it in your work, please cite:

```bibtex
@article{sarhan2025intelligent,
  title        = {Intelligent air traffic control using NLP‑enhanced speech recognition and natural language generation},
  author       = {Sarhan, Amany M. and Fathy, Rawda and Ali, Hesham A.},
  journal      = {Journal of Electrical Systems and Information Technology},
  year         = {2025},
  volume       = {12},
  pages        = {Article 41},
  publisher    = {Springer Nature},
  doi          = {10.1186/s43067-025-00234-9},
  url          = {https://link.springer.com/article/10.1186/s43067-025-00234-9}
}
```

Thank you for checking out this project — hope you find it useful!
