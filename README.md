# Tiny-OpenCV

A tiny version of [OpenCV](https://opencv.org). AAR size: ~26 MB

- tiny version of OpenCV **4.4.0**:
	- armeabi-v7a: **3.1 MB** (original: 10.1 MB)
	- arm64-v8a: **5.6 MB** (original: 18.8 MB)
	- x86: **16.7 MB** (original: 38.6 MB)
	- x86_64: **25.1 MB** (original: 53.7 MB)

## Installation

In your app gradle:

    dependencies {
        ...
        implementation 'com.github.zynkware:Tiny-OpenCV:4.4.0-4'
    }

In your root gradle: 

	allprojects {
	    repositories {
		...
		maven { url "https://jitpack.io" }
	    }
	}
