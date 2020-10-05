# Difference Between MVC(Model View Controller) & MVVM(Model View ViewModel)

## MVC Model View Controller
### MVC vs MVVM
* **Model:** Model in Android can be data coming from within your application (including Shared Preferences), Database (in Cursor, or via other Data Access Object) or externally (via Cursor to other Data Contract) or we can say where we implement our business logic.
* **View:** is layout (XML file ,UI components/Widget) 
* **Controller:** is an Activity(Click Events, FindViewbyId etc)

## MVVM architecture 
* **MVVM architecture is a Model-View-ViewModel architecture.**
* **Model:** Model in Android can be data coming from within your application (including Shared Preferences), Database (in Cursor, or via other Data Access Object) or externally (via Cursor to other Data Contract).
* **View:** All the elements displayed in GUI, that include android.widget.* family, and your custom views.
* **ViewModel:** ViewModel exposes properties and commands for the View, it also serves in data binding between the View and the Model. In Android, most of this job is done in Activity.
