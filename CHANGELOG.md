## Detect and frame faces in an image on Android - Changelog

# 1.4.3 (2018-07-11)

*Features*

* Import of sample code from [Create an Android app to detect and frame faces in an image](https://docs.microsoft.com/en-us/azure/cognitive-services/face/tutorials/faceapiinjavaforandroidtutorial).
* Targets [com.microsoft.projectoxford : face : 1.4.3](http://search.maven.org/#artifactdetails%7Ccom.microsoft.projectoxford%7Cface%7C1.4.3%7Caar) Java client library from Maven.
* New `AlertDialog` to display errors returned by the Face service.
* Increased rectangle stroke width for better frame visibility.

*Bug Fixes*

* Layout uses `android:paddingLeft="@dimen/activity_horizontal_margin"` and others, but doesn't define the `dimen`'s.

*Breaking Changes*

* none
