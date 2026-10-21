# Recipe Finder

Recipe Finder is a native Android application for browsing and searching recipes. It was originally developed as an academic group project and uses a prepopulated local database so recipe information remains available offline.

## Features

- Browse popular recipes
- Explore salads, main dishes, drinks, and desserts
- Search recipes by title as the user types
- View preparation time, ingredients, and cooking instructions
- Switch between ingredient and procedure views
- View recipe imagery in fitted or cropped modes

## Technology

- Kotlin and Android Studio
- Android XML layouts and View Binding
- Room with a prepopulated SQLite database
- RecyclerView with custom adapters
- Glide for image loading
- Gradle

## Project structure

The application uses separate Android activities for the splash screen, home screen, category browsing, search, and recipe details. Room exposes recipe data through a DAO, while RecyclerView adapters render popular, category, and search results.

## Run locally

1. Clone the repository.
2. Open the project in Android Studio.
3. Allow Gradle to synchronize the dependencies.
4. Run the `app` configuration on an Android emulator or physical device running Android 8.0 (API 26) or newer.

## Notes

- Recipe records are provided through `app/src/main/assets/recipe.db`.
- Internet access is used to load recipe images referenced by the local records.
- This repository contains an early-college academic project and is preserved as part of the developer's learning portfolio.
