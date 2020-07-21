---
page_type: sample
languages:
- java
products:
- azure
description: "This repository contains the sample discussed in Create an Android app to detect and frame faces in an image."
urlFragment: cognitive-services-face-android-detect
---

# Detect and frame faces in an image on Android

This repository contains the sample discussed in [Create an Android app to detect and frame faces in an image](https://docs.microsoft.com/en-us/azure/cognitive-services/face/tutorials/faceapiinjavaforandroidtutorial). The sample uses the Java client library for the Cognitive Services Face service.

## Features

This project framework provides the following features:

* Detects faces in an image.
* Draws a rectangle around each face.

![Android screenshot of a photo with faces framed by a red rectangle](https://docs.microsoft.com/en-us/azure/cognitive-services/face/Images/android_getstarted2.1.PNG)

## Getting Started

### Prerequisites

- You need a subscription key to run the sample. [Create a new Azure account, and try Cognitive Services for free.](https://azure.microsoft.com/free/cognitive-services/)
- [Android Studio](https://developer.android.com/studio/) with minimum SDK 22 (required by the Face client library).
- The [com.microsoft.projectoxford : face : 1.4.3](http://search.maven.org/#artifactdetails%7Ccom.microsoft.projectoxford%7Cface%7C1.4.3%7Caar) Java client library from Maven. It isn't necessary to download the package.

### Quickstart

1. Clone or download the repository.
1. Open Android Studio and select **Open an existing Android Studio project**.
1. Navigate to the *FaceTutorial* folder and click **OK**.
1. In the **Project** pane, expand **app** > **java** > **com.contoso.facetutorial**, then open `MainActivity`.
1. Replace `<API endpoint>` with the Azure region associated with your subscription key.
1. Replace `<Subscription Key>` with your subscription key.
1. Run the app.
1. Browse and select an image containing faces.
1. Wait a few seconds for the Face service to respond.

For more information, see [Create an Android app to detect and frame faces in an image](https://docs.microsoft.com/en-us/azure/cognitive-services/face/tutorials/faceapiinjavaforandroidtutorial).

## Resources

- [Face service documentation](https://docs.microsoft.com/en-us/azure/cognitive-services/face/)
- [Face API](https://docs.microsoft.com/en-us/azure/cognitive-services/face/apireference)
