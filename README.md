# Translator-App
>This app is an easy way to learn machine learning.

## Setup

Make sure to delete file google-service.json and then build your own file, i think this video will help you (https://www.youtube.com/watch?v=nep85PD8U7M&ab_channel=CubixSol)

### Add dependencies :
dependencies {

    implementation 'androidx.appcompat:appcompat:1.4.2'
    implementation 'com.google.android.material:material:1.6.1'
    implementation 'androidx.constraintlayout:constraintlayout:2.1.4'
    implementation 'com.google.firebase:firebase-core:21.0.0'
    implementation 'com.google.firebase:firebase-ml-natural-language:22.0.1'
    implementation 'com.google.firebase:firebase-ml-natural-language-language-id-model:20.0.8'
    implementation 'com.google.firebase:firebase-ml-natural-language-translate-model:20.0.9'
    testImplementation 'junit:junit:'
    androidTestImplementation 'androidx.test.ext:junit:1.1.3'
    androidTestImplementation 'androidx.test.espresso:espresso-core:3.4.0'
}

### Add this permission in AndroidManifest.xml :
`
<uses-permission android:name="android.permission.INTERNET" />
<uses-permission android:name="android.permission.RECORD_AUDIO" />
`




Preview Project :


https://user-images.githubusercontent.com/82699596/177057162-6dd046b9-04ea-4c58-9211-149cda0aaec5.mp4


## Acknowledgements

- This project was inspired by GeeksforGeeks
- This project was based on [this tutorial](https://www.youtube.com/watch?v=i58g-EPG5_s&ab_channel=GeeksforGeeks).
- Many thanks to GeeksforGeeks

