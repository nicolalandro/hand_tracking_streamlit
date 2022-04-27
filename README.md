[![Streamlit App](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://share.streamlit.io/nicolalandro/hand_tracking_streamlit/main/app.py)

# Streamlit hand tracking demo

This codebase include a streamlit app with a HandTraking service.


```
python3.8 -m venv venv
source venv/bin/activate
# or on fish shell
source venv/bin/activate.fish

pip install -r requirements.txt

python -m streamlit run app.py

# run demo opencv
python opencv_test.py
```

# References
* [streamlit](https://streamlit.io/)
* [streamlit_webrtc](https://github.com/whitphx/streamlit-webrtc): to use webcam from browser on stramlit
* [Hand Tracking](https://z-uo.medium.com/hand-tracking-with-opencv-and-mediapipe-on-python-991dfae615d6)
* [Mediapipe](https://google.github.io/mediapipe/solutions/hands)