# adaptive_app_demos

Demo code for adaptive app development techniques.




# SS : 
<br/><br/>

<img src="https://i.imgur.com/9BQ0mnv.png" />
<img src="https://i.imgur.com/WtV4jZr.png" />
<img src="https://i.imgur.com/oVfjcaq.png" />
<img src="https://i.imgur.com/cFoQl3G.png" />
<img src="https://i.imgur.com/qgKrW81.png" />
<img src="https://i.imgur.com/Xwspfzg.png" />
<img src="https://i.imgur.com/Jt2fTIH.png" />
<img src="https://i.imgur.com/5ZR1kck.png" />
<img src="https://i.imgur.com/zfrJrLH.png" />


---

<br/>

### Demonstrated in this repo:

[https://github.com/gskinnerTeam/flutter-adaptive-demo](https://github.com/gskinnerTeam/flutter-adaptive-demo)

* Login view
  * re-flows from vertical to horizontal layout depending on screen size
  * shows how to use horizontal constraints to stop an item from growing excessively large
* Main App Scaffold
  * a responsive scaffold that changes from tab bar + drawer, to a combined side-menu for larger screens
  * children are shared between widgets showing how you can reuse the same widget in multiple places
* A custom title bar is implemented for all platforms using a single widget
  * VisualDensity is controlled with a button inside the title bar, and changes density across the entire app
  * VisualDensity button is right-aligned on macOS to not conflict with native window controls
* AdaptiveGrid uses LayoutBuilder to create a responsive grid,
  * //TODO: shows cross platform multi-select behavior
  * //TODO: shows popups and right-click menu to delete
  * //TODO: shows select all and delete behavior
* AdaptiveDataTable uses LayoutBuilder to add/remove columns in a table, depending on space available
* AdaptiveReflow uses LayoutBuilder to reflow between 3 different layout types: Vertical, Horizontal and Mixed.
* FocusExamples show various examples of how you can control focusable widgets and listen for key events
* Logout dialog contains adaptive logic to place the "Ok" button on the left-hand side on Windows, as per OS convention.
