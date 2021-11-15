# VDS-NC Checker Library

[![Release](https://jitpack.io/v/jitpack/android-example.svg)](https://URL) TODO: Replace with the real Jitpack URL

To better inform your usage of this library, please see [here](https://www.passports.gov.au/vds-nc-checker) for the business case for the original VDS-NC Checker.

This library is intended for use by entities and organisations that need to validate [Visible Digital Seals](https://www.icao.int/Security/FAL/TRIP/PublishingImages/Pages/Publications/Visible%20Digital%20Seal%20for%20non-constrained%20environments%20%28VDS-NC%29.pdf), typically employed in passports and other identifying/travel documentation.

## Installation

You may add the library via your build.gradle file; firstly add [Jitpack](https://jitpack.io/) to your repository list:
```gradle
allprojects {
    repositories {
        maven { url "https://jitpack.io" }
    }
}
```
and then add the dependency:

```gradle
dependencies {
    implementation 'au.gov.dfat.lib.vdsncchecker:{ReleaseNumber}'
}
```

Alternatively, you may download the source code directly from this repository and modify it to fit your purpose, as per the [MIT License](https://opensource.org/licenses/MIT)
