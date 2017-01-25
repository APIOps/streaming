# Streaming from APIOps events

We have at least two ways to do streaming. First (onsite streaming) is ideal for event site streaming and the other for speakers participating only online. The latter gives us leverage on getting speakers from different locations around Finland for each meetup. 

# 1. Onsite streaming

APIOps events streaming is handled with youtube at least for the beginning. In this setup we use iPad. You need: 
- access to APIOps youtube (get username and password from Meetup organizers)
- Live Now app

<img src="https://raw.githubusercontent.com/APIOps/streaming/master/livenow.jpg" width="400px"/>

## Live Now app
Live Now app is free and can be downloaded from appstore. In the app you need to configure broadcast key, which can be found from Youtube settings https://www.youtube.com/live_dashboard 
- In youtube dashboard select "live streaming" and you'll find the encoder setup below the videoscreen. There is Stream name/key. 
- In Live Now App configuration: Server URL: rtmp://a.rtmp.youtube.com/live2
- In Live Now App configuration: name/key: xxxxxxxxxxxxx (from Youtube dashboard, Stream name/key). 

<img src="https://raw.githubusercontent.com/APIOps/streaming/master/livenow-conf.jpg" width="400px"/>

The server url should be there in the app already, but you need to insert the stream name/key. After that when you press record, the stream will appear at below given address and is automatically stored to youtube. You don't need to be logged in to Youtube to stream. Stream name/key is used to identify your device. 

## Youtube live 
Address for live broadcast is: https://www.youtube.com/channel/UC1pBHMSm5-gWjkLswIwt6WA/live 

<img src="https://raw.githubusercontent.com/APIOps/streaming/master/youtube.png" width="400px"/>


# 2. Speaker streams from different location than meetup

We use Google Hangouts, which plays nicely together with Youtube Live. 

- You need to **log in to APIOPs youtube account**.
- Go to https://www.youtube.com/my_live_events?action_create_live_event=1
- **Give title** (Your presentation topic would be logical eg Vulcan)
- Make sure event **type** is "Quick (using Google Hangouts On Air)" 
- Click button **"Go live now"**. Confirm broadcasting now by selecting "ok"
- Hangouts window opens (install needed plugins and extensions) and **wait until you see "start broadcast"** button at the bottom of the page. 
- When ready start broadcasting by **clicking "start broadcast"**. 
- You can share your screen in Hangouts from left "screen share". 

## Youtube live 
Address for live broadcast is: https://www.youtube.com/channel/UC1pBHMSm5-gWjkLswIwt6WA/live 

## Notes for speakers

- If you present powerpoint, PDF or something else, DON'T use fullscreen. It will not show live, instead your video is shared. Everything else works, but not fullscreen. 
- Also, Hangouts chat is not synced with Youtube live chat. So don't use Hangouts chat. 

## Notes based on test

- The following may override the last bullet on the previous *Notes for speakers*.
- Youtube login most likely requires verification. Discuss the options with the @kyyberi.
- If streaming from a laptop, you probably will need to install [Google Hangouts Voice and Video](https://www.google.com/tools/dlpage/hangoutplugin/).
- Just make sure you are creating a new event ("Events" on the left navigation), not Stream now, since the latter option will require additional installations [encoding software](https://support.google.com/youtube/answer/2907883?hl=en). Of course you can do this too, if you like.
- Note: There seems to be a couple of minutes delay between the presenter and Youtube stream.
