# CAFReceiverVideoLooping
This Cast receiver application shows how to loop video playback using Google CAF Receiver.

# Dependencies
1. A Google Cast Receiver Device (eg. Chromecast)
2. The Google Cast Receiver SDK.

# Setup Instructions
1. Check out the code from GitHub and host the receiver.html file on your web server.
2. Create a custom receiver app ID in the Google Cast Developer console: https://cast.google.com/publish
3. Enter the URL to the hosted receiver.html file for the custom receiver URL.
4. Use the app ID in your sender app: https://developers.google.com/cast/docs/sender_apps

# References
1. CAF Receiver Overview: https://developers.google.com/cast/docs/caf_receiver_overview
2. Queuing : https://developers.google.com/cast/docs/caf_receiver_features#queueing
3. Cast APIs: http://developers.google.com/cast/docs
4. Design Checklist: http://developers.google.com/cast/docs/design_checklist
