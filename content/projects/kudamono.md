---

draft: false

date: 14

title: "Kudamono - Digital QR Menu App"
subtitle: "Kudamono is a platform that helps cafes and restaurants to show their menus."
image: "/project-images/kudamono/cover.webp"

categories: [Web App, Mobile App, UI/UX Design]

---

# Kudamono - Digital QR Menu App Platform

<br>

<center>

  <div  style="height:200px; width:200px; border-radius:32px; box-shadow: rgba(149, 157, 165, 0.35) 0px 8px 24px;  display: flex; justify-content: center; align-items: center;background-color:white">
  <img  src="/project-images/kudamono/logo.webp" alt="App Logo" style="height:135px"/>
</div>

  <a href="https://kudamono.app">Website</a>
</center>

## Summary 

It's my first SaaS and Startup project that helps to create their own qr menus to their restaurants/cafes.

I tried to start my own business, It was a pure disaster but I learned a lot!

<br>

Here are my little notes about my journey and app features!

<br>

**This Project contains 4 types of app!**

1. Website (HTML/CSS) - To Engage with the world!
2. Web App (Flutter/VueJS) - To scan QR Codes and see the digital menus! (Both Mobile app and Web App for best UX)
3. Customer Console (CMS) (Flutter/VueJS) -  To manage their own accounts! 
4. Admin Panel (Flutter) - To manage my customers and show some charts!

---
 ## Screnshots 

![Screenshots](/project-images/kudamono/cover.webp)

## Download

<a href="https://play.google.com/store/apps/details?id=com.kudamonodes.kudamono_console">
  <img src="/images/googleplay.webp" alt="GooglePlay" height="65px"/>
</a>
<a href="https://apps.apple.com/us/app/kudamono-console/id1606631507">
  <img src="/images/appstore.webp" alt="AppStore" height="65px"/>
</a>


## My Roles
- UI/UX Designer - [Figma]
- Mobile App Developer - [Flutter]
- Frontend (Web App) Developer - [VueJS, NuxtJS]
- Backend Developer - [NodeJS, Firebase, MongoDB, Google Cloud Run, Cloudflare Pages, AWS..]

<br>

---

<br>

### Website (Web)
**Highlighted App Features**
I used Bootstrap and Tailwind for CSS and wrote some pure JS scripts!

<br>

---

### Digital QR Menu App (Mobile/Web)
At first, I made Web and Mobile app at once with Flutter

But even If SEO is not important for this project, bundle size and slow loading was the holdback not to use Flutter for web!

That's why I learned VueJS/NuxtJS from scratch and made the menu web app!

**Highlighted App Features**
- Search
- Localization
- Dark Theme 

**Technical Features**
- nuxt/axios - HTTP client for requests
- nuxt/i18n - Localization
- vuex - State management
- vuetify - UI kit

<br>

---

### User Console (CMS) App (Mobile/Web)

**Highlighted Technical Features**
- State Management - [riverpod](https://pub.dev/packages/riverpod)
- Dependency Injection - [riverpod](https://pub.dev/packages/riverpod)
- Navigation - [go_router](https://pub.dev/packages/go_router)
- Modelling - [freezed](https://pub.dev/packages/freezed) & [json_serializable](https://pub.dev/packages/json_serializable)
- Realtime Chat (Customer Service) - [firebase_database](https://pub.dev/packages/firebase_database) 
- Push Notifications -[firebase_messaging](https://pub.dev/packages/firebase_messaging)
- In App Purchase - [in_app_purchase](https://pub.dev/packages/in_app_purchase)
- Charts - [fl_chart](https://pub.dev/packages/fl_chart)
- Reorderable Lists - [reorderables](https://pub.dev/packages/reorderables)
- Generate QR Codes - [qr_flutter](https://pub.dev/packages/qr_flutter)
- Analytics - [firebase_analytics](https://pub.dev/packages/firebase_analytics) & [firebase_crashlytics](https://pub.dev/packages/firebase_crashlytics)

<br>

---

### Admin Panel App (Mobile)
**Highlighted Technical Features**
- State Management - [riverpod](https://pub.dev/packages/riverpod)
- Dependency Injection - [riverpod](https://pub.dev/packages/riverpod)
- Navigation - [go_router](https://pub.dev/packages/go_router)
- Modelling - [freezed](https://pub.dev/packages/freezed) & [json_serializable](https://pub.dev/packages/json_serializable)
- Realtime Chat (Customer Service) - [firebase_database](https://pub.dev/packages/firebase_database) 
- Push Notifications -[firebase_messaging](https://pub.dev/packages/firebase_messaging)

<br>

---

### Backend (Firebase/NodeJS)

**NodeJS**
- Express - Web framework for api requests
- Axios - HTTP client
- AWS S3 - Store the image files
- Compression - Compress the requests
- Helmet - Better security
- Mongoose - MongoDB ODM
- Multer - Handle images (multipart/form-data)
- sharp - Resizing the images
- imagemin - Compressing images

**Others**
- Firebase - Notifications, Authentication, Analytics, Realtime Chat
- Google Cloud Run - Deploy NodeJS API
- Cloudflare Pages - Deploy Websites
- MongoDB - database to store all datas
- AWS - (S3) Store image files

<br>

---

### Some Lessons That I Learned

- Flutter Web is not ready for production yet (Because of load time, bundle size, routing problems.. .)
- If you do everything on your own, please don't reinvent the wheel :) (I even rent a server and manage the backend from stratch it was fun actually but not suitable for the one-guy-startup concept)
- MVP is the key! don't add too much features!
- Don't overengineer!
- Coding is good but Marketing is as well!