# Disney+ Clone with Expo

[![made with expo](https://img.shields.io/badge/MADE%20WITH%20EXPO-000.svg?style=for-the-badge&logo=expo&labelColor=4630eb&logoWidth=20)](https://github.com/expo/expo) [![supports iOS and Android](https://img.shields.io/badge/Platforms-Native-4630EB.svg?style=for-the-badge&logo=EXPO&labelColor=000&logoColor=fff)](https://github.com/expo/expo)

[![follow @calebnance](https://img.shields.io/twitter/follow/calebnance.svg?style=for-the-badge&logo=TWITTER&logoColor=FFFFFF&labelColor=00aced&logoWidth=20&color=lightgray)](https://twitter.com/calebnance)

<p align="center">
  <img src="screenshots/screenshare-4.png?raw=true" />
</p>

## Table of Contents

- [Install & Build](#install--build)
- [Stats](#stats)
- [Linting](#linting)
- [Demo & Release Notes](#release-notes)

## Install & Build

First, make sure you have Expo CLI installed: `npm install -g expo-cli`

Install: `yarn` or `yarn install`

Run Project Locally: `expo start` or `yarn dev`

## Stats

- Expo SDK 35
- iOS and Android
- React Navigation v3
- PropTypes

## Linting

- run: `yarn lint` for a list of linting warnings/error in cli
- prettier and airbnb config
- make sure you have prettier package installed:
  - [prettier for atom](https://atom.io/packages/prettier-atom)
  - [prettier for vscode](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
- then make sure to enable these options (packages → prettier):
  - eslint integration
  - stylelint integration
  - automatic format on save (toggle format on save)
- be aware of the `.prettierignore` file

## Release Notes

### version 0.0.1 (current)

- iOS and Android
- Tab Navigation
  - Home
  - Search
  - Downloads
  - Profile
- started with [Expo SDK 35](https://blog.expo.io/expo-sdk-35-is-now-available-beee0dfafbf4)