# learning-android

### Basic Info
 - `app > java > com.example.myfirstapp > MainActivity`
    - This is the main activity (the entry point for your app). When you build and run the app, the system launches an instance of this Activity and loads its layout.
 - `app > res > layout > activity_main.xml`
    - This XML file defines the layout for the activity's UI. It contains a TextView element with the text "Hello world!".
 - the user interface is broken up into layouts and widgets
    - in java these are [ViewGroup](https://developer.android.com/reference/android/view/ViewGroup.html) and [View](https://developer.android.com/reference/android/view/View.html) objects
    - Layouts are containers that control how their child views are positioned on the screen
    - Widgets are UI components such as buttons and text boxes
 - methods can be attached to widgets using the Attributes window
 - Specific details in methods are required in order for the system to recognize it as compatible with [android:onClick](https://developer.android.com/reference/android/view/View.html#attr_android:onClick)
    - Public access
    - A void or, in Kotlin, an implicit unit return value
    - A [View](https://developer.android.com/reference/android/view/View.html) as the only parameter (it is the [View](https://developer.android.com/reference/android/view/View.html) object that was clicked)
    - An [Intent](https://developer.android.com/reference/android/content/Intent) is an object that provides runtime binding between separate components, such as two activities
    - The Intent constructor takes two parameters, a Context and a Class
    -The Context parameter is used first because the Activity class is a subclass of Context.
    - The Class parameter of the app component, to which the system delivers the Intent, is, in this case, the activity to start.
    -
      