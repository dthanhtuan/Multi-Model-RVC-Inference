<div align="center">

# Multi-Model RVC Inference

[![License](https://img.shields.io/github/license/arkandash/Multi-Model-RVC-Inference?style=for-the-badge)](https://github.com/ArkanDash/Multi-Model-RVC-Inference/blob/master/LICENSE)
[![Repository](https://img.shields.io/badge/Github-Multi%20Model%20RVC%20Inference-blue?style=for-the-badge&logo=github)](https://github.com/ArkanDash/Multi-Model-RVC-Inference)
</div>

### Information
Now Support V1 and V2 Model <br />
[![Original RVC Repository](https://img.shields.io/badge/Github-Original%20RVC%20Repository-blue?style=for-the-badge&logo=github)](https://github.com/RVC-Project/Retrieval-based-Voice-Conversion-WebUI)
#### Features
- Youtube Audio Downloader ✅
- Demucs (Voice Splitter) [Internet required for downloading model] ✅
- TTS Support ✅
- HuggingFace Spaces Inference [FREE TIER CPU] ✅
    - Remove Youtube & Input Path ✅
    - Remove Crepe Support due to gpu requirement ✅

#### Plans
- UVR

### Installation
1. Build Pyword from source
```
#@title Build pyword from source
%cd /content/
!git clone https://github.com/JeremyCCHsu/Python-Wrapper-for-World-Vocoder.git
%cd /content/Python-Wrapper-for-World-Vocoder
!git submodule update --init
!pip install -U pip
!pip install -r requirements.txt
!pip install .
```
2. Install Requirement <br />
```bash
pip install torch torchvision torchaudio

pip install -r requirements.txt
```
3. Download [Hubert Model](https://huggingface.co/lj1995/VoiceConversionWebUI/blob/main/hubert_base.pt)

4. Run WebUI <br />
```bash
python app.py
```
# Other Inference
[Simple RVC Inference](https://github.com/ArkanDash/rvc-simple-inference)
