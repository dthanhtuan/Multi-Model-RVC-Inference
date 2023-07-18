# Multi-Model RVC Inference

### Installation
1. Build Pyword from source
```
git clone https://github.com/JeremyCCHsu/Python-Wrapper-for-World-Vocoder.git
cd Python-Wrapper-for-World-Vocoder
git submodule update --init
pip install -U pip
pip install -r requirements.txt
pip install .
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
