# FlutterFlow-Image-Cropper

After you copied the cropper code, add these Pubsec Dependencies

crop_your_image: 1.1.0
firebase_storage: 12.1.0
firebase_core_web: 2.17.2
firebase_core_platform_interface: 5.1.0
firebase_core: 3.1.1
firebase_performance_web: 0.1.6+10
firebase_performance: 0.10.0+2
firebase_performance_platform_interface: 0.1.4+38
firebase_auth: 5.1.1
firebase_auth_web: 5.12.3
firebase_auth_platform_interface: 7.4.1
cloud_firestore_web: 4.0.2
cloud_firestore_platform_interface: 6.2.8
cloud_firestore: 5.0.2
firebase_storage_web: 3.9.10
firebase_storage_platform_interface: 5.1.25

(Note: Do not create a folder named "users" in your Firebase Storage)
There will be no error in your custom widgets anymore.




Next step, in your newly created Component, do the same to the video but don't set your Custom Code Widget to infinite. Set it to 350 width and 500 height, the same with its container.
(The Crop botton should be visible by now)




The last part. The Conditional Action 1 in Action Flow Editor should be "Is Data Uploading is set".   NOT "Uploaded Local File 2" or "Uploaded Local File 1".


