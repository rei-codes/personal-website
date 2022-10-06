---

draft: false

date: 15

title: "Poshta UA (ПОШТА УА)"
subtitle: "A Complete Mobile App System Solution for A Cargo Company in Ukraine."
image: /project-images/poshta/cover.webp

categories: [Mobile App]

---

> DROPPED

# Poshta UA (ПОШТА УА) - A Cargo Company in Ukraine

<br>

<center >
<div  style="height:200px; width:200px; border-radius:32px; box-shadow: rgba(149, 157, 165, 0.35) 0px 8px 24px;  display: flex; justify-content: center; align-items: center;background-color:white">
  <img  src="/project-images/poshta/logo.webp" alt="App Logo" style="height:100px"/>
</div>

<a href="https://www.poshta.ua/">Website</a>
</center>

## Summary 

We built 3 apps in total, but we had to drop and unpublish them all because of the Ukraine invasion.
That's why I can't show you any reference for it! But I'll explain all the process that we had!

Unfortunately, I also can't provide any screenshots, too, due to privacy restrictions.

## My Roles
- Mobile App Developer - [Flutter]

<br>

## Apps
---

### 1. App For Customers 

**Highlighted App Features**
- Localization 
- Authentication (Including OTP)
- Payment Integration
- Realtime Messaging
- Push Notifications
- Search 
- Delivery Tracking

**Technical Features**
- State Management - [riverpod](https://pub.dev/packages/riverpod)
- Dependency Injection - [riverpod](https://pub.dev/packages/riverpod)
- Navigation - [go_router](https://pub.dev/packages/go_router)
- Localization - Our own implementation
- Modelling - [freezed](https://pub.dev/packages/freezed) & [json_serializable](https://pub.dev/packages/json_serializable)
- Realtime Chat - [socket_io_client](https://pub.dev/packages/socket_io_client)
- Push Notifications - [firebase_messaging](https://pub.dev/packages/firebase_messaging)
- Delivery Tracking - [OpenStreetMap](https://www.openstreetmap.org/#map=6/39.031/35.252) & [socket_io_client](https://pub.dev/packages/socket_io_client)

--- 
### 2. App For Delivery Guys

**Highlighted App Features**
- Localization 
- Authentication (with OTP and NFC Support)
- Push Notifications
- Search 
- Delivery Tracking
- Call Users 
- Daily Delivery Route Generation on Map
- Scan Barcodes
- Generate Barcodes
- Send Realtime Metadata to Server
- Bluetooth Connection with Scanner

**Technical Features**
- State Management - [riverpod](https://pub.dev/packages/riverpod)
- Dependency Injection - [riverpod](https://pub.dev/packages/riverpod)
- Navigation - [go_router](https://pub.dev/packages/go_router)
- Localization - Our own implementation
- Modelling - [freezed](https://pub.dev/packages/freezed) & [json_serializable](https://pub.dev/packages/json_serializable)
- Push Notifications - [firebase_messaging](https://pub.dev/packages/firebase_messaging)
- Analytics - [firebase_analytics](https://pub.dev/packages/firebase_analytics) & [firebase_crashlytics](https://pub.dev/packages/firebase_crashlytics)
- Sending App Information (current location, status, etc.) - [web_socket_channel](https://pub.dev/packages/web_socket_channel)
- Realtime Tracking - [OpenStreetMap](https://www.openstreetmap.org/#map=6/39.031/35.252) & [socket_io_client](https://pub.dev/packages/socket_io_client)
- Bluetooth - [flutter_bluetooth_serial](https://pub.dev/packages/flutter_bluetooth_serial)
- NFC - [nfc_manager](https://pub.dev/packages/nfc_manager)
- Barcode Scanner - [flutter_barcode_scanner](https://pub.dev/packages/flutter_barcode_scanner)
- Generate Barcode - [barcode](https://pub.dev/packages/barcode)
- VoIP (Voice over IP) - [sip_ua](https://pub.dev/packages/sip_ua)
- Map - [OpenStreetMap](https://www.openstreetmap.org/#map=6/39.031/35.252)

--- 

### 3. In-house App For Internal Usage -> Shifts, Announcements, etc. 

**Technical Features**
- Authentication (with OTP and NFC Support)
- State Management - [riverpod](https://pub.dev/packages/riverpod)
- Dependency Injection - [riverpod](https://pub.dev/packages/riverpod)
- Navigation - [go_router](https://pub.dev/packages/go_router)
- Localization - Our own implementation
- Modelling - [freezed](https://pub.dev/packages/freezed) & [json_serializable](https://pub.dev/packages/json_serializable)
- Push Notifications - [firebase_messaging](https://pub.dev/packages/firebase_messaging)
- Charts - [fl_chart](https://pub.dev/packages/fl_chart)