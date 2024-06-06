# If you can't add modules to installed Unity editor you can download them via links on Hub/Editor/%version%/modules.json

1. open modules.json with a json file reader(you can use a browser)
2. search the name of module in file
3. you will find a download link and a determined destination
4. download the zip then extract it in determined destination

## Its a example for Unity Editor version 2021.3.39f1 :

I downloaded 9 zip files for Unity Android Support contains SDK, NDK, OpenJDK, and Platformtools

{
    "url": "https://download.unity3d.com/download_unity/fb3b7b32f191/TargetSupportInstaller/UnitySetup-Android-Support-for-Editor-2021.3.39f1.exe",
    "integrity": "md5-YTAyYWI0ZWM0MDU1YTQzNjQyMzg1ZGY2MjdkYjM2Njk=",
    "type": "EXE",
    "id": "android",
    "name": "Android Build Support",
    "slug": "2021.3.39f1-windows-x86_64-android",
    "description": "Android Playback Engine",
    "category": "Platforms",
    "downloadSize": 394858496,
    "installedSize": 2015416320,
    "required": false,
    "hidden": false,
    "extractedPathRename": null,
    "preSelected": false,
    "destination": "{UNITY_PATH}",
    "eula": null,
    "subModules": [
      {
        "url": "https://download.unity3d.com/download_unity/open-jdk/open-jdk-win-x64/jdk8u172-b11_4be8440cc514099cfe1b50cbc74128f6955cd90fd5afe15ea7be60f832de67b4.zip",
        "integrity": null,
        "type": "ZIP",
        "id": "android-open-jdk-8u172-b11",
        "name": "OpenJDK",
        "slug": "2021.2.19f1-windows-x86_64-android-open-jdk-8u172-b11",
        "description": "Android Open JDK 8u172-b11",
        "category": "PLATFORM",
        "downloadSize": {
          "value": 153000000,
          "unit": "BYTE"
        },
        "installedSize": {
          "value": 70460000,
          "unit": "BYTE"
        },
        "required": true,
        "hidden": false,
        "extractedPathRename": null,
        "preSelected": false,
        "destination": "{UNITY_PATH}/Editor/Data/PlaybackEngines/AndroidPlayer/OpenJDK",
        "eula": [],
        "subModules": []
      },
      {
        "url": "https://dl.google.com/android/repository/sdk-tools-windows-4333796.zip",
        "integrity": null,
        "type": "ZIP",
        "id": "android-sdk-ndk-tools",
        "name": "Android SDK & NDK Tools",
        "slug": "2021.3.39f1-windows-x86_64-android-sdk-ndk-tools",
        "description": "android-sdk-ndk-tools 26.1.1",
        "category": "PLATFORM",
        "downloadSize": {
          "value": 148000000,
          "unit": "BYTE"
        },
        "installedSize": {
          "value": 174000000,
          "unit": "BYTE"
        },
        "required": true,
        "hidden": false,
        "extractedPathRename": null,
        "preSelected": false,
        "destination": "{UNITY_PATH}/Editor/Data/PlaybackEngines/AndroidPlayer/SDK",
        "eula": [
          {
            "url": "https://dl.google.com/dl/android/repository/repository2-1.xml",
            "integrity": null,
            "type": "TEXT",
            "label": "Android SDK and NDK License Terms from Google",
            "message": "Please review and accept the license terms before downloading and installing Android's SDK and NDK."
          }
        ],
        "subModules": [
          {
            "url": "https://dl.google.com/android/repository/android-ndk-r21d-windows-x86_64.zip",
            "integrity": null,
            "type": "ZIP",
            "id": "android-ndk-r21d",
            "name": "Android NDK",
            "slug": "2021.2.19f1-windows-x86_64-android-ndk-r21d",
            "description": "Android NDK r21d",
            "category": "PLATFORM",
            "downloadSize": {
              "value": 1024000000,
              "unit": "BYTE"
            },
            "installedSize": {
              "value": 3911680000,
              "unit": "BYTE"
            },
            "required": true,
            "hidden": true,
            "extractedPathRename": {
              "from": "{UNITY_PATH}/Editor/Data/PlaybackEngines/AndroidPlayer/NDK/android-ndk-r21d",
              "to": "{UNITY_PATH}/Editor/Data/PlaybackEngines/AndroidPlayer/NDK"
            },
            "preSelected": false,
            "destination": "{UNITY_PATH}/Editor/Data/PlaybackEngines/AndroidPlayer/NDK",
            "eula": []
          },
          {
            "url": "https://dl.google.com/android/repository/efbaa277338195608aa4e3dbd43927e97f60218c.build-tools_r30.0.2-windows.zip",
            "integrity": null,
            "type": "ZIP",
            "id": "android-sdk-build-tools-30.0.2",
            "name": "Android SDK Build Tools",
            "slug": "2021.2.19f1-windows-x86_64-android-sdk-build-tools-30.0.2",
            "description": "Android SDK Build Tools 30.0.2",
            "category": "PLATFORM",
            "downloadSize": {
              "value": 51300000,
              "unit": "BYTE"
            },
            "installedSize": {
              "value": 137248031,
              "unit": "BYTE"
            },
            "required": true,
            "hidden": true,
            "extractedPathRename": {
              "from": "{UNITY_PATH}/Editor/Data/PlaybackEngines/AndroidPlayer/SDK/build-tools/android-11",
              "to": "{UNITY_PATH}/Editor/Data/PlaybackEngines/AndroidPlayer/SDK/build-tools/30.0.2"
            },
            "preSelected": false,
            "destination": "{UNITY_PATH}/Editor/Data/PlaybackEngines/AndroidPlayer/SDK/build-tools",
            "eula": []
          },
          {
            "url": "https://dl.google.com/android/repository/platform-tools_r30.0.4-windows.zip",
            "integrity": null,
            "type": "ZIP",
            "id": "android-sdk-platform-tools-30.0.4",
            "name": "Android SDK Platform Tools",
            "slug": "2021.2.19f1-windows-x86_64-android-sdk-platform-tools-30.0.4",
            "description": "Android SDK Platform Tools 30.0.4",
            "category": "PLATFORM",
            "downloadSize": {
              "value": 8000000,
              "unit": "BYTE"
            },
            "installedSize": {
              "value": 24582871,
              "unit": "BYTE"
            },
            "required": true,
            "hidden": true,
            "extractedPathRename": null,
            "preSelected": false,
            "destination": "{UNITY_PATH}/Editor/Data/PlaybackEngines/AndroidPlayer/SDK",
            "eula": []
          },
          {
            "url": "https://dl.google.com/android/repository/platform-33_r02.zip",
            "integrity": null,
            "type": "ZIP",
            "id": "android-sdk-platforms-33",
            "name": "Android SDK Platforms 33",
            "slug": "6000.0.4f1-windows-x86_64-android-sdk-platforms-33",
            "description": "Android SDK Platforms 33",
            "category": "PLATFORM",
            "downloadSize": {
              "value": 67334130,
              "unit": "BYTE"
            },
            "installedSize": {
              "value": 104794121,
              "unit": "BYTE"
            },
            "required": true,
            "hidden": true,
            "extractedPathRename": {
              "from": "{UNITY_PATH}/Editor/Data/PlaybackEngines/AndroidPlayer/SDK/platforms/android-13",
              "to": "{UNITY_PATH}/Editor/Data/PlaybackEngines/AndroidPlayer/SDK/platforms/android-33"
            },
            "preSelected": false,
            "destination": "{UNITY_PATH}/Editor/Data/PlaybackEngines/AndroidPlayer/SDK/platforms",
            "eula": []
          },
          {
            "url": "https://dl.google.com/android/repository/platform-34-ext7_r02.zip",
            "integrity": null,
            "type": "ZIP",
            "id": "android-sdk-platforms-34",
            "name": "Android SDK Platforms 34",
            "slug": "6000.0.4f1-windows-x86_64-android-sdk-platforms-34",
            "description": "Android SDK Platforms 34",
            "category": "PLATFORM",
            "downloadSize": {
              "value": 63180079,
              "unit": "BYTE"
            },
            "installedSize": {
              "value": 99855424,
              "unit": "BYTE"
            },
            "required": true,
            "hidden": true,
            "extractedPathRename": null,
            "preSelected": false,
            "destination": "{UNITY_PATH}/Editor/Data/PlaybackEngines/AndroidPlayer/SDK/platforms",
            "eula": []
          }
        ]
      }
    ],
    "downloadUrl": "https://download.unity3d.com/download_unity/fb3b7b32f191/TargetSupportInstaller/UnitySetup-Android-Support-for-Editor-2021.3.39f1.exe",
    "visible": true,
    "selected": false,
    "sync": "",
    "parent": "",
    "eulaUrl1": "",
    "eulaLabel1": "",
    "eulaMessage": "",
    "renameTo": "",
    "renameFrom": "",
    "preselected": false
  },
