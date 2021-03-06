# Xamarin.Forms - iOS - List of SwipeViews

Apparently there is an iOS bug in the [SwipeView](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/swipeview) component when it's contained in a [ListView](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/listview/).
This project is a demo of this bug.

![demo](https://github.com/ragu89/xam-list-of-swipeviews/blob/main/assets/readme-demo.gif)

The bug is specially there when the [caching strategy](https://docs.microsoft.com/en-us/xamarin/xamarin-forms/user-interface/listview/performance#caching-strategy) of the ListView is configured as **RecycleElement**.
But it's also possible to reproduce without caching strategy.
