# Talk transcriptor

Transcribes your blabbering 💬 and broadcasts it to the world 🌍 in realtime ⚡ using [Pusher Channels](pusher.com/channels).

## Setting up

- Set up a Google Cloud Speech to text project, and store your credentials in the `GOOGLE_APPLICATION_CREDENTIALS` environment variable. For more info, read up [on their official docs](https://cloud.google.com/speech-to-text/docs/).

- Set up a [Pusher Channels app](pusher.com/channels), and replace your credentials in `start_streaming.js`. 

## Using 

- Spin up the service: - `npm start`
- Listen and transcribe (in a different project lol!)