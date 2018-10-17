###Custom font for TextView

You make custom font style from "assets" in module. Font file should be in folder "assets", which is located in library.

``
app:customFont="example1.otf"
``

- ####Example

```xml
    <group.bost.customfonttextview.CustomTextView
				android:layout_width="match_parent"
				android:layout_height="wrap_content"
				android:text="Hello World!"
				app:customFont="example1.otf"/>
```

- ####Screenshot

![](https://raw.githubusercontent.com/bost001/DemoCustomTextView/master/screenshot.png)
