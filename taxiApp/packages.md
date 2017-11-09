# Packages Used

_package.json_

<pre class="line-numbers"><code class="language-json">{
{
  "name": "StrapTaxiApp",
  "version": "8.0.0",
  "private": true,
  "devDependencies": {
    "babel-eslint": "^8.0.2",
    "eslint": "^4.10.0",
    "eslint-plugin-flowtype": "^2.39.1",
    "eslint-plugin-import": "^2.8.0",
    "eslint-plugin-jsx-a11y": "^6.0.2",
    "eslint-plugin-prettier": "^2.3.1",
    "eslint-plugin-react": "^7.4.0",
    "eslint-plugin-react-native": "^3.1.0",
    "flow-bin": "^0.59.0",
    "flow-typed": "^2.2.3",
    "husky": "^0.14.3",
    "jest": "^21.2.1",
    "jest-expo": "^22.0.0",
    "prettier": "^1.8.1",
    "react-native-scripts": "1.7.0",
    "react-test-renderer": "16.0.0-beta.5",
    "remote-redux-devtools": "^0.5.12",
    "remote-redux-devtools-on-debugger": "^0.8.3"
  },
  "main": "./node_modules/react-native-scripts/build/bin/crna-entry.js",
  "scripts": {
    "start": "react-native-scripts start",
    "eject": "react-native-scripts eject",
    "android": "react-native-scripts android",
    "ios": "react-native-scripts ios",
    "test": "jest && eslint .",
    "precommit": "yarn test"
  },
  "jest": {
    "preset": "jest-expo",
    "transformIgnorePatterns": [
      "node_modules/(?!(react-native|lottie-react-native|expo|react-native-maps|react-native-svg|react-native-branch|native-base-shoutem-theme|react-native-easy-grid|react-native-drawer|react-native-vector-icons|react-native-keyboard-aware-scroll-view|react-native-swiper|react-navigation|native-base|@expo|react-native-scrollable-tab-view|react-native-simple-modal)/)"
    ]
  },
  "dependencies": {
    "color": "^2.0.1",
    "expo": "^22.0.2",
    "lodash": "^4.17.4",
    "moment": "^2.19.1",
    "native-base": "^2.3.3",
    "prop-types": "^15.6.0",
    "react": "16.0.0-beta.5",
    "react-native": "^0.49.5",
    "react-native-router-flux": "^4.0.0-beta.22",
    "react-redux": "^5.0.6",
    "redux": "^3.7.2",
    "redux-persist": "4.10.0",
    "redux-thunk": "2.2.0"
  }
}

</code></pre>
