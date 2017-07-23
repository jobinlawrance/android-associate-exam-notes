# android-associate-exam-notes
Bookmark of all the material required for Android Associate Developer Certification

## Topics  
Reference - https://developers.google.com/training/certification/associate-android-developer/#info  

### Testing and debugging
Writing tests to verify that the application's logic and user interface are performing as expected, and executing those tests using the developer tools. Candidates should be able to analyze application crashes, and find common bugs such as layout errors and memory leaks. This includes working with the debuggers to step through application code and verify expected behavior.  
- [ ] Write and execute a local JVM unit test  
	* [Testing Android MVP](https://medium.com/@Miqubel/testing-android-mvp-aa0de6e165e4) (overview)  
	* [Mockito](http://www.vogella.com/tutorials/Mockito/article.html)
	* [RxJava Unit Testing](https://medium.com/mobile-engineering/rxjava-unit-testing-examples-a26af80dfce4)
- [ ] Write and execute a device UI test  
- [ ] Given a problem description, replicate the failure
- [ ] Use the system log to output debug information
- [ ] Debug and fix an application crash (uncaught exception)
- [ ] Debug and fix an activity lifecycle issue
- [ ] Debug and fix an issue binding data to views  

### Application user interface (UI) and user experience (UX)  
Implementation of the visual and navigational components of an application's design. This includes constructing layouts—using both XML and Java code—that consist of the standard framework UI elements as well as custom views. Candidates should have a working knowledge of using view styles and theme attributes to apply a consistent look and feel across an entire application. Understanding of how to include features that expand the application's audience through accessibility and localization may also be required.  
- [ ] Mock up the main screens and navigation flow of the application
- [ ] Describe interactions between UI, background task, and data persistence
- [ ] Construct a layout using XML or Java code
- [ ] Create a custom view class and add it to a layout
- [ ] Implement a custom application theme
- [ ] Apply a custom style to a group of common widgets
- [ ] Define a RecyclerView item list
- [ ] Bind local data to a RecyclerView list
- [ ] Implement menu-based or drawer navigation
- [ ] Localize the application's UI text into one other language
- [ ] Apply content descriptions to views for accessibility
- [ ] Add accessibility hooks to a custom view  

### Fundamental application components

Understanding of Android's top-level application components (Activity, Service, Broadcast Receiver, Content Provider) and the lifecycle associated with each one. Candidates should be able to describe the types of application logic that would be best suited for each component, and whether that component is executing in the foreground or in the background. This includes strategies for determining how and when to execute background work.  

- [ ] Describe an application's key functional and nonfunctional requirements
- [ ] Create an Activity that displays a layout resource
- [ ] Fetch local data from disk using a Loader on a background thread
- [ ] Propagate data changes through a Loader to the UI
- [ ] Schedule a time-sensitive task using alarms
- [ ] Schedule a background task using JobScheduler
- [ ] Execute a background task inside of a Service
- [ ] Implement non-standard task stack navigation (deep links)
- [ ] Integrate code from an external support library  

### Persistent data storage

Determining appropriate use cases for local persisted data, and designing solutions to implement data storage using files, preferences, and databases. This includes implementing strategies for bundling static data with applications, caching data from remote sources, and managing user-generated private data. Candidates should also be able to describe platform features that allow applications to store data securely and share that data with other applications in.

- [ ] Define a database schema; include tables, fields, and indices
- [ ] Create an application-private database file
- [ ] Construct database queries returning single results
- [ ] Construct database queries returning multiple results
- [ ] Insert new items into a database
- [ ] Update or delete existing items in a database
- [ ] Expose a database to other applications via Content Provider
- [ ] Read and parse raw resources or asset files
- [ ] Create persistent preference data from user input
- [ ] Toggle application logic based on preference values  

### Enhanced system integration

Determining appropriate use cases for local persisted data, and designing solutions to implement data storage using files, preferences, and databases. This includes implementing strategies for bundling static data with applications, caching data from remote sources, and managing user-generated private data. Candidates should also be able to describe platform features that allow applications to store data securely and share that data with other applications in Persistent Data Storage.

- [ ] Create an app widget that displays on the device home screen
- [ ] Implement a task to update the app widget periodically
- [ ] Create and display a notification to the user
