Project Structure


Manifests folder

It contain AndroidManifest.xml file which is heart of android project.

This file contains information about our application such as app metadata, android version,app name, activities, permissions, and much more.

Java folder

This folder contain source code java/kotlin

Resource folder(res)

This folder contain all non-code resources such as images, audio, video, menus, styles, strings,etc

drawable

contains assets like images etc

layout:

Contain all xml layouts

mipmap:

Contains file to defined icons

values

Contains files like strings, dimensions, colors etc

Gradle Scripts folder

Gradle is project management tool which help to manage dependency , build of the projects.

Gradle folder contains many files used to defined number of configuraion files.

build.gradle(project)

Is used to specify global build configurations for the entire project, including the repositories where dependencies can be found and the version of the Android build tools to use.

build.gradle(module)

Is used to specify the build configurations for a specific module within the project, such as the dependencies, build tools, and other settings needed to build and run the app.

gradle.setting

Is used to specify project-wide settings for the build process, including which modules should be included in the project and how they should be organized.

gradle-wrapper.properties

Is used to specify the version of Gradle to use for the build process.



## Views

- A View occupies a rectangular area on the screen and is responsible for **drawing** and **event handling**.

- View is the base class for widgets, which are used to create interactive UI components (buttons, text fields, etc.).

- Views are called widgets

- Button,TextView,EditText ....

  - Button

    ![Android Button](images/image-5.png)

  - ImageButton

    ![Android Image Button](images/image-6.png)

  - EditText

    ![Android Edit Text](images/image-7.png)

  - TextView

    ![Android TextView](images/image-8.png)

  - Toast

    ![Android Toast](images/image-10.png)

  - CheckBox

    ![Android CheckBox](images/image-11.png)

  - RadioButton

    ![Android Radio Button](images/image-12.png)

  - Spinner

    ![Android Spinner](images/image-13.png)

  - AutoCompleteTextView

  - ProgressBar

    ![Android Progressbar](images/image-14.png)

  - DatePicker

    ![Alt text](images/image-15.png)

  - TimePicker

    ![Alt text](images/image-16.png)

  - AlertDialog

    ![Alt text](images/image-17.png)

  - RatingBar

    ![Alt text](images/image-18.png)

  - WebView

    ![Alt text](images/image-19.png)

## ViewGroups

- The ViewGroup is the base class for layouts, which are invisible containers that hold other Views (or other ViewGroups) and define their layout properties.

- Viewgroups are called layouts such as

- ConstraintLayout, LinearLayout, RelativeLayout, FrameLayout etc

  - **Relative Layout**s :
    RelativeLayout is a view group that places its child views relative to one another

    ![Alt text](images/image-1.png)

  - **Constraint Layout**: It is similar to RelativeLayout in that all views are set up according to the relationships between sibling views and the parent layout, but it is more flexible than RelativeLayout and easier to use with the Layout Editor in Android Studio

    ![Alt text](images/image-3.png)

  - **Linear Layout**: Arrage the components in linear way

    ![Alt text](images/image.png)

  - **Frame Layout** : FrameLayout is designed to display a single object in a section of the screen
    ![Alt text](images/image-2.png)

  - **Table Layout** :TableLayout is a ViewGroup that presents its children in rows and columns.

    ![Alt text](images/image-4.png)
