**Open Speech Recording** is a small web application to collect short snippets
of speech, and upload them to your server. It's designed to help gather open
speech data sets to train machine learning systems.

It's based around a small Flask app that will run on docker. This
serves up a client-side Javascript app that prompts for a series of words,
records the audio, and then POSTs the results back to the server.

## Running

To get started, you'll need to edit docker-compose.yml to update the session key. If you have the docker and docker-compose set up, you should be able to run with this command:

```
git clone https://github.com/senyoltw/open-speech-recording
cd open-speech-recording
docker-compose up
```

## Credits

Thanks to the Mozilla team for the [Web Dictaphone sample application](https://developer.mozilla.org/en-US/docs/Web/API/MediaStream_Recording_API/Using_the_MediaStream_Recording_API#A_sample_application_Web_Dictaphone)
that I used as a starting point, [Sole](https://soledadpenades.com/) for the
oscilloscope, and the Flask team for a lovely Python microframework!

thanks! Pete Warden, https://github.com/petewarden/open-speech-recording