# Difference Between MVC(Model View Controller) & MVP (Model View Presenter) &  MVVM(Model View ViewModel) architecture.

## MVC (Model View Controller) architecture
* **Model:** Model in Android can be data coming from within your application (including Shared Preferences), Database (in Cursor, or via other Data Access Object) or externally (via Cursor to other Data Contract) or we can say where we implement our business logic.
* **View:** is layout (XML file ,UI components/Widget) 
* **Controller:** is an Activity(Click Events, FindViewbyId etc)

## MVP (Model View Presenter) architecture

* **View:** is layout (XML file ,UI components/Widget) 
* **Model:** Model in Android can be data coming from within your application (including Shared Preferences), Database (in Cursor, or via other Data Access Object) or externally (via Cursor to other Data Contract) or we can say where we implement our business logic.
* **Presenter:** The Presenter acts as the middleman. It retrieves data from the Model and shows it in the View. It also processes user actions forwarded by the View.


## MVVM (Model View ViewModel) architecture 
* **Model:** Model in Android can be data coming from within your application (including Shared Preferences), Database (in Cursor, or via other Data Access Object) or externally (via Cursor to other Data Contract).
* **View:** All the elements displayed in GUI, that include android.widget.* family, and your custom views.
* **ViewModel:** ViewModel exposes properties and commands for the View, it also serves in data binding between the View and the Model. In Android, most of this job is done in Activity.
