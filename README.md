# cryptoApp

## 📌 Overview
CryptoApp is a modern Android application built using **Kotlin** that provides real-time cryptocurrency data. The app leverages **MVVM architecture**, **Retrofit**, and **Coroutines** to fetch and display crypto market details in a user-friendly UI.

## 🚀 Features
- Fetches real-time cryptocurrency prices
- Displays coin details with interactive UI
- Uses **Retrofit** for API requests
- Implements **MVVM architecture** for better separation of concerns
- Uses **Kotlin Coroutines** for asynchronous operations
- **LiveData** integration for UI updates
- Simple and responsive UI using **Jetpack Components**

## 🛠️ Technologies Used
- **Kotlin** - Programming language
- **Retrofit** - API communication
- **MVVM Architecture** - Separation of concerns
- **Kotlin Coroutines** - Asynchronous programming
- **LiveData & ViewModel** - Lifecycle-aware UI components
- **Material Design** - Modern UI elements

## 📂 Project Structure
```
CryptoApp/
│── app/
│   ├── data/
│   │   ├── api/
│   │   │   ├── ApiService.kt
│   │   ├── model/
│   │   │   ├── Crypto.kt
│   │   ├── repository/
│   │   │   ├── CryptoRepository.kt
│   ├── ui/
│   │   ├── view/
│   │   │   ├── MainActivity.kt
│   │   ├── viewmodel/
│   │   │   ├── CryptoViewModel.kt
│   ├── utils/
│── build.gradle
│── AndroidManifest.xml
```

## 📥 Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/khurrammushtaq55/cryptoApp.git
   ```
2. Open the project in **Android Studio**.
3. Build and run the project on an emulator or a physical device.

## 📖 Usage
1. **View real-time crypto prices** fetched from the API.
2. **Tap on a coin** to view detailed information.
3. **Pull to refresh** to get the latest prices.

## 💡 Best Practices Implemented
- **MVVM architecture** ensures clean code structure.
- **Dependency injection** for easy maintainability.
- **Lifecycle-aware components** prevent memory leaks.
- **Error handling** for API requests.

## 📜 License
This project is licensed under the **MIT License**. Feel free to use and modify it.

## 🤝 Contributing
Contributions are welcome! Feel free to **fork** this repository and submit a **pull request**.

## 📧 Contact
- **LinkedIn:** [linkedin.com/in/khurram27](https://www.linkedin.com/in/khurram27/)
- **GitHub:** [github.com/khurrammushtaq55](https://github.com/khurrammushtaq55)
- **Email:** khurram.dlx@gmail.com

