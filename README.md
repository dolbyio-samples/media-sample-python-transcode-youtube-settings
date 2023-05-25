[![License](https://img.shields.io/github/license/dolbyio-samples/blog-transcode-for-youtube)](LICENSE)

![Blog Picture](https://dolby.io/wp-content/uploads/2021/12/Transcoding-for-Youtube-1.jpg)

# Transcode for YouTube
Python sample application to transcode media to YouTube recommended settings. This repo goes along with the [Transcode Video to YouTube Recommendations](https://dolby.io/blog/transcode-video-to-youtube-recommendations/) blog.

# Overview
Videos uploaded that don't follow the stipulated guidelines by YouTube will undergo an automatic re-configuration causing it not to match your specific preferences and longer upload times. With Dolby.io Media APIs, you can programmatically reconfigure your videos and deliver great media at scale. Learn how to leverage Dolby.io's API to diagnose and correctly format your videos. 

# Requirements
- Install Python 3.8+
- Sign up for a free Dolby.io account [here](https://dashboard.dolby.io/).
- Create a new application and save the Media API key.

![How to Create Dolby.io App and Get API Key](https://imgur.com/VKvQRio.gif)

# Getting Started

1. Clone this repo and change directory.
    ```sh
    $ git clone https://github.com/dolbyio-samples/blog-transcode-for-youtube

    $ cd blog-transcode-for-youtube
    ```
    
2. Install required packages.
    ```sh
    $ pip3 install -r requirements.txt 
    ```
    
4. Create environment variable to store your Dolby.io Media API key (Replace `$DOLBYIO_API_KEY` with your API key).
    ```sh
    $ export DOLBYIO_API_KEY=$DOLBYIO_API_KEY
    ```
    OR

    ```sh
    $ echo "DOLBYIO_API_KEY=$DOLBYIO_API_KEY" > .env

    ```

3. Run the code to transcode the video file in [/videos/input/](/videos/input/).
    ```sh
    $ python3 ./src/main.py
    ```
# Report a Bug 
In the case any bugs occur, report it using Github issues, and we will see to it. 

# Forking
We welcome your interest in trying to experiment with our repos. 

# Feedback 
If there are any suggestions or if you would like to deliver any positive notes, feel free to open an issue and let us know!

# Learn More
For a deeper dive, we welcome you to review the following:
 - [Media Diagnose API](https://docs.dolby.io/media-apis/docs/diagnose-api-guide)
 - [Getting Started with Diagnosing API](https://docs.dolby.io/media-apis/docs/quick-start-to-diagnosing-media)
 - [API Reference](https://docs.dolby.io/media-apis/reference/media-diagnose-post)
 - [How-to Livestream a Dolby.io Conference on YouTube](https://dolby.io/blog/how-to-livestream-a-dolby-io-conference-on-youtube/)
 - [How-to Share Your Screen with Audio in a WebRTC Video Call](https://dolby.io/blog/how-to-share-your-screen-with-audio-in-a-webrtc-video-call/)
 - [Blog Session - Media API](https://dolby.io/search/?_blog_categories=media)

# About Dolby.io
Using decades of Dolby's research in sight and sound technology, Dolby.io provides APIs to integrate real-time streaming, voice & video communications, and file-based media processing into your applications. [Sign up for a free account](https://dashboard.dolby.io/signup/) to get started building the next generation of immersive, interactive, and social apps.

<div align="center">
  <a href="https://dolby.io/" target="_blank"><img src="https://img.shields.io/badge/Dolby.io-0A0A0A?style=for-the-badge&logo=dolby&logoColor=white"/></a>
&nbsp; &nbsp; &nbsp;
  <a href="https://docs.dolby.io/" target="_blank"><img src="https://img.shields.io/badge/Dolby.io-Docs-0A0A0A?style=for-the-badge&logoColor=white"/></a>
&nbsp; &nbsp; &nbsp;
  <a href="https://dolby.io/blog/category/developer/" target="_blank"><img src="https://img.shields.io/badge/Dolby.io-Blog-0A0A0A?style=for-the-badge&logoColor=white"/></a>
</div>

<div align="center">
&nbsp; &nbsp; &nbsp;
  <a href="https://youtube.com/@dolbyio" target="_blank"><img src="https://img.shields.io/badge/YouTube-red?style=flat-square&logo=youtube&logoColor=white" alt="Dolby.io on YouTube"/></a>
&nbsp; &nbsp; &nbsp; 
  <a href="https://twitter.com/dolbyio" target="_blank"><img src="https://img.shields.io/badge/Twitter-blue?style=flat-square&logo=twitter&logoColor=white" alt="Dolby.io on Twitter"/></a>
&nbsp; &nbsp; &nbsp;
  <a href="https://www.linkedin.com/company/dolbyio/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white" alt="Dolby.io on LinkedIn"/></a>
</div>
