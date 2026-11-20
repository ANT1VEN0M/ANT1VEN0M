<div align="center">

<!-- Cyberpunk Header Wave Banner -->
<img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=12,24,35&height=220&section=header&text=ANT1VEN0M%20%E2%9A%A1%20BUNKER&fontSize=42&fontAlignY=38&desc=Lead%20Architect%20@%20Bunker%20VPN%20%E2%80%A2%20Xray%20Core%20%E2%80%A2%20Android%20Cyber-Engineering&descAlignY=62&descAlign=50&fontColor=ffffff" width="100%"/>

<!-- Animated Typing Text -->
<a href="https://t.me/BUNKER_KOTA">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=19&duration=2800&pause=1200&color=06B6D4&center=true&vCenter=true&width=650&lines=%E2%9A%A1+Welcome+to+the+Bunker+Ecosystem;%F0%9F%9B%A1%EF%B8%8F+Bunker+VPN+v1.3.9+Stealth+Edition+is+Live;%F0%9F%8D%8F+1-Click+Onboarding+for+iOS%2C+Windows+%26+Mac;%F0%9F%90%88%E2%80%8D%E2%AC%9B+VLESS+Reality+%E2%80%A2+Cloudflare+WARP%2B+(880)+%E2%80%A2+Xray;%F0%9F%9A%80+Building+unbreakable+network+tunnels+%26+freedom" alt="Typing SVG" />
</a>

<br/>

<!-- Community & Contact Badges -->
<p align="center">
  <a href="https://t.me/BUNKER_KOTA">
    <img src="https://img.shields.io/badge/📢_Канал_Бункера-BUNKER__KOTA-0088cc?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Channel"/>
  </a>
  &nbsp;
  <a href="https://t.me/BUNKER_K0TA">
    <img src="https://img.shields.io/badge/💬_Чат_Сообщества-BUNKER__K0TA-7C3AED?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram Chat"/>
  </a>
  &nbsp;
  <a href="https://t.me/k0tlux">
    <img src="https://img.shields.io/badge/👤_Создатель-@k0tlux-10B981?style=for-the-badge&logo=telegram&logoColor=white" alt="Personal Telegram"/>
  </a>
</p>

</div>

---

### 🐈‍⬛ О проекте и экосистеме Бункера

Разрабатываю передовые открытые решения для высокоскоростного обхода блокировок, интеллектуальной маршрутизации и защиты трафика в условиях ТСПУ:

