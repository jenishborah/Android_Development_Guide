# Understanding Project File Structure

An Android Studio project consists of several key directories and files:

- **app/**: Contains the application code and resources.
  - **src/**: Contains the source code.
    - **main/**: The main source set.
      - **java/**: Contains Java/Kotlin source files.
      - **res/**: Contains application resources (layouts, strings, images).
      - **AndroidManifest.xml**: Describes essential information about the app.
  - **build.gradle**: The Gradle build script for the app module.
- **build/**: Contains build outputs.
- **gradle/**: Contains configuration files for the Gradle build system.
- **settings.gradle**: Specifies the settings for the Gradle build.
- **build.gradle (Project level)**: The top-level build file.

For a more detailed explanation, refer to the [official documentation](https://developer.android.com/studio/projects).
