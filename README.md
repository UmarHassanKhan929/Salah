# Salah - Prayer Times & Qibla Compass

[![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)](https://flutter.dev)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)
[![Platform](https://img.shields.io/badge/Platform-Android%20%7C%20iOS%20%7C%20Web%20%7C%20Windows%20%7C%20Linux%20%7C%20macOS-lightgrey?style=for-the-badge)](https://flutter.dev/multi-platform)

A beautiful cross-platform Flutter application that provides accurate Islamic prayer times and Qibla direction for Muslims worldwide.

## Features

- **Prayer Times**: Get daily prayer times (Fajr, Sunrise, Dhuhr, Asr, Maghrib, Isha'a) for any city
- **Qibla Compass**: Find the direction of the Kaaba in Mecca for prayer
- **Offline Support**: Caches last searched city data for quick access
- **Cross-Platform**: Works on Android, iOS, Web, Windows, Linux, and macOS
- **Clean UI**: Simple and intuitive interface for daily use

## Screenshots

<div align="center">
  <img src="https://user-images.githubusercontent.com/56496945/177995019-e768d590-6dd7-4328-8459-91ab7a4450c0.png" width="200" alt="Splash Screen"/>
  <img src="https://user-images.githubusercontent.com/56496945/177995029-08633f4d-03ab-454c-8d89-525a6c8ab4c5.jpeg" width="200" alt="Home Screen"/> 
  <img src="https://user-images.githubusercontent.com/56496945/177995038-d26857ab-a10a-499f-8db1-584b8235d1d0.jpeg" width="200" alt="Namaz Times"/>
  <img src="https://user-images.githubusercontent.com/56496945/177995050-9c1077b8-032d-4810-aa7e-4d0adf1e5ae3.jpeg" width="200" alt="Qiblah Compass"/>
</div>

## Getting Started

### Prerequisites

- [Flutter SDK](https://flutter.dev/docs/get-started/install) (>=2.17.3 <3.0.0)
- Dart SDK
- Android Studio / VS Code with Flutter plugins

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/salah.git
   cd salah
   ```

2. Install dependencies:
   ```bash
   flutter pub get
   ```

3. Run the app:
   ```bash
   flutter run
   ```

## Built With

- [Flutter](https://flutter.dev) - UI framework
- [flutter_qiblah](https://github.com/medyas/flutter_qiblah) - Qibla direction detection
- [Daily Prayer Time API](https://github.com/abdulrcs/Daily-Prayer-Time-API) - Prayer times data
- [http](https://pub.dev/packages/http) - API requests
- [shared_preferences](https://pub.dev/packages/shared_preferences) - Local storage
- [flutter_compass](https://pub.dev/packages/flutter_compass) - Device compass
- [sensors_plus](https://pub.dev/packages/sensors_plus) - Device sensors

## Contributing

Contributions are welcome! Please read our [Contributing Guidelines](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md) before getting started.

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- Prayer times data provided by [Daily Prayer Time API](https://github.com/abdulrcs/Daily-Prayer-Time-API)
- Qibla functionality powered by [flutter_qiblah](https://github.com/medyas/flutter_qiblah)
- Compass graphics and icons

## Contact

If you have any questions or suggestions, feel free to open an issue or reach out!

---

<div align="center">
  Made with ❤️ for the Muslim community
</div>
