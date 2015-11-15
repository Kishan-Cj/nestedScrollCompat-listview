# nestedScrollCompat-listview
This is Android's good old List View with Material Design properties, i.e it has nested scroll enabled, so that the Views/toolbars collapse on scrolling.

**Very Important**
As per Android's guidelines, the scrolling content which collapses the toolBar or View, i.e the view with the tag **app:layout_behavior="@string/appbar_scrolling_view_behavior"** should always be declared **above** & outside the **AppBar Layout**

In the example project above, the fragment has a listview which collapses the toolbar, hence the fragment is declared above appbarlayout. Fragment is declared with the property, **app:layout_behavior="@string/appbar_scrolling_view_behavior"**.

**Directions for use**

1) Replace all your **listview** tags with **com.mkishan.nestedScrollCompat.view.CompatListView** tag and add the **app:layout_behavior="@string/appbar_scrolling_view_behavior"** to the parent layout or accordingly.

2) All default listview properties are applicable to this custom list view in XML as well as Java.

![Settings](https://cloud.githubusercontent.com/assets/1867155/11167811/c66a8dd6-8b98-11e5-8f8d-589290d5946a.gif)
![Settings](https://cloud.githubusercontent.com/assets/1867155/11167852/9d60ad1a-8b9a-11e5-8b15-50659ea06635.png)