* 🛡️ **[Bunker VPN (Android)](https://github.com/ANT1VEN0M/BunkerVPN)** — флагманский VPN-клиент на базе **Xray Core Lite** и Jetpack Compose.
  * **Режим «Stealth» (v1.3.9):** чистый глубокий OLED-черный интерфейс (`#000000`), компактная шапка **48dp** без лишнего визуального шума и эмодзи.
  * **Безотказный WARP+ на порту 880:** встроенная генерация WireGuard-аккаунтов Cloudflare с байтами рукопожатия `client_id`, работающая даже офлайн.
  * **Аппаратный Kill-Switch:** блокировка утечек DNS и трафика с сохранением стабильности Wi-Fi (NDP/ICMPv6).
  * **Скоростные зеркала (`ghfast.top`):** прямое обновление и загрузка в РФ без необходимости стороннего VPN.
* 🌐 **[Bunker-Auto-Engine](https://github.com/ANT1VEN0M/Bunker-Auto-Engine) & [Веб-портал / Telegram Mini App (TMA)](https://ant1ven0m.github.io/Bunker-Auto-Engine/)** — автономный движок автопилота подписок и универсальный портал подключения:
  * **Telegram Mini App (TMA):** работает прямо внутри Telegram с поддержкой тактильной отдачи (Haptics), авто-подстройкой темы, интерактивным выбором фидов, живым замером пинга (Live Ping Meter), аварийным MTProto прокси и генерацией QR-кодов.
  * Проверяет **28 источников** (включая зеркала AeryxVPN, незаблокируемый GitLab `hub.mos.ru` и агрегатор **mehdirzfx** на 1125+ фидов) каждые 6 часов на GitHub Actions через реальное ядро Xray Core (HTTP 204 real traffic test).
  * Генерирует **470+ гарантированно живых серверов** с разделением на фиды: *Микс*, *Белый список*, *Завод 443/53*, *Турбо*, *Discord Voice & Gaming*, *Telegram SOS*.
  * **Поддержка Apple iOS (iPhone/iPad) и Windows/Mac:** подключение в 1 клик через Karing, Hiddify, v2rayN, Streisand.
  * **Поддержка домашних роутеров (Keenetic, OpenWrt, MikroTik):** готовые `.conf` файлы WireGuard на порту 880 для работы YouTube 4K и Discord на Smart TV, консолях и ПК без VPN на каждом клиенте.
  * **Фикс Discord Voice (RTC / Стримы):** специализированный пул Hysteria 2 и Cloudflare WARP+ (Full-Cone UDP) без задержек и подвисаний.
* ⚡ **[Bunker Parser](https://github.com/ANT1VEN0M/BunkerParser)** — высокоскоростной парсер и нормализатор конфигураций на Xray.
* 🤖 **Bunker OS Bot ([@BunkerCatOSBot](https://t.me/BunkerCatOSBot))** — Telegram-бот Бункера для публикации конфигураций и быстрой поддержки.

---

### 🛠 Стек технологий и протоколов

<div align="center">

#### 🛰️ Протоколы туннелирования и обхода блокировок
![VLESS Reality](https://img.shields.io/badge/VLESS_Reality-7C3AED?style=flat-square&logo=cloudflare&logoColor=white)
![WireGuard WARP+](https://img.shields.io/badge/WireGuard_WARP+_(Port_880)-F38020?style=flat-square&logo=cloudflare&logoColor=white)
![Hysteria 2](https://img.shields.io/badge/Hysteria_2_(QUIC)-EF4444?style=flat-square&logo=speedtest&logoColor=white)
![Trojan](https://img.shields.io/badge/Trojan-10B981?style=flat-square&logo=lock&logoColor=white)
![Shadowsocks 2022](https://img.shields.io/badge/Shadowsocks_2022-06B6D4?style=flat-square&logo=shield&logoColor=white)
![XHTTP / gRPC](https://img.shields.io/badge/XHTTP_/_gRPC-F59E0B?style=flat-square&logo=fastapi&logoColor=white)

#### 💻 Разработка и инфраструктура
![Kotlin](https://img.shields.io/badge/Kotlin-7F52FF?style=flat-square&logo=kotlin&logoColor=white)
![Android SDK](https://img.shields.io/badge/Android_SDK-3DDC84?style=flat-square&logo=android&logoColor=white)
![Jetpack Compose](https://img.shields.io/badge/Jetpack_Compose-4285F4?style=flat-square&logo=jetpackcompose&logoColor=white)
![Go](https://img.shields.io/badge/Go_(Xray_Core)-00ADD8?style=flat-square&logo=go&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![HTML5 / JS](https://img.shields.io/badge/Web_Landing-E34F26?style=flat-square&logo=html5&logoColor=white)
![GitHub Actions CI/CD](https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white)
![jsDelivr CDN](https://img.shields.io/badge/jsDelivr_CDN-E84D3D?style=flat-square&logo=jsdelivr&logoColor=white)

</div>

---

### 🔥 Ключевые проекты экосистемы

<table>
  <tr>
    <td width="50%">
      <h3><a href="https://github.com/ANT1VEN0M/BunkerVPN">📱 Bunker VPN for Android (v1.3.9)</a></h3>
      <p>Официальный Android-клиент Бункера: Stealth-минимализм (OLED), встроенный Cloudflare WARP+ (порт 880), защита от утечек Kill-Switch, live-спидометр сессии и поддержка всех современных протоколов.</p>
      <p>
        <a href="https://github.com/ANT1VEN0M/BunkerVPN/releases/latest"><img src="https://img.shields.io/github/v/release/ANT1VEN0M/BunkerVPN?color=7C3AED&label=Релиз&style=flat-square" alt="Release"/></a>
        <a href="https://ghfast.top/https://github.com/ANT1VEN0M/BunkerVPN/releases/download/v1.3.9/BunkerVPN-arm64-v8a.apk"><img src="https://img.shields.io/badge/Скачать-ARM64-10B981?style=flat-square&logo=android&logoColor=white" alt="Download ARM64"/></a>
      </p>
    </td>
    <td width="50%">
      <h3><a href="https://github.com/ANT1VEN0M/Bunker-Auto-Engine">⚡ Bunker-Auto-Engine & Mini App</a></h3>
      <p>Автономный автопилот на 28 источников + Telegram Mini App с Live-замером пинга, аварийным MTProto-прокси в 1 клик, QR-кодами и быстрым подключением для iPhone (Karing) и ПК (Hiddify).</p>
      <p>
        <a href="https://ant1ven0m.github.io/Bunker-Auto-Engine/"><img src="https://img.shields.io/badge/Mini_App-1_клик-0088cc?style=flat-square&logo=telegram&logoColor=white" alt="Mini App"/></a>
        <a href="https://github.com/ANT1VEN0M/Bunker-Auto-Engine/releases/latest"><img src="https://img.shields.io/github/v/release/ANT1VEN0M/Bunker-Auto-Engine?color=10B981&label=Автопилот&style=flat-square" alt="Engine Release"/></a>
      </p>
    </td>
  </tr>
</table>

---

### 📊 Статистика активности на GitHub

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=ANT1VEN0M&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a855f7&icon_color=06b6d4&text_color=e2e8f0" alt="ANT1VEN0M GitHub Stats" height="165" />
  &nbsp;
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=ANT1VEN0M&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a855f7&text_color=e2e8f0" alt="Top Languages" height="165" />
</div>

---

<div align="center">
  <i>«Свободный интернет без границ, цензуры и задержек»</i> ⚡<br/>
  <b>Бункер Кота © 2026</b>
  
  <br/><br/>
  <img src="https://capsule-render.vercel.app/api?type=waving&color=gradient&customColorList=35,24,12&height=90&section=footer" width="100%"/>
</div>
