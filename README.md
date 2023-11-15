# FastInvoiceReader

A Flutter application that allows you to quickly read the invoices at hand, get the necessary information and then output it as an .xls file.

## Installation

1. Create a new Flutter project:
```
flutter create weather_app
```

2. Clone the repository:
```
git clone https://github.com/OverBrave/WeatherApp.git
```

3. Test your changes by running the app on an emulator or a physical device:
```
flutter run
```

## Packages

- [hive](https://pub.dev/packages/hive) - To save for the user’s invoices data in device’s storage.
- [syncfusion_flutter_xlsio](https://pub.dev/packages/syncfusion_flutter_xlsio) - To export invoices data with image to .xls file.
- [google_mlkit_text_recognition](https://pub.dev/packages/google_mlkit_text_recognition) - To read texts in image.
- opencv - It reads the corners of the invoice and ensures that it is trimmed.