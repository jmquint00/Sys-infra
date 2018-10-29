# Sys-infra
Sys-infra is an inventory application

Auth

![image](https://user-images.githubusercontent.com/24324570/47654868-24793000-db62-11e8-8d02-045b6e8ac1b9.png)![image](https://user-images.githubusercontent.com/24324570/47654905-3a86f080-db62-11e8-9865-b5aca2b746b1.png)![image](https://user-images.githubusercontent.com/24324570/47654920-44a8ef00-db62-11e8-9d61-53f5e87ad7b5.png)


Stats

![image](https://user-images.githubusercontent.com/24324570/47654960-5b4f4600-db62-11e8-80a4-edaba060e8ff.png)![image](https://user-images.githubusercontent.com/24324570/47655004-7326ca00-db62-11e8-9639-b7529b84eb4e.png)

Assets

![image](https://user-images.githubusercontent.com/24324570/47655123-b41ede80-db62-11e8-9d1d-6d9fb9d5e74f.png)![image](https://user-images.githubusercontent.com/24324570/47655151-c39e2780-db62-11e8-9deb-360c22a4722a.png)![image](https://user-images.githubusercontent.com/24324570/47655068-96517980-db62-11e8-9ca6-e8525c6316a9.png)![image](https://user-images.githubusercontent.com/24324570/47655089-9d788780-db62-11e8-9b5f-fe061f229512.png)


Used Libraries

    implementation fileTree(include: ['*.jar'], dir: 'libs')
    implementation 'com.android.support:appcompat-v7:27.1.1'
    implementation 'com.android.support:design:27.1.1'
    implementation 'com.android.support:recyclerview-v7:27.1.1'
    implementation 'com.android.support:cardview-v7:27.1.1'
    implementation 'com.android.support.constraint:constraint-layout:1.1.3'
    implementation 'com.google.android.gms:play-services-maps:16.0.0'

    // retrofit, gson, OkHttp
    implementation 'com.google.code.gson:gson:2.8.5'
    implementation 'com.squareup.retrofit2:retrofit:2.4.0'
    implementation 'com.squareup.retrofit2:converter-gson:2.4.0'
    implementation 'com.squareup.okhttp3:logging-interceptor:3.9.1'
    implementation 'com.squareup.okhttp3:okhttp:3.11.0'

    //picasso, implementing with 2.5.5 because of in-app messaging
    implementation 'com.squareup.picasso:picasso:2.5.2'

    //Firebase
    implementation 'com.google.firebase:firebase-core:16.0.4'
    implementation 'com.google.firebase:firebase-messaging:17.3.3'
    implementation 'com.google.firebase:firebase-inappmessaging-display:17.0.2'
    implementation 'com.google.firebase:firebase-auth:16.0.4'
    implementation 'com.firebaseui:firebase-ui-auth:4.2.0'
    implementation 'com.google.firebase:firebase-database:16.0.3'
    
    //MPAndroidChart for grahics 
    implementation 'com.github.PhilJay:MPAndroidChart:v3.0.3'

    //test
    testImplementation 'junit:junit:4.12'
    androidTestImplementation 'com.android.support.test:runner:1.0.2'
    androidTestImplementation 'com.android.support.test.espresso:espresso-core:3.0.2'
