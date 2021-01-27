# Progressive Web Apps - Complete Guide
This source code is part of Maximilian Schwarzmüller's "Progressive Web Apps - Complete Guide" course on udemy.com.

# How to Use
You need [Node.js](https://nodejs.org) installed on your machine. Simply download the installer from [nodejs.org](https://nodejs.org) and go through the installation steps.

Once Node.js is installed, open your command prompt or terminal and **navigate into this project folder**. There, run `npm install` to install all required dependencies.

Finally, run `npm start` to start the development server and visit [localhost:8080](http://localhost:8080) to see the running application.

# Manifest Properties

"name": "Sweaty - Activity Tracker", Long name of app
"short_name": "Sweaty", Short name of app
"start_url": "/index.html", Which page to load on startup
"scope":".", Which pages are included in "PWA Experinece"
"display": "standalone", Should it look like a standalone app?
"background_color": "#fff", Bg whilst loading & on Splashscreen
"theme_color":"#3f51b5", Theme color
"description":"keep running until you are super sweaty!", description
"dir":"ltr", Read direction of your app
"lang":"en-US", main lang of app
"orientation":"portrait-primary", "Set (and enforce) default orientation
"icons":[...] Configure icons

"icons": [
    {
        "src": icon path,
        "type": image type,
        "sizes": icon size
        # 48x48 and 96x96
    }
]

"related_applications": [
    {
        "platform": "play",
        "url": "https://play.google.com/...",
        "id": "com.example.app1"
    }
]

Checklist

1. Add Manifest.json in index.html file in all folders - OK