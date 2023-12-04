#Overview
The TV Show Tracker App is an Android application that allows users to discover TV shows from an API server, add their favorite shows to an isolated list, and track the episodes they've watched. The app is built using the MVVM architecture and incorporates various Android libraries and design principles for a seamless user experience.

#Features
MVVM Architecture: The app follows the Model-View-ViewModel architectural pattern, promoting separation of concerns and maintainability.

Retrofit: Network requests are made using Retrofit to fetch TV show data from the API server.

Lifecycle Extensions: Utilizes Android Lifecycle Extensions to efficiently manage the lifecycle of components.

Room Database: Persists user-specific data, such as favorite TV shows and watched episodes, using Room, an SQLite object mapping library.

RxJava: Implements reactive programming with RxJava to handle asynchronous tasks and simplify complex data flow.

Material Design: Adheres to Google's Material Design guidelines for a modern and visually appealing user interface.

Data Binding: Leverages data binding to bind UI components in layouts to data sources, reducing boilerplate code.

#Usage
Discover Shows:
Browse through a list of TV shows fetched from the API server.

Favorites:
Add your favorite TV shows to the favorites list for quick access.

Watched Episodes:
Mark episodes as watched to keep track of your viewing progress.

Isolated List:
Access an isolated list of your favorite TV shows for a personalized experience.
