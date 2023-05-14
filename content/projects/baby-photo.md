---

draft: false

date: 11

title: "Baby Photo - A Photo Editor App For Parents"
subtitle: "An photo editor app which focused on parents who want to edit their babies with cute stickers and other stuff!"
image: "/project-images/baby-photo/ss.webp"

categories: [Mobile App, UI/UX Design]

---


# Baby Photo - A Photo Editor App For Parents 

<br>

<center>
  <img  src="/project-images/baby-photo/logo.webp" alt="App Logo"
    style="height:200px; width:200px; border-radius:32px; box-shadow: rgba(149, 157, 165, 0.35) 0px 8px 24px;"
  />
</center>

## Summary 
An photo editor app which focused on parents who want to edit their babies with cute stickers and other stuff!

---
 
![Screenshots](/project-images/baby-photo/ss.webp)

## Download

<a href="https://play.google.com/store/apps/details?id=com.artlyapp.android">
  <img src="/images/googleplay.webp" alt="GooglePlay" height="65px"/>
</a>
<a href="https://apps.apple.com/tr/app/baby-photo-editor-milestone/id1350838310">
  <img src="/images/appstore.webp" alt="AppStore" height="65px"/>
</a>
<a href="https://www.figma.com/community/file/1139196892519123695">
  <img src="/images/figma.webp" alt="figma" height="65px"/>
</a>


## My Roles
- UI/UX Designer - [Figma]
- Mobile App Developer - [Flutter]

## Highlighted App Features
- Localization 
- Photo Filters
- Photo Manipulating - Brightness, Exposure, Contrast..
- Photo Transforming - Cropping, Rotating, Mirroring..
- Adding Personalized Texts on Image
- Adding Cute Stickers on Image
- Pre-made Ready to Use Templates
- Undo/Redo Support
- Image Compression Support
- Collage - Brings the Photos Together.


## Technical Features
- Localization - [intl](https://pub.dev/packages/intl) 
- State Management - [provider](https://pub.dev/packages/provider) 
- Dependency Injection - [get_it](https://pub.dev/packages/get_it)
- Navigation - vanilla
- Modelling - [freezed](https://pub.dev/packages/freezed) & [json_serializable](https://pub.dev/packages/json_serializable)
- MVVM - [stacked](https://pub.dev/packages/stacked) 

## Some Notes
There were lots of challenges in this app but we overcame all of them successfully!

<div style="height:5px"> </div>
<p style="font-size:20px;font-weight:bold;"> Such as; </p>
<div style="height:5px"> </div>

**Nested Bottombar**

- Every bottombar item have their own stack and they had to work together in harmony for sure!

**Undo/Redo System**
  
- While editing the image, App use very different approaches to edit for every features like adding stickers, manipulating the image, or adding filters..

**Slow Image Manipulating**

- Dart's official image library was too slow to perform image manipulating operations. we had to take care of it carefully for the sake of high performance.

**Adding Customizable Stickers and Texts on the image**

- There was no good package for it. We had to make it from scratch using basic features like drag and drop, and transform..

**Collage photos and pre-made templates**

- They requires a bit math and some adaptive design techniques ^^"