# Mobile Application Development Assignment

This repository contains my **Mobile Application Development (MAD)** assignment developed using **Android Studio** in **Java**.  
It includes four Android applications covering core concepts such as **UI design, intents, multimedia handling, sensors, SharedPreferences, GridView, camera integration, and activity navigation**.

---

## Applications Included

### **Q1 - Currency Converter App**
A simple Android application that converts values between different currencies.

#### **Features**
- Convert between **INR, USD, JPY, and EUR**
- User-friendly input and dropdown selection
- **Settings page**
- **Dark mode / Light mode toggle**
- Theme preference saved using **SharedPreferences**

#### **Concepts Used**
- `EditText`
- `Spinner`
- `Button`
- `TextView`
- `Intent`
- `SharedPreferences`

---

### **Q2 - Media Player App**
An Android app for playing audio files from the device and streaming video from a URL.

#### **Features**
- Open and play **audio files**
- Enter and play **video using URL**
- Basic media controls:
  - Play
  - Pause
  - Stop
  - Restart

#### **Concepts Used**
- `MediaPlayer`
- `VideoView`
- File picker intent
- Internet permission

---

### **Q3 - Sensor App**
A sensor-based Android application using the **Accelerometer Sensor**.

#### **Features**
- Detects motion of the device
- Displays real-time values of:
  - **X-axis**
  - **Y-axis**
  - **Z-axis**

#### **Concepts Used**
- `SensorManager`
- `Sensor`
- `SensorEventListener`
- Real-time sensor data handling

---

### **Q4 - Photo Gallery and Camera App**
An Android app for selecting and managing images using gallery and camera.

#### **Features**
- Select image from **gallery**
- Capture image using **camera**
- Display images in **GridView**
- View image in **full screen**
- Show **basic image information**
- Delete image using **long press**

#### **Concepts Used**
- `GridView`
- Custom `BaseAdapter`
- `Intent`
- Camera integration
- Multiple activities
- Image URI handling

---

## Tech Stack

- **Language:** Java
- **IDE:** Android Studio
- **Platform:** Android
- **UI Design:** XML

---

## 📂 Project Structure

```text
Q1_CurrencyConverter
Q2_MediaPlayerApp
Q3_SensorApp
Q4_PhotoGalleryApp
