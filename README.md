
**Green Guard app (Plants Identification, diagnose and treatment )**

**Green Guard** is a Flutter-based mobile application designed to help
users identify plants and diagnose plant diseases with ease. The app
features a clean interface with options for plant identification,
disease diagnosis, and an "Ask Experts" feature for additional support.
It provides real-time feedback for uploaded or captured images.

**Features**

-   **Plant Identification**: Identify plants with detailed results.

-   **Disease Diagnosis**: Diagnose plant diseases with actionable
    suggestions.

-   **Ask Experts**: Consult with plant experts for additional support.

-   **Cross-Platform Support**: Available for both Android and iOS.

**How to Use**

1.  **Select or Capture Image**: Tap on the camera icon to capture an
    image or select one from your gallery.

2.  **Get Results**: The AI model processes the image to provide
    identification and diagnosis results.

3.  **Navigate Through Features**:

    -   **Home**: Access the main screen for core functionalities.

    -   **Identification**: Explore plant information.

    -   **Diagnose**: Check for diseases and suggested treatments.

    -   **Ask Experts**: Submit queries for expert assistance.

**Technical Details**

-   **Architecture**: Modular Flutter architecture with separate files
    for different screens and models.

-   **UI Framework**: Flutter's Material Design with smooth animations
    and responsive layouts.

-   **State Management**: Utilizes StatefulWidget for interactive and
    dynamic UI.

-   **Image Processing**: AI model processes images uploaded via
    AssetImage integration.

-   **Custom Widgets**: Reusable components for buttons, cards, and
    result views.

**Development Report**

**Challenges Faced**

1.  **Model Integration**: Ensuring seamless integration of the AI model
    with the Flutter frontend.

2.  **UI Responsiveness**: Maintaining a consistent design across
    devices.

3.  **Real-Time Feedback**: Reducing delays in providing instant
    analysis results.

**Lessons Learned**

-   Modular architecture improves scalability and debugging.

-   Testing across multiple devices ensures a consistent and responsive
    UI.

-   Optimized AI model integration enhances user experience.

**Future Enhancements**

-   Implement real-time data using APIs.

-   Add a backend for dynamic plant and disease database updates.

-   Introduce advanced features such as plant care suggestions and
    community forums.

**Current Status**

-   **Model Development**: The model for plant identification and
    diagnosis has been built and is capable of providing treatment
    suggestions.

-   **Integration Status**: The model is not yet integrated into the
    Green Guard app. Currently; the app uses hardcoded data for testing
    purposes.
