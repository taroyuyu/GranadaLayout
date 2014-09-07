GranadaLayout
=============

I know that AutoLayout exists, but I think that it doesn't solve the problem with layouting in iOS. It's too complex and slow, and animating by changing constraints is even more complicated.

This is an attempt to implement a layout system for iOS that works similar to Android. The primary goal is just to implement layout views like ``LinearLayout`` and ``RelativeLayout`` but with simplified options.

Current Status
--------------

- ``LinearLayout`` is already implemented and works flawlessly with the already tested views
- There are categories to support size measurement for some views from UIKit
- Some test controllers are implemented

TODO:
-----
- Add size calculation and tests for all UIKit base views
    - UITextField
    - UISegmentedControl
    - UIWebView
    - UISearchBar
    - UISlider
    - UIProgressView
    - UIActivityIndicatorView
    - UIStepper
    - UIDatePicker
    - UIPickerView
    - UIScrollView (needed?)
- Add size calculation for the layouts, so that they can be embedded in other layouts
- Cache measured size for given measureSpec
- Implement the ``RelativeLayout``
- Test, test, test! -> Unit and snapshot tests
- Create a nicer syntax a la [Masonry](https://github.com/Masonry/Masonry)

Thanks + Acknowledments
-----------------------

- To the developers of the Android Projects, for designing such a simple but powerful layout system

Collaborations
--------------

Collaboration, help and suggestions are very welcome :)
