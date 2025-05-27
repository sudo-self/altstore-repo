## altstore-repo 
https://tinyurl.com/sudo-self

Add the source<br>

<a href="https://raw.githubusercontent.com/sudo-self/altstore-repo/main/apps.json">https://raw.githubusercontent.com/sudo-self/altstore-repo/main/apps.json

![Apps](https://github.com/user-attachments/assets/1f53b1ef-b027-4fe8-8bd4-d829aae313f1)


### AltStore Source Example

```
{
  "name": "My Example Source",
  "subtitle": "A source for all of my apps",
  "description": "Welcome to my source! Here you'll find all of my apps.",
  "iconURL": "https://example.com/source_icon.png",
  "headerURL": "https://example.com/source_header.png",
  "website": "https://example.com",
  "patreonURL": "https://patreon.com/mycampaign"
  "tintColor": "#F54F32",
  "featuredApps": [
    "com.example.myapp",
    "com.example.anotherapp"
  ],
  "apps": [],
  "news": [],
}
```
### Adding iOS Apps Example

```

"apps": [
    {
        "name": "My Example App",
        "bundleIdentifier": "com.example.myapp",
        "marketplaceID": "12345678",
        "developerName": "Example Developer",
        "subtitle": "An awesome app.",
        "localizedDescription": "This is an awesome app only available on AltStore.",
        "iconURL": "https://example.com/myapp_icon.png",
        "tintColor": "#F54F32",
        "category": "utilities",
        "screenshots": [
            "https://example.com/myapp_screenshot1.png",
            "https://example.com/myapp_screenshot2.png",
            "https://example.com/myapp_screenshot3.png"
        ],
        "versions": [],
        "appPermissions": {},
        "patreon": {},
    },
]

```
### App versions

```

"versions": [
  {
    "version": "1.0",
    "buildVersion": "60",
    "date": "2023-03-30",
    "localizedDescription": "First AltStore release!",
    "downloadURL": "https://myapp.com/myapp-1.0.ipa",
    "size": 79821,
    "minOSVersion": "12.0",
    "maxOSVersion": "16.3"
  },
]

```
### Privacy

```
"privacy": {
    "NSMicrophoneUsageDescription": "App uses the microphone to record audio.",
    "NSCameraUsageDescription": "App uses the camera to take photos."
}
```
