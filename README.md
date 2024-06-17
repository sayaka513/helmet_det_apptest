👷 [Safety Helmet Detection App](https://tygbv47rmjer2ftq9sfl8c.streamlit.app/) 👷‍♀️

This is the modified version of the code created for [the final project for Le Wagon Tokyo Data Science & AI batch #1639 project](https://github.com/Nsayre/helmet_det) to run on Streamlit Community Cloud. 
It utilizes [streamlit-webrtc](https://github.com/whitphx/streamlit-webrtc) to detect the real-time wearing of safety helmets.
However, to operate on Streamlit Community Cloud, a TURN server is necessary.
Therefore, [Twilio Network Traversal Service](https://www.twilio.com/docs/stun-turn) is used to set up the TURN server.


これは[Le Wagon データサイエンス＆ＡＩプロジェクト batch#1639で作成されたコード](https://github.com/Nsayre/helmet_det)をStreamlit Community Cloud上で動けるように修正したものです。
安全ヘルメット着用の有無をリアルタイムで検知するためにstreamlit-webrtcを使用していますが、Streamlit Community Cloud上で動かすためにはTURNサーバーが必要となります。
そのため、Twilio Network Traversal Serviceを用いてTURNサーバーをセットしています。
