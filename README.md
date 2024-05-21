Steps to configure heatmap.py on macOS:

```
brew install python@3.11
cd ~
python3.11 -m venv heatmap
cd heatmap
wget https://raw.githubusercontent.com/kalem-dev/rtl-sdr-misc/master/heatmap/heatmap.py
wget https://raw.githubusercontent.com/kalem-dev/rtl-sdr-misc/master/heatmap/requirements.txt
source bin/activate
pip install -r requirements.txt
```

Then to generate a heatmap:

```
python3.11 heatmap.py data.csv out.png
```
