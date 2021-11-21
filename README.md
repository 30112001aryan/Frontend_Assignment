# Music waveform visualization


## Built with

- [React.js](https://reactjs.org/)
- [Redux](https://redux.js.org/)
- [Redux Thunk](https://github.com/reduxjs/redux-thunk)
- [Material-UI](https://material-ui.com/) components as an implementation of [Google's Material Design](https://material.io/design)
- [axios](https://github.com/axios/axios)
- [wavesurfer.js](https://wavesurfer-js.org/) library in order to produce song's waveform visualization

## Features
- List uploaded tracks
- Select a track to play
- Produce waveform visualization for current playing track
- Force player at any track position using the cursor on waveform
- 10 seconds forward
- 10 seconds backward
- Play/Pause



## Quick Start

### Prerequisites

#### 1. Create a `.env` file at project's root directory, running the following command:

```console
$ touch .env
```
Define needed project environment variables as key/value pairs inside `.env` file. Notice that custom environment variables needs to start with ```REACT_APP``` prefix, so React can expose them in JS through ```process.env```.
Only one environment variable is required for this application, the API base URL.

`REACT_APP_BASE_URL`

#### 2. Install dependencies

Before starting the server, install all the needed dependencies for the project, running the following command:

```console
$ npm install
```

#### 3. Run dev server

Run the appplication in the development mode using your terminal at project's root directory:

```console
$ npm start
```

Open [http://localhost:3000](http://localhost:3000) to view it in the browser.


It correctly bundles React in production mode and optimizes the build for the best performance.
