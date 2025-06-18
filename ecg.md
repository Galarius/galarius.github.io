---
layout: default
---

# ECG mob

![intro](./assets/images/ecgmob.png)

[![](./assets/images/app-store.png)](https://apps.apple.com/us/app/id1406511388)

## What is it about?

<div style="text-align: justify;">
The application serves to work together with a mini cardiograph <b>«SERDECHKO»</b> or with devices close in parameters. The system (device and application) is designed for recording, storing and transmitting an electrocardiogram (ECG), which is captured from fingers in everyday life at any time and anywhere and corresponds to the first standard arm-arm channel. 
<br><br>
The ECG signal is transmitted from the device to the smartphone through the headset jack (headphones). The ECG is displayed on the smartphone's display. This allows the patient to monitor the quality of electrode contact and monitor the start and end of the recording. The duration of the ECG record can be set based on the recommendation of a doctor (from 30 seconds to 3 minutes). After registration the ECG remains in the memory of the smartphone and is transferred to the doctor as a PDF file by e-mail if necessary.
</div>

<br>

## Preview

Video guide showing the use of the mini-cardiograph and the application together.

<iframe width="600" height="315" src="https://www.youtube.com/embed/fb_RBO4Gedg" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

> Application design significantly evolved in the latest version.

## Features

The application has the following main features:

* Noise-resistant ECG recording
* Fast heart-rate detection
* Simple UI
* PDF report generation
* Protection from using mini-cardiograph while charging an iPhone
* Mini-cardiograph discharge detector
* User has full control over recordings (the app has no server backend or data collection routines)
* Three available ECG sources:
  * Headset microphone for a wired «Serdechko»
  * BuiltIn microphone for a wireless «Serdechko» with a sound generator
  * Bluetooth microphone for a wireless «Serdechko» with a bluetooth module  
    [*This is an experimental feature and is not available for users in ECG mob 1.3*]

## ECG PDF Report

The app generates a PDF report with recorded ECG signal. It contains the following information:

* Survey's date, time, length and an optional comment about user's general state of health
* User's name, surname, age and optionally SNILS number
* Minimum, maximum and avarage heart-rate values for each pdf page.

User may send this report to his doctor or to himself to print it later.

## Development

The app is developed using `Objective-C` / `C++` and supports devices with *iOS 8* or higher. It contains a powerful signal processing engine which was tested with a lot of hardware. The following cool photo shows a small portable testing environment.

![sim](./assets/images/sim.jpg)

> ECG simulator, a prototype ECG recorder and an iPhone are being used for testing experimental feature allowing wireless ECG recording.

## Links

* [KardioMob](https://ecgmobile.github.io)

* [ECG mob on the App Store](https://apps.apple.com/us/app/id1406511388)

```
```
