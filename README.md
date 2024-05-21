Steps to configure heatmap.py on macOS (Python 3.12 does not work):

```
brew install python@3.11
cd ~
python3.11 -m venv heatmap
cd heatmap
wget https://raw.githubusercontent.com/kalem-dev/rtl-sdr-misc/master/heatmap/heatmap.py
wget https://raw.githubusercontent.com/kalem-dev/rtl-sdr-misc/master/heatmap/requirements.txt
source bin/activate
pip3.11 install -r requirements.txt
```

Then to generate a heatmap:

```
python3.11 heatmap.py data.csv out.png
```
