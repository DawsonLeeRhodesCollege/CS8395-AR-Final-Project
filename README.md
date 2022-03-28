# Augmented Virtual Reality Final Project

Creator: Dawson Lee

Professor: Dr. Bodenheimer

Course: CS 8395


**========== Project Description ==========**

*Summary:*

As a graduate student who walks to campus every day, one of the first tasks I complete before getting ready is to check my mobile weather app. My final project will be similar to this application, but provide users an interactive AR experience for checking the weather through their mobile device camera. Using AR buttons, AR Image Targets, classic UI in combination with 3D UI, and 3D models / animations (stretch goal), I intend to provide users several interactive AR screens displaying information about the local weather. The app's displayed information may include the following: Temperatures, precipitation, weather advisories, humidity, air quality index, wind speeds, and maps.

*UX & Functionality:*

The UX flow will go like this: A user begins the application by opening their mobile device camera. After identifying a unique AR image target on a flat surface like the refrigerator or a cabinet, a 3D display will be rendered in front of the user on the target. In this 3D display, local weather information will be displayed and users can slide between viewing their local weather metrics (Home Screen), a map of the weather in their location (Map Screen), and a search page where they can change the location where they want to learn about the weather (Search page). So, the Home Screen, Map Screen, and Search Screen will be the three primary GUI displays and also the primary features of the project. When viewing a particular screen, the user will be able to use their hands to toggle left or right to view the other virtual screens.

*Main Goals*

- Home Screen
- Map Screen
- Functioning GUI interactions
- Accurate and properly displayed weather info

*Stretch Goals*

- Search for weather conditions in a non-local location using GUIs and the OpenWeather API (Search page)
- Virtual objects for displaying climate such as clouds, sun, lightning, etc. on the Home Screen (may cost $)
- Animations for 3D models (may cost $)
- Settings to scale the AR GUIs or text for easier accessibility and customization
- UI Polish

*Inspirational Images*

![alt text](https://www.immersivelearning.news/wp-content/uploads/2020/07/body-img8-spotlight-weatherchannel-1920x1080-303323645.jpg = 390x270)
![alt text](https://icdn.digitaltrends.com/image/digitaltrends/samsung-4-door-flex-refrigerator-with-family-hub-859x572.jpg = 430x286)

**========== Project Technology, SDKs, & APIs ==========**

*Technology:*

Unity Engine Version 2020.3.+ - Unity will be the 3D content creation platform which I will use as my development environment.

*APIs:*

OpenWeather Weather API (https://openweathermap.org/api) - This API grants programmatic, free access to a wide range of weather data and can be utilized through C# scripts in several ways to display weather content in my AR application (Example: https://rapidapi.com/blog/openweathermap-api-overview/c-sharp/).

*SDKs:*

Vuforia Engine Version 10.5 - The Vuforia SDK gives me access to interactive AR components (e.g. AR buttons or AR image targets) which can be associated with application logic and UI/UX flow programmatically.

**========== Repository ==========**

*README.md* - This file contains project documentation and explanation.
...
