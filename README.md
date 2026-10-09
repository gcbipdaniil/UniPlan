# 🎓 UniPlan — Student Planner & USOS Client for UKEN Krakow

<p align="center">
  <img src="app/src/main/res/mipmap-xxhdpi/ic_launcher.png" width="128" height="128" alt="UniPlan Logo" />
</p>

<p align="center">
  <b>Modern Android Timetable Planner & Integrated USOS Portal for UKEN Krakow Students</b>
</p>

<p align="center">
  <a href="#-english">English</a> •
  <a href="#-polski">Polski</a> •
  <a href="#-русский">Русский</a>
</p>

---

## 🇬🇧 English

### About UniPlan
**UniPlan** is a modern, native Android application designed specifically for students of **Uniwersytet Komisji Edukacji Narodowej w Krakowie (UKEN Krakow)**. It combines an intuitive class timetable planner with an integrated **USOSweb** portal client, smart reminders, and news feeds into a clean Material Design 3 interface.

### Key Features
- 📅 **Interactive Class Calendar**: 7x6 month grid, daily schedule sheet, and list view with progress tracking.
- ⚡ **"Now Card" Status**: Real-time countdown timer to your ongoing class or upcoming lecture.
- 🔐 **Native USOS Portal**:
  - CAS SSO Authentication (`cas.uken.krakow.pl`).
  - Native Grades & Subjects viewer organized by academic semesters.
  - Live USOS News feed with rich text formatting, warning alerts (`UWAGA!`), and clickable links.
  - Interactive Fullscreen Image Viewer with multi-touch pinch-to-zoom gestures.
  - Embedded authenticated USOS Web View (`home/index`).
- ⏰ **Smart Class Reminders**: Exact Alarm notifications before class starts (automatically silenced during active lectures).
- 🌐 **Timezone Support**: Automatic detection, preset chips for major cities, and searchable timezone picker.
- 🎨 **Material 3 / Material You**: Dynamic color themes (Android 12+), dark/light mode support, and spring motion animations.
- 🌍 **Multi-language**: Full localization in English, Polish, Russian, Belarusian, and Ukrainian.

### Tech Stack
- **Language**: Kotlin 100%
- **UI Framework**: Jetpack Compose + Material Design 3
- **Asynchronous**: Kotlin Coroutines & StateFlow
- **Database**: Room (SQLite local caching)
- **Networking**: OkHttp 4 + Custom CookieJar for CAS SSO
- **Parsing**: JSoup & Regex HTML parser
- **Background Work**: WorkManager & AlarmManager
- **Security**: EncryptedSharedPreferences / Android Keystore

### Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/gcbipdaniil/UniPlan.git
   ```
2. Open the project in **Android Studio 2024.1+**.
3. Build and run on an Android device or emulator (Android 8.0 / API 26+).

### Author
- **Developer**: Dudarchuk Daniil (**DanStudio**)
- **GitHub**: [github.com/gcbipdaniil/UniPlan](https://github.com/gcbipdaniil/UniPlan)

---

## 🇵🇱 Polski

### O aplikacji UniPlan
**UniPlan** to nowoczesna, natywna aplikacja na system Android stworzona z myślą o studentach **Uniwersytetu Komisji Edukacji Narodowej w Krakowie (UKEN Kraków)**. Łączy w sobie przejrzysty planer planu zajęć z zintegrowanym klientem systemu **USOSweb**, inteligentnymi przypomnieniami oraz wiadomościami uczelnianymi.

### Główny Funkcje
- 📅 **Interaktywny Plan Zajęć**: Miesięczna siatka 7x6, podgląd dzienny oraz widok listy z postępem zajęć.
- ⚡ **Karta "Teraz"**: Licznik czasu w czasie rzeczywistym wskazujący czas do końca trwających zajęć lub do rozpoczęcia kolejnego wykładu.
- 🔐 **Zintegrowany Portal USOS**:
  - Autoryzacja przez Centralny System Uwierzytelniania CAS (`cas.uken.krakow.pl`).
  - Natywny podgląd ocen i przedmiotów z podziałem na semestry akademickie.
  - Aktualności USOS z sformatowanym tekstem, wyróżnionymi komunikatami (`UWAGA!`) i aktywnymi linkami.
  - Pełnoekranowa przeglądarka zdjęć z obsługą gestów przybliżania (pinch-to-zoom).
  - Wbudowany, zalogowany widok strony USOS (`home/index`).
- ⏰ **Inteligentne Przypomnienia**: Dokładne powiadomienia budzika przed zajęciami (automatycznie wyciszane podczas trwania innych zajęć).
- 🌐 **Obsługa Stref Czasowych**: Automatyczne wykrywanie, szybkie przyciski miast oraz wyszukiwarka stref.
- 🎨 **Material Design 3**: Dynamiczne kolory (Android 12+), tryb jasny i ciemny.
- 🌍 **Wielojęzyczność**: Pełne tłumaczenie na język polski, angielski, rosyjski, białoruski i ukraiński.

### Autor
- **Deweloper**: Daniil Dudarchuk (**DanStudio**)
- **GitHub**: [github.com/gcbipdaniil/UniPlan](https://github.com/gcbipdaniil/UniPlan)

---

## 🇷🇺 Русский

### О приложении UniPlan
**UniPlan** — это современное нативное Android-приложение для студентов **Uniwersytet Komisji Edukacji Narodowej w Krakowie (UKEN Краков)**. Приложение объединяет планировщик учебного расписания, встроенный клиент портала **USOSweb**, систему умных напоминаний и ленту новостей университета.

### Основные возможности
- 📅 **Интерактивный календарь расписания**: Сетка месяца 7x6, просмотр занятий на день и списочное представление.
- ⚡ **Карточка статуса «Сейчас»**: Таймер обратного отсчета до конца текущей пары или до начала следующей лекции.
- 🔐 **Встроенный модуль USOS**:
  - Единая авторизация через CAS SSO (`cas.uken.krakow.pl`).
  - Просмотр предметов и оценок, распределенных по академическим семестрам.
  - Лента новостей USOS с форматированием, карточками предупреждений (`UWAGA!`) и кликабельными ссылками.
  - Полноэкранный просмотрщик изображений из новостей с приближением пальцами (pinch-to-zoom).
  - Встроенная авторизованная веб-версия USOS (`home/index`).
- ⏰ **Умные напоминания о парах**: Точные уведомления будильника перед началом пары (автоматически отключаются во время других пар).
- 🌐 **Управление часовыми поясами**: Автоматическое определение, популярные города в один клик и удобный поиск.
- 🎨 **Material Design 3**: Динамические цвета (Android 12+), поддержка темной и светлой темы.
- 🌍 **Локализация**: Полный перевод на русский, польский, английский, белорусский и украинский языки.

### Разработчик
- **Автор**: Дударчук Даниил (**DanStudio**)
- **GitHub**: [github.com/gcbipdaniil/UniPlan](https://github.com/gcbipdaniil/UniPlan)

---

<p align="center">
  Copyright © 2026 DanStudio. All rights reserved.
</p>
