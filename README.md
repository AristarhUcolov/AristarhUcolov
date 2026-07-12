<!-- Language Navigation -->
<p align="center">
  <a href="#ru-section"><img src="https://img.shields.io/badge/🇷🇺-Русский-1f6feb?style=for-the-badge" alt="Русский"></a>
  <a href="#en-section"><img src="https://img.shields.io/badge/🇬🇧-English-6e40c9?style=for-the-badge" alt="English"></a>
</p>

<div align="center">

# Аристарх Уколов · Aristarh Ucolov

**Digital Security · Digital Forensics · OSINT · Law & Technology**

Основатель инициативы гражданской кибербезопасности **[C.N.S — Clear Net Sky](https://clearnetsky.github.io/C.N.S-Clear.Net.Sky-S.O.W.A/)**
<br>
Founder of the civilian cybersecurity initiative **[C.N.S — Clear Net Sky](https://clearnetsky.github.io/C.N.S-Clear.Net.Sky-S.O.W.A/languages/english.html)**

<p>
  <a href="https://www.linkedin.com/in/aristarhucolov"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://youtube.com/@Aristarh.Ucolov"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"></a>
  <a href="mailto:ucolov.artur@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/ClearNetSky"><img src="https://img.shields.io/badge/Clear%20Net%20Sky-181717?style=for-the-badge&logo=github&logoColor=white" alt="Clear Net Sky"></a>
</p>

</div>

---

<h1 id="ru-section">🇷🇺 Русский</h1>

## О себе

Исследователь в области **гражданской кибербезопасности**. Развиваю инициативу **[C.N.S — Clear Net Sky](https://github.com/ClearNetSky)** — открытые проекты, которые защищают обычных пользователей в интернете: от DNS-фильтрации и безопасности браузера до инструментов цифровой криминалистики.

Готовлюсь к поступлению на **юридический факультет**: моя цель — работать на стыке **права и технологий** — киберправо, цифровые доказательства и расследование киберпреступлений.

## Направления

| Область | Что делаю |
|---|---|
| 🛡️ **Цифровая безопасность** | DNS-фильтрация (DoH / DoT / DNSCrypt), безопасность браузера, защита от нежелательного контента |
| 🔬 **Цифровая криминалистика** | Песочницы для анализа поведения ПО, снимки файловой системы и реестра, индикаторы компрометации (IOC), отчёты STIX 2.1 / MISP |
| 🔎 **OSINT** | Разведка по открытым источникам, мониторинг сетевой активности и публичных данных |
| ⚖️ **Право и технологии** | Киберправо, цифровые доказательства, правовые аспекты информационной безопасности |

## Ключевые проекты

### Криминалистика и безопасность

| Проект | Описание | Стек |
|---|---|---|
| **[Virtual Software Machine (VSM)](https://github.com/ClearNetSky/Virtual-Software-Machine)** | User-mode песочница для цифровой криминалистики и OSINT: изолированный запуск (Job Object, Low Integrity), снимки ФС и реестра «до/после», мониторинг сети, DNS и процессов, эвристический вердикт и отчёты HTML / JSON / STIX 2.1 | Go |
| **[S.O.W.A Security Software](https://github.com/ClearNetSky/CNS-SOWA-SECURITY)** | Сетевой DNS-сервер с фильтрацией: DoH / DoT / DNSCrypt, принудительный Safe Search, родительский контроль, DHCP, журнал запросов с WHOIS и веб-панель управления | Go |
| **[S.O.W.A DNS Blacklist](https://github.com/ClearNetSky/CNS-SOWA-DNS-BLACKLIST-FILTERING)** | Блокировочные списки для DNS-фильтров: 29+ категорий опасных и нежелательных ресурсов ([ранняя версия](https://github.com/ClearNetSky/Safe-World-DNS-BlackList-Of-Danger-WebSites-by-C.N.S-Clear.Net.Sky)) | Data |
| **[Operation Mirror Cloud](https://github.com/ClearNetSky/Anti-Terrorist-Project-Operation-Mirror-Cloud)** | Открытый информационный OSINT-проект в сфере общественной безопасности ([сайт](https://clearnetsky.github.io/Anti-Terrorist-Project-Operation-Mirror-Cloud/)) | JavaScript |

<details>
<summary>📸 <b>Скриншоты</b></summary>
<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/ac9a2943-3376-4ce4-91c1-39e0c64837b1" width="800" alt="C.N.S — Clear Net Sky (S.O.W.A)">
  <br><sub>Сайт инициативы C.N.S — Clear Net Sky (S.O.W.A)</sub>
</p>
<p align="center">
  <img src="https://github.com/ClearNetSky/C.N.S-Clear.Net.Sky-S.O.W.A/assets/56760026/e5ac6a77-1851-4e4e-93eb-02869adca27d" width="800" alt="S.O.W.A DNS Blacklist">
  <br><sub>S.O.W.A DNS Blacklist — категории блокировочных списков</sub>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/4c071e6e-c6a5-439a-862b-518eef0f9254" width="800" alt="Operation Mirror Cloud">
  <br><sub>Operation Mirror Cloud — открытый OSINT-проект</sub>
</p>
</details>

### Безопасность браузера

| Проект | Описание | Стек |
|---|---|---|
| **[NSFW Filter](https://github.com/ClearNetSky/NSFW-Filter)** | AI-блокировка NSFW-контента в реальном времени: TensorFlow.js + NSFWJS, WebGPU-ускорение, 5-классовая классификация — [опубликовано в Chrome Web Store](https://chromewebstore.google.com/detail/nsfw-filter/nojnjhlhdhfaghkgdgdcobjnoeghkopg) | JavaScript |
| **[Global Content Guard](https://github.com/ClearNetSky/Global-Content-Guard)** | Расширение Chrome: фильтрация текста, изображений и блоков по ключевым словам на любых сайтах, интерфейс RU/EN, whitelist | JavaScript |
| **[Secure Profile Lock](https://github.com/ClearNetSky/Browser-Profiles-Authentication-Secure-Profile-Lock)** | Парольная защита профилей Chrome для общих компьютеров | JavaScript |
| **[Eye Vision Protector](https://github.com/ClearNetSky/Eye-Vision-Protector---Better-Vision-Save-Your-Vision)** | Защита зрения при длительной работе и помощь слабовидящим пользователям | JavaScript |

<details>
<summary>📸 <b>Скриншоты</b></summary>
<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/29df3dff-ed52-47fa-899d-ccd0bbcbb878" width="500" alt="Global Content Guard">
  <br><sub>Global Content Guard — интерфейс расширения</sub>
</p>
</details>

### Инструменты и автоматизация

| Проект | Описание | Стек |
|---|---|---|
| **[DayZ Server Manager](https://github.com/AristarhUcolov/DayZ-Server-Manager)** | Веб-панель управления выделенным сервером DayZ в одном .exe: моды из Steam Workshop, редакторы конфигов, авто-рестарт | Go |
| **[TV Remote Control](https://github.com/AristarhUcolov/TV-Remote-Control)** | Универсальный пульт Android TV для Windows — один .exe, без установки | Go · Wails · Svelte |
| **[QuickShare](https://github.com/ClearNetSky/QuickShare)** | Быстрая передача файлов по локальной сети с drag & drop, без настройки | JavaScript |
| **[Humanity Language Tool](https://github.com/AristarhUcolov/Humanity-Language-Tool-Synonymizer)** | Мультиязычный синонимайзер (EN/RU/MO): 15 000+ синонимов, полное сохранение форматирования DOCX, офлайн | Go |

<details>
<summary>📸 <b>Скриншоты</b></summary>
<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/bae4cc20-936a-47e8-8251-2e8948987e87" width="800" alt="DayZ Server Manager">
  <br><sub>DayZ Server Manager — веб-панель управления сервером</sub>
</p>
</details>

<details>
<summary><b>Архив: ранние работы</b></summary>
<br>

| Проект | Описание |
|---|---|
| **[Horse System for SA:MP](https://github.com/AristarhUcolov/Horse-System-for-SA-MP-Servers)** | Скрипт на Pawn, позволяющий управлять объектом лошади как транспортным средством — использовался многими серверами GTA SA:MP |
| **[Smit Role Play](https://github.com/AristarhUcolov/Smit-Role-Play-SAMP-0.3.7)** | Игровой режим Role Play для GTA SA:MP |
| **[YouTube Downloader](https://github.com/AristarhUcolov/YouTube-Downloader)** | Загрузчик видео и плейлистов (MP3/MP4) с графическим интерфейсом на Python |

<p align="center">
  <img src="https://github.com/AristarhUcolov/Horse-System-for-SA-MP-Servers-SA-MP-/assets/56760026/89276dc0-f0dc-4652-8a27-9cb6e3f0c6ac" width="500" alt="Horse System for SA:MP">
  <br><sub>Horse System for SA:MP</sub>
</p>

</details>

## Технологии

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white" alt="Svelte">
  <img src="https://img.shields.io/badge/TensorFlow.js-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow.js">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
</p>

**Специализация:** внутренности Windows (Job Objects, реестр, токены безопасности) · расширения Chrome (Manifest V3) · DNS-инфраструктура (DoH / DoT / DNSCrypt) · форматы Threat Intelligence (STIX 2.1, MISP)

## Связь

Открыт к сотрудничеству в области цифровой безопасности, криминалистики и OSINT.

<p>
  <a href="https://www.linkedin.com/in/aristarhucolov"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://youtube.com/@Aristarh.Ucolov"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"></a>
  <a href="mailto:ucolov.artur@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

<h1 id="en-section">🇬🇧 English</h1>

## About Me

Researcher in the field of **civilian cybersecurity**. I run the **[C.N.S — Clear Net Sky](https://github.com/ClearNetSky)** initiative — open projects that protect everyday users on the internet: from DNS filtering and browser security to digital forensics tooling.

I am preparing to enter **law school**: my goal is to work at the intersection of **law and technology** — cyber law, digital evidence, and cybercrime investigation.

## Focus Areas

| Area | What I do |
|---|---|
| 🛡️ **Digital Security** | DNS filtering (DoH / DoT / DNSCrypt), browser security, protection against harmful content |
| 🔬 **Digital Forensics** | Software behavior analysis sandboxes, file system & registry snapshots, indicators of compromise (IOC), STIX 2.1 / MISP reporting |
| 🔎 **OSINT** | Open-source intelligence, monitoring of network activity and public data |
| ⚖️ **Law & Technology** | Cyber law, digital evidence, legal aspects of information security |

## Featured Projects

### Forensics & Security

| Project | Description | Stack |
|---|---|---|
| **[Virtual Software Machine (VSM)](https://github.com/ClearNetSky/Virtual-Software-Machine)** | User-mode sandbox for digital forensics & OSINT: isolated execution (Job Object, Low Integrity), before/after file system & registry snapshots, network / DNS / process monitoring, heuristic verdict and HTML / JSON / STIX 2.1 reports | Go |
| **[S.O.W.A Security Software](https://github.com/ClearNetSky/CNS-SOWA-SECURITY)** | Network DNS server with filtering: DoH / DoT / DNSCrypt, enforced Safe Search, parental controls, DHCP, query log with WHOIS, and a web control panel | Go |
| **[S.O.W.A DNS Blacklist](https://github.com/ClearNetSky/CNS-SOWA-DNS-BLACKLIST-FILTERING)** | Blocklists for DNS filters: 29+ categories of dangerous and unwanted resources ([earlier version](https://github.com/ClearNetSky/Safe-World-DNS-BlackList-Of-Danger-WebSites-by-C.N.S-Clear.Net.Sky)) | Data |
| **[Operation Mirror Cloud](https://github.com/ClearNetSky/Anti-Terrorist-Project-Operation-Mirror-Cloud)** | Open OSINT information project in the field of public safety ([website](https://clearnetsky.github.io/Anti-Terrorist-Project-Operation-Mirror-Cloud/)) | JavaScript |

<details>
<summary>📸 <b>Screenshots</b></summary>
<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/efc2ccbc-b314-49e8-9a29-8cc588d6775f" width="800" alt="C.N.S — Clear Net Sky (S.O.W.A)">
  <br><sub>C.N.S — Clear Net Sky (S.O.W.A) initiative website</sub>
</p>
<p align="center">
  <img src="https://github.com/ClearNetSky/C.N.S-Clear.Net.Sky-S.O.W.A/assets/56760026/e5ac6a77-1851-4e4e-93eb-02869adca27d" width="800" alt="S.O.W.A DNS Blacklist">
  <br><sub>S.O.W.A DNS Blacklist — blocklist categories</sub>
</p>
<p align="center">
  <img src="https://github.com/user-attachments/assets/4c071e6e-c6a5-439a-862b-518eef0f9254" width="800" alt="Operation Mirror Cloud">
  <br><sub>Operation Mirror Cloud — open OSINT project</sub>
</p>
</details>

### Browser Security

| Project | Description | Stack |
|---|---|---|
| **[NSFW Filter](https://github.com/ClearNetSky/NSFW-Filter)** | Real-time AI-powered NSFW content blocking: TensorFlow.js + NSFWJS, WebGPU acceleration, 5-class classification — [published on the Chrome Web Store](https://chromewebstore.google.com/detail/nsfw-filter/nojnjhlhdhfaghkgdgdcobjnoeghkopg) | JavaScript |
| **[Global Content Guard](https://github.com/ClearNetSky/Global-Content-Guard)** | Chrome extension: keyword-based filtering of text, images, and blocks on any website, RU/EN interface, whitelist support | JavaScript |
| **[Secure Profile Lock](https://github.com/ClearNetSky/Browser-Profiles-Authentication-Secure-Profile-Lock)** | Password protection for Chrome profiles on shared computers | JavaScript |
| **[Eye Vision Protector](https://github.com/ClearNetSky/Eye-Vision-Protector---Better-Vision-Save-Your-Vision)** | Eye protection during prolonged computer use and assistance for visually impaired users | JavaScript |

<details>
<summary>📸 <b>Screenshots</b></summary>
<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/29df3dff-ed52-47fa-899d-ccd0bbcbb878" width="500" alt="Global Content Guard">
  <br><sub>Global Content Guard — extension interface</sub>
</p>
</details>

### Tools & Automation

| Project | Description | Stack |
|---|---|---|
| **[DayZ Server Manager](https://github.com/AristarhUcolov/DayZ-Server-Manager)** | Single-exe web panel for a DayZ dedicated server: Steam Workshop mods, config editors, auto-restart | Go |
| **[TV Remote Control](https://github.com/AristarhUcolov/TV-Remote-Control)** | Universal Android TV remote for Windows — single .exe, no install | Go · Wails · Svelte |
| **[QuickShare](https://github.com/ClearNetSky/QuickShare)** | Fast LAN file transfer with drag & drop, no setup required | JavaScript |
| **[Humanity Language Tool](https://github.com/AristarhUcolov/Humanity-Language-Tool-Synonymizer)** | Multi-language synonymizer (EN/RU/MO): 15,000+ synonyms, full DOCX formatting preservation, 100% offline | Go |

<details>
<summary>📸 <b>Screenshots</b></summary>
<br>
<p align="center">
  <img src="https://github.com/user-attachments/assets/bae4cc20-936a-47e8-8251-2e8948987e87" width="800" alt="DayZ Server Manager">
  <br><sub>DayZ Server Manager — web control panel</sub>
</p>
</details>

<details>
<summary><b>Archive: early work</b></summary>
<br>

| Project | Description |
|---|---|
| **[Horse System for SA:MP](https://github.com/AristarhUcolov/Horse-System-for-SA-MP-Servers)** | Pawn script that lets players control a horse object as a vehicle — used by many GTA SA:MP servers |
| **[Smit Role Play](https://github.com/AristarhUcolov/Smit-Role-Play-SAMP-0.3.7)** | Role Play game mode for GTA SA:MP |
| **[YouTube Downloader](https://github.com/AristarhUcolov/YouTube-Downloader)** | Video and playlist downloader (MP3/MP4) with a Python GUI |

<p align="center">
  <img src="https://github.com/AristarhUcolov/Horse-System-for-SA-MP-Servers-SA-MP-/assets/56760026/89276dc0-f0dc-4652-8a27-9cb6e3f0c6ac" width="500" alt="Horse System for SA:MP">
  <br><sub>Horse System for SA:MP</sub>
</p>

</details>

## Technologies

<p>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white" alt="Go">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Svelte-FF3E00?style=for-the-badge&logo=svelte&logoColor=white" alt="Svelte">
  <img src="https://img.shields.io/badge/TensorFlow.js-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow.js">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
</p>

**Specialization:** Windows internals (Job Objects, registry, security tokens) · Chrome extensions (Manifest V3) · DNS infrastructure (DoH / DoT / DNSCrypt) · Threat Intelligence formats (STIX 2.1, MISP)

## Contact

Open to collaboration in digital security, forensics, and OSINT.

<p>
  <a href="https://www.linkedin.com/in/aristarhucolov"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://youtube.com/@Aristarh.Ucolov"><img src="https://img.shields.io/badge/YouTube-FF0000?style=for-the-badge&logo=youtube&logoColor=white" alt="YouTube"></a>
  <a href="mailto:ucolov.artur@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
</p>

---

<div align="center">

<img src="https://github-readme-stats.vercel.app/api?username=AristarhUcolov&show_icons=true&theme=transparent&hide_border=true&rank_icon=github" alt="GitHub Stats" height="165">
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AristarhUcolov&layout=compact&theme=transparent&hide_border=true&langs_count=8&hide=php,batchfile" alt="Top Languages" height="165">

<sub>C.N.S — Clear Net Sky · «Сова никогда не спит / The Owl never sleeps»</sub>

</div>
