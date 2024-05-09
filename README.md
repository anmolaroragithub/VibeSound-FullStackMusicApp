# VibeSound

People often listen to music to express their feelings and regulate their emotions. But choosing the right music from the extensive options available that resonates with one’s current mood is a dull and daunting task. It is challenging because users must scroll through the endless playlists on the music streaming applications to find the right music on their own based on their mood. Our goal is to develop a Mood-Based Music Recommender that utilizes existing technologies like facial analysis and emoji-based questionnaire in a way that makes it fun and engaging for the users and enhance their overall experience when searching for music to listen to on their favorite music streaming applications.

## Getting Started

### Setting up the Spotify Web API
Follow the documentation from [here](https://developer.spotify.com/documentation/web-api) to use the Spotify Web API. After 'Creating an app', paste the client ID and client secret in the config files found in `Backend` folder and `src` folder.

### Setting up the local environment and running it
Install the backend dependencies with pip.

```bash
pip install -r requirements.txt
```

Navigate to the `Backend` folder and run the following command to start the backend.

```bash
python -m flask --app app run
```

Install the front-end dependencies with npm or yarn.

#### For npm:
To install the dependencies -

```bash
npm install
```
To start the frontend -

```bash
npm start
```

#### For yarn:
To install the dependencies -

```bash
yarn install
```

To start the frontend -

```bash
yarn start
```
