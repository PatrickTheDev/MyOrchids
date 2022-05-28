<h1 align="center">My Orchids</h1>
<p align="center">
    <img alt="MyOrchids" src="myorchids_logo.jpg"/>
    <br>
    <!-- This and other base64 flags are available at https://www.phoca.cz/cssflags/ -->
    <a href="https://github.com/PatrickTheDev/MyOrchids/blob/main/.github/README_de.md">
        <img height="20px" src="https://img.shields.io/badge/DE-flag.svg?color=555555&style=flat&logo=data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMTAwMCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIiBoZWlnaHQ9IjYwMCIgdmlld0JveD0iMCAwIDUgMyI+DQo8cGF0aCBkPSJtMCwwaDV2M2gtNXoiLz4NCjxwYXRoIGZpbGw9IiNkMDAiIGQ9Im0wLDFoNXYyaC01eiIvPg0KPHBhdGggZmlsbD0iI2ZmY2UwMCIgZD0ibTAsMmg1djFoLTV6Ii8+DQo8L3N2Zz4NCg==">
    </a>
</p>

<p align="center">
    <!-- This and other shields are available at https://shields.io/ -->
    <img src="https://img.shields.io/badge/OS-Android-green?style=flat&logo=android"/>
    <img src="https://img.shields.io/badge/API-21%2B-brightgreen.svg?style=flat"/>
    <a href="https://matrix.to/#/@patrickthedev:matrix.org">
        <img src="https://img.shields.io/badge/Chat%20on-matrix-03b381">
    </a>
</p>

<p align="center">
Eine Android App mit der man Informationen und Bilder von Orchideen sammeln,
das Wachstum deiner Orchideen protokollieren und die Pflege durch Dinge wie
Erinnerungen vereinfachen kann.
</p>

## Inhaltsverzeichnis
<!--ts-->
* [Hintergrund](#-hintergrund)
* [Momentane Funktionen](#-momentane-funktionen)
* [Roadmap](#-roadmap)
* [Verwendete Tools und Technologien](#-verwendete-tools-und-technologien)
* [Du hast eine Frage? Du möchtest mir schreiben?](#-du-hast-eine-frage-du-mchtest-mir-schreiben)
<!--te-->

## 📜 Hintergrund
<p>
I started this project to have a possibility to practice and implement new things I learn in android development. <br>
One of my hobbies is keeping and collecting orchids and that also was part of my inspiration to develop this app. <br>
I still work on this project whenever I have time and hope that I can release a full first version soon.
</p>

## 🎯 Momentane Funktionen
- Einen Datensatz zu einer Orchidee anlegen oder bearbeiten
- Bilder zu einem Datensatz einer Orchidee hinzufügen oder entfernen
- Eine Orchidee zu einer Sammlung eigener Orchideen hinzufügen

## 🛣 Roadmap
- MyOrchidsViewPager implementieren, inspiriert durch [MaterialViewPager](https://github.com/florent37/MaterialViewPager)
- Das Schreiben von Notizen zu Orchideen ermöglichen📝
- Das Feature implementieren, durch die App an Dinge wie Gießen erinnert werden zu können 💦
- Wetterdaten API, see [OrchidWeather](https://github.com/PatrickTheDev/OrchidWeather) 🌦
- Push-Benachrichtigungen mit Warnungen über Außentemperaturen, die deinen Orchideen schaden könnten 🥶⚠️
- Die UI aufwerten 💅✨

## 🧰 Verwendete Tools und Technologien
- [**Architektur**][0] - Eine Sammlunge an Bibliotheken die dir dabei helfen robuste, testbare und wartbare Apps zu schreiben.
    - [Data Binding][1] - This support library allows you to bind your layouts' UI components to data sources in your app without the need for any Java/Kotlin code.
    - [Lifecycles][2] - Create a UI with components that automatically respond to lifecycle events such as creation of a fragment.
    - [LiveData][3] - An observable and lifecycle-aware data holder class.
    - [Navigation][4] - In-app navigation made easy. Also complex navigation information can be put in a central and visualized place with the Navigation graph.
    - [Room][5] - Abstraction layer over SQLite also providing benefits like compile-time verification of SQL queries.
    - [ViewModel][6] - Store and manage UI-related data in a lifecycle conscious way. It also allows data to survive configuration changes and easy scheduling of asynchronous tasks.
    - [WorkManager][7] - Handling persistent work across all Android API versions with a single uniform API.
- **Miscellaneous and third party libraries**
    - [Coil][8] for image loading backed by Kotlin Coroutines.
    - [Dagger][9] and [Hilt][10] for [DI][11].
    - [Kotlin Coroutines][12] and [Flow][13] for managing asynchronous programming and stream processing.

<!--
## ℹ️ Getting help
Check the [user manual]() or the wiki for usage instructions. 
See the [help page]() for how to submit a bug report.
-->

## 📬 Du hast eine Frage? Du möchtest mir schreiben?
<p>Schreib mir eine <a href="mailto:patrickpaul@posteo.de">mail</a> 📧</p>
<p>-oder-</p>
<p>schreib mir auf <a href="https://matrix.to/#/@patrickthedev:matrix.org">matrix</a> 💬. :)</p>


[0]: https://developer.android.com/topic/architecture
[1]: https://developer.android.com/topic/libraries/data-binding/
[2]: https://developer.android.com/topic/libraries/architecture/lifecycle
[3]: https://developer.android.com/topic/libraries/architecture/livedata
[4]: https://developer.android.com/guide/navigation
[5]: https://developer.android.com/training/data-storage/room
[6]: https://developer.android.com/topic/libraries/architecture/viewmodel
[7]: https://developer.android.com/topic/libraries/architecture/workmanager
[8]: https://github.com/coil-kt/coil
[9]: https://dagger.dev/dev-guide/
[10]: https://dagger.dev/hilt/
[11]: https://developer.android.com/training/dependency-injection
[12]: https://kotlinlang.org/docs/coroutines-overview.html
[13]: https://kotlinlang.org/docs/flow.html
