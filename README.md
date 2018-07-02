# Journal-App
This project allows its users to pin down their thoughts and feelings at any given moment. 
It was developed to store data into Google's online database, Firebase Realtime Database to keep users' information for as long as they wish to. Every note can be recovered even when you lose your cellphone, unless you delete it manually.

# Basic Installation Instructions:
  Clone JournalApp.7Zip
  Install 7-Zip File Extractor
  Select Repository, Right-click and Select "Extract Files" to any folder of your choice.
  Open Project in Android Studio
  
  Install these Dependencies to build.gradle (Module:app) like:
   
    dependencies {
      compile 'com.android.support:appcompat-v7:24.2.1'
    
      compile 'com.android.support:recyclerview-v7:24.2.1'
      compile 'com.android.support:design:24.2.1'
    
      compile 'com.google.firebase:firebase-auth:11.0.4'
      compile 'com.google.firebase:firebase-core:11.0.4'
      compile 'com.google.firebase:firebase-database:11.0.4'
      compile 'com.google.android.gms:play-services-auth:11.0.4'
    }
    apply plugin: 'com.google.gms.google-services'

  and this line to build.gradle (Project: "project name") inside dependencies like:
  
    dependencies {
       classpath 'com.google.gms:google-services:3.0.0'
    }
  
# Security Vulnerabilities
Upon discover of any security vulnerability within this project, kindly send an e-mail to buzzydeveloper@gmail.com.
Every security-related issue will be accordingly and promptly addressed.
