# MovieList

![*"Search"* tab of the app](/assets/images/MovieListSearch.jpg)


## Table of Contents

- [About](##About)
  + [Description](###Description)
  + [Tools](###Tools)
  + [Preview](###Preview)
- [Setup Project](##Setup%20Project)
  + [Prerequisites](###Prerequisites)
  + [Get Started](###Get%20Started)
  + [Get a Fresh Project](###Get%20a%20Fresh%20Project)
  + [Learn More](###Learn%20More)
  + [Join The Community](###Join%20The%20Community)

## About

### Description

**This is an [Expo](https://expo.dev) project created with [`create-expo-app`](https://www.npmjs.com/package/create-expo-app).**
MovieList is an android app designed to show the trending movies. There are several features including: viewing popular/recently searched movies("Home" tab), searching for a specific movie("Search" tab), saving movies in which user was interested("Saved") and viewing the movie details("Details" page). The purpose of writing this project was to learn the basics of react-native by using expo.

### Tools
1. React Native: an open-source framework used for building native-style, cross-platform applications for iOS and Android using JavaScript.
2. Expo: a framework that makes developing Android and iOS apps easier. It is highly recommended for beginners to start.
3. TailwindCSS: a utility-first CSS framework designed to enable developers to create applications faster and more efficiently with smaller css files.
4. TMDB API: This API service allows using movie, TV show or actor images and/or data in the application.
5. Appwrite: an open-source, cloud development platform with built-in backend infrastructure and web hosting, all from a single place.


### Preview
---
*"Home" tab*

![*"Home"* tab of the app](/assets/images/MovieListHome.jpg)

---
*"Search" tab*

![*"Search"* tab of the app](/assets/images/MovieListSearch.jpg)

---
*"Saved" tab*

![*"Saved"* tab of the app](/assets/images/MovieListSaved.jpg)

---
*"Details" page*

![*"Details"* tab of the app](/assets/images/MovieListDetails.jpg)


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
