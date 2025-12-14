# MovieList

![*"Search"* tab of the app](/assets/images/MovieListSearch.jpg)


## Table of Contents

- [About](#about)
  + [Description](#description)
  + [Tools](#tools)
  + [Preview](#preview)
  + [Repository structure](#repository-structure)
- [Setup Project](#setup-project)
  + [Prerequisites](#prerequisites)
  + [Get Started](#get-started)
  + [Get a Fresh Project](#get-a-fresh-project)
  + [Learn More](#learn-more)
  + [Join The Community](#join-the-community)

## About

### Description

**This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).**
MovieList is an android app designed to show the trending movies. There are several features including: viewing popular/recently searched movies("Home" tab), searching for a specific movie("Search" tab), saving movies in which user was interested("Saved") and viewing the movie details("Details" page). The purpose of writing this project was to learn the basics of react-native by using expo. ***You can download the APK file [here](https://portfolio-yeradil.vercel.app/)***.

### Tools
1. [React Native](https://reactnative.dev/docs/environment-setup): an open-source framework used for building native-style, cross-platform applications for iOS and Android using JavaScript.
2. [Expo](https://docs.expo.dev/): a framework that makes developing Android and iOS apps easier. It is highly recommended for beginners to start.
3. [TailwindCSS](https://v2.tailwindcss.com/docs/guides/create-react-app): a utility-first CSS framework designed to enable developers to create applications faster and more efficiently with smaller css files.
4. [TMDB API](https://developer.themoviedb.org/v4/reference/getting-started): This API service allows using movie, TV show or actor images and/or data in the application.
5. [Appwrite](https://appwrite.io/docs): an open-source, cloud development platform with built-in backend infrastructure and web hosting, all from a single place.


### Preview
---
*"Home" tab*, /app/(tabs)/index.tsx

![*"Home"* tab of the app, MovieListHome.jpg](/assets/images/MovieListHome.jpg)

---
*"Search" tab*, /app/(tabs)/search.tsx

![*"Search"* tab of the app, MovieListSearch.jpg](/assets/images/MovieListSearch.jpg)

---
*"Saved" tab*, /app/(tabs)/saved.tsx

![*"Saved"* tab of the app, MovieListSaved.jpg](/assets/images/MovieListSaved.jpg)

---
*"Details" page*, /app/movies/[id].tsx

![*"Details"* tab of the app, MovieListDetails.jpg](/assets/images/MovieListDetails.jpg)

### Repository Structure

1. android: the folder generated after creating APK file
2. app: the folder containing the main logic of this project
   - (tabs): contains main pages used in the project
   - movies: [id].tsx used as a template for different movie details
3. assets: the folder containing resources used in the project including images, icons and fonts
4. components: contains reusable components potentially used in multiple files
5. constants: used for code cleanliness
6. interfaces: stores all interfaces used in this project
7. services: contains hooks, functions used for fetching data
8. types: used for importing different types of files

## Setup Project

### Prerequisites
Make sure that the following tools are already installed:
- [Node.js](https://nodejs.org/en/download/): It is a JavaScript runtime build.
- [Git](https://git-scm.com/install/): It is an open source version control system.
- [Expo Go](https://docs.expo.dev/get-started/set-up-your-environment/): For debugging with physical a device or emulator. Please refer to the link for instructions.

### Get Started

1. Clone the Repository

   ```powershell
   git clone https://github.com/w-obi/MovieList.git
   ```

3. Install dependencies

   ```bash
   npm install
   ```

4. Install Expo CLI

   ```bash
   npm install -g expo-cli
   ```

6. Start the app

   ```bash
   npx expo start
   ```

In the output, you'll find options to open the app in a

- [development build](https://docs.expo.dev/develop/development-builds/introduction/)
- [Android emulator](https://docs.expo.dev/workflow/android-studio-emulator/)
- [iOS simulator](https://docs.expo.dev/workflow/ios-simulator/)
- [Expo Go](https://expo.dev/go), a limited sandbox for trying out app development with Expo

You can start developing by editing the files inside the **app** directory. This project uses [file-based routing](https://docs.expo.dev/router/introduction).

### Get a Fresh Project

When you're ready, run:

```bash
npm run reset-project
```

This command will move the starter code to the **app-example** directory and create a blank **app** directory where you can start developing.

### Learn More

To learn more about developing your project with Expo, look at the following resources:

- [Expo documentation](https://docs.expo.dev/): Learn fundamentals, or go into advanced topics with our [guides](https://docs.expo.dev/guides).
- [Learn Expo tutorial](https://docs.expo.dev/tutorial/introduction/): Follow a step-by-step tutorial where you'll create a project that runs on Android, iOS, and the web.

### Join The Community

Join our community of developers creating universal apps.

- [Expo on GitHub](https://github.com/expo/expo): View our open source platform and contribute.
- [Discord community](https://chat.expo.dev): Chat with Expo users and ask questions.
