flask-video-streaming
=====================

Supporting code for Miguel Grinberg's article [video streaming with Flask](http://blog.miguelgrinberg.com/post/video-streaming-with-flask) and its follow-up [Flask Video Streaming Revisited](http://blog.miguelgrinberg.com/post/flask-video-streaming-revisited).

## Installation

Install into a virtual environment:

```{bash}
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

## Usage

Start with ONE of::

```{bash}
python app.py                # stream 1-2-3 images
CAMERA=opencv python app.py  # stream from webcam
```
