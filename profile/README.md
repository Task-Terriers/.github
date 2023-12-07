# TaskTerriers 🐕‍🦺

Have you ever needed a tutor for a specific class but weren't able to find one easily? Do you wish that you were able to take a breather and get some help?

Finally presenting Task Terriers, an app which provides BU students with a platform to offer services to other students to make extra income and to seek services.

## Tech Stack

<img src="https://img.shields.io/badge/reactnative-61DAFB?style=for-the-badge&logo=react&logoColor=white"> <img src="https://img.shields.io/badge/C%23-512BD4?style=for-the-badge&logo=c%23&logoColor=white"> <img src="https://img.shields.io/badge/NancyFX-000000?style=for-the-badge&logoColor=white"> <img src="https://img.shields.io/badge/typescript-3178C6?style=for-the-badge&logo=typescript&logoColor=white"> <img src="https://img.shields.io/badge/.NET-512BD4?style=for-the-badge&logo=dotNet&logoColor=white"> <img src="https://img.shields.io/badge/prettier-F7B93E?style=for-the-badge&logo=prettier&logoColor=black">
<img src="https://img.shields.io/badge/firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black">

## Installation

### Frontend
  - Clone the ```App``` repository
  - Install expo if needed

  #### Prerequisites
    
  ##### EAS build
  - Follow the steps : https://docs.expo.dev/eas-update/getting-started/
  ##### Download Android Studio
  - Install virtual device

  #### Running the App
  1. ```yarn```
  2.  ```yarn expo start```
  3.   switch to development mode by pressing ```s```
  4.   run the emulator by pressing ```a```

  ❗ If you don't see the app running on the emulator: <br>
    press ```r``` to reload
  
  ---

### Backend
  - Clone the ```Backend``` repository
  - Navigate to ```NancyFX``` folder

#### Prerequisites
  - Install [.NET 8.0](https://dotnet.microsoft.com/download)

#### Run
  1. Install NancyFX (NuGet package) ```dotnet add package Nancy --version 2.0.0```
  2. Open `program.cs`.
  3. Add Firebase Base Key and Secret Auth in lines 22-23. (provided upon request)
  4. Setup the correct IpAddress: <br>
       - Add your IP address in line 44 (and 47 for the console logs)
       - ❗ `localhost` will not work with the Android Simulator, keep `1234` as the port.
  6. Run the server: <br>
       ```dotnet run```


## Team Members
- 2023 Fall CS392 Final Project

|Youngjin Shin|Aleksander Sekulovski|Anabelle Brodsky|Alim Cemal Kura|Olivia Provonsil|
|---|---|---|---|---|
|[**@yjshin229**](https://github.com/yjshin229)|[**@aleks-s10**](https://github.com/aleks-s10)|[**@anabellebr22**](https://github.com/anabellebr22)|[**@smokethecookie**](https://github.com/smokethecookie)|[**@oliviaprovonsil**](https://github.com/oliviaprovonsil)|


