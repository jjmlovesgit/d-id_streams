# 10/27/23  Update -- I did the integration of the streaming avatar with ChatGPT:  https://github.com/jjmlovesgit/D-id_Streaming_Chatgpt
# Streaming Live Demo by D-ID and modified by JJM
[https://youtu.be/5X_sse80arc](https://youtu.be/JUYIZD-p2w8)
#
![image](https://github.com/jjmlovesgit/d-id_streams/assets/47751509/1706072d-19cb-44a3-865e-2657ace373df)
# D-ID Streaming API to create Realtime video Responses for your Chatbot with code included...

## Initial Setup:
* (install express) open a terminal in the folder and run  - npm install express
* (add your api key) edit the `api.json` inside the uncompressed folder and replace the emoji with your key


## Start the demo:
* (bring up the app) in the folder (ctr left click on folder through finder) open the terminal 
* I prefer to run Python Webserver python -m http.server
* You should see this message - Serving HTTP on :: port 8000 (http://[::]:8000/) ...
* (open the app) in the browser add localhost:8000
* http://localhost:8000/index.html
* Enter Text to Send for Processing 15 words = 1 credit -- keep it short :)
* (connect) press connect you should see the connection ready 
* (stream) press the start button to start streaming
* Give it a sec and it starts talking!
* Be aware it is fun and you will run out of credits if you create a lot of video feedback 

## Note:
change the line 34 in streaming-client-api.js to cusomize the avitar to your image 
