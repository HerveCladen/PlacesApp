# PlacesApp
React Native application using native device features (camera and map) to store places in an SQLite local database from a picture taken with the camera and a location taken from the map or from the user's location. <br />

This was done following Maximilian Schwarzmüller's course "[React Native - The Practical Guide](https://www.udemy.com/course/react-native-the-practical-guide/)" on Udemy <br />

Requires adding a `env.js` file with a Google API Key following this structure:
```
const vars = {
  googleApiKey: 'your google api key'
}

export default vars;
```

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm start
```
