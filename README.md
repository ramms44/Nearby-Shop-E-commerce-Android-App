Nearby Shops Tweet

<a href="buymeacoffee.com/?via=ramms44" target="_blank"><img src="https://cdn.buymeacoffee.com/buttons/default-orange.png" alt="Buy Me A Coffee" height="41" width="174"></a>

Self-Hosted Mobile Based Hyperlocal and Food Delivery Platform

Commercial Use Permitted
All the source code of the Nearby Shops Open-Source project is released under a liberal MIT license which allows you to use this software for commercial use.



Nearby Shops is an Open-Source food delivery, grocery and hyperlocal app platform. You can install your self-hosted instance on Digital Ocean or AWS and get your grocery or food delivery market up and running for just $ 5 per month in hosting fees.

Nearby Shops implements Alibaba's Grocery Online-to-Offline Concept. Customers can place and order from the app and pick it up in the store. Home Delivery is also available !

The installation guide and app customization guide is provided at http://developer.nearbyshops.org

Website : https://nearbyshops.org | Developers Guide: http://developer.nearbyshops.org

Get it on Google Play

    

🚩 Table of Contents
Concept
Tech Stack and App Architecture
Features and highlights
Screenshots
Libraries Used
Third Party Integrations
Community forum
Source Code for Shop Owner and Admin app and REST API
Contributions Required
Development Instructions
Nonprofit and Open-Source
Commercial Use
License
Concept
Nearby Shops is a Hyperlocal Shopping platform where a customer can buy directly from the shops available in his/her local area and get their orders delivered to their home or just pick the order up from the shop.

In the new emerging world, customers are getting tired of going outside the home to shop every day. They would much prefer to simply place an order and have the products delivered to their home the same day.

Conventional e-commerce has issues ... the delivery takes a long time and it's more difficult to trust unknown vendors whom you cannot see and meet. Hyperlocal e-commerce solves these issues because delivery is faster and customers can reach out to the vendors easily.

Nearby Shops can also be used as a food Delivery platform where restaurants can use it to deliver food.

Nearby Shops implements Alibaba's New Offline-to-Online Concept, where customers discover products online and then pick those products up from physical stores.

Online to Offline

Tech Stack and app Architecture
Uses Android Jetpack and Google’s Recommended Architecture Patterns - Migration to MVVM is planned

Written in both Java and Kotlin : Migration to kotlin is planned and will be coming in near future

Built using Butterknife, Retrofit, Ok-HTTP, Picasso, Dagger, and the Mapbox Android SDK

User-Interface is made using the modular View-Holder Pattern which makes the UI blocks modular, easy to reuse, modify and understand.

The app uses Single Activity Architecture, where most of the screens are implemented as fragments and there are only 2-3 activities in the entire project.

The project has 3 Android apps. One app each for the end-user, shop-owner and adminstrator. There is also a JSON-based REST API on the backend. The source-code for the REST API is provided.

Features and Highlights
Support for Multiple Currencies : You can set your locale and country and currency for your local market will be set accordingly.

Mobile Based - Multi-Vendor Platform where customers can send orders to multiple Shops / Restaurants

Integrations for Sending SMS-OTP, E-mail and Push Notifications are available

Order Tracking, with live status updates for customers using E-mail, SMS and Push Notifications

Rating and Reviews for items and shops

Home delivery and pick-up from the shop (Online-to-Offline) Shopping Concept is Supported

Location based filtering is available, which means that customers will see only those shops which can deliver to their address -- other shops will be filtered out.

Vendors / Shop-Owners can track orders through orders inventory and update the order progress !

By adding delivery staff, shop-owners can deliver orders by themselves. Shared delivery logistics will also be available in future releases of Nearby Shops.

Billing and payments are supported. Shop-owners are billed according to the number of orders they deliver successfully. And Service Providers (Market Owners) can collect payments from the shop-owners.

App Customization Permitted - You can whitelabel or customize the android app with your own branding using this customization guide. https://developer.nearbyshops.org/installation/customize-apps.html

Nearby Shops Multi-Market Mode - you can add your local market to nearby shops market discovery service and your market becomes visible and accessible to Global audience of Nearby Shops app. Read more about Nearby Shops multi-market mode !

Commercial Use - This is not just a hobby project and you can actually use it to setup your business and earn some real money.

Screenshots
    

Libraries Used
Android-Jetpack, Retrofit, Ok-Http, Event-Bus, Picasso, butterknife, dagger2, U-Crop, Gesture Views, Smiley Rating, Mapbox Android SDK

Third Party Integrations
SMS-OTP using MSG91 (More Integrations coming soon ...)

E-mail using Simple-Java-Mail E-mail Library

Push Notifications using Firebase and One-Signal

Maps using Mapbox Android SDK and Google Maps

Payment Gateway (Coming Soon ...)

Community - Need Help ?
If you want any help regarding anything. Feel free to contact us -- send a message through our forum or you can simply post an issue. Your issues will not be ignored and you will surely receive help.

Reach out to us - Please Visit - https://forum.nearbyshops.org

Source code for Shop-Owner, Admin app and Server Side
If you want to see source code for the Shop-Owner app, Admin-app and the server side -- links are provided below

Shop-Owner app : https://github.com/SumeetMoray/Nearby-Shops-Shop-Owner-Android-app

Admin app : https://github.com/SumeetMoray/Nearby-Shops-Admin-App

Source code for Server Side JSON Based REST API is available in this repository https://github.com/SumeetMoray/Nearby-Shops-API

Contributions Welcome
https://forum.nearbyshops.org/t/project-roadmap-and-contributions-required/34/4

Improved Search with Search Suggestions for android app

Develop a PWA and Web app for Nearby Shops

i18n Internationalization support

Payment Gateway Integrations

Performance Testing and Optimization

Suggestions and Improvements in App Architecture

Code Review and Architecture

Development Instructions
If you're a developer looking to work on the source code follow these instructions to start developing !

git clone https://github.com/SumeetMoray/Nearby-Shops-End-User-Android-app.git
You should now open the project with the latest version of Android Studio. The project will not compile unless you add the following property in the local.properties file.

This project uses mapbox android sdk which requires mapbox style url. To add the style url in the project open this project in the android studio and add the Mapbox Style URL in the local.properties file.

It is okay if you don't have an actual Mapbox style url. In that case, just put some dummy text in place of the url.

mapbox_style_url="your-mapbox-style-url"
Nonprofit and Open Source
Nearby Shops is not just open-source its Nonprofit also. Which means that we are not under any obligation to commertialize the project. This is good because commertialization of an open-source project often leads to restrictions in licensing.

This is an assurance from our side that this project will always be free and open-source.

Commercial Use Permitted
All the source code of Nearby Shops Open-Source project is released under a liberal MIT license which allows you to use this software for commercial use.

License
The MIT License (MIT) Copyright 2017-19 Bluetree Software LLP, Inc. | http://nearbyshops.org

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the “Software”), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED “AS IS”, WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
