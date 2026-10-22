<p align="center">
  <img src="icon.png" width="128" alt="Veyra Player icon">
</p>

<h1 align="center">Veyra Player</h1>

<p align="center">
  A Windows video player that stays out of your way.<br>
  Hidden controls, episode folders, resume where you left off, and themes.
</p>

<p align="center">
  <a href="https://github.com/nova-faye/veyra-updates/releases/latest"><img alt="Latest release" src="https://img.shields.io/github/v/release/nova-faye/veyra-updates?color=ad9d85&labelColor=1c1c24"></a>
  <a href="https://github.com/nova-faye/veyra-updates/releases"><img alt="Downloads" src="https://img.shields.io/github/downloads/nova-faye/veyra-updates/total?color=ad9d85&labelColor=1c1c24"></a>
  <img alt="Platform" src="https://img.shields.io/badge/platform-Windows%2010%2F11-ad9d85?labelColor=1c1c24">
</p>

<p align="center">
  <b>English</b> · <a href="#العربية">العربية</a>
</p>

---

## Download

**[Download the latest version](https://github.com/nova-faye/veyra-updates/releases/latest)**, then run `Veyra-Player-Setup-x.x.x.exe`.

- Windows 10 or 11, 64-bit
- Website: https://nova-faye.github.io/veyra-updates/

> Windows may show a SmartScreen warning because the installer isn't code-signed yet. Click **More info**, then **Run anyway**.

## Features

- **A clean screen.** The interface is always hidden, even when you move the mouse. Press `Space` to show or hide it, so screenshots are never covered by controls.
- **Folders become seasons.** Pick a folder and every video inside appears as an episode, sorted properly (episode 2 before episode 10), subfolders included.
- **Pick up where you left off.** The home screen shows the last episode you watched with a thumbnail of the exact frame you stopped at, followed by recent episodes and the ones you haven't watched yet.
- **Skip the intro.** One key jumps past the opening. Set the length once and it is remembered.
- **Watch history.** Every show or folder you opened, with progress and time.
- **Clean screenshots.** Press `S` to save the current frame to your desktop, with no interface in it.
- **Subtitles.** Put an `.srt` or `.vtt` file with the same name next to the video and it loads automatically.
- **Themes.** Veyra, Dark, Light, Dracula, Nord, Solarized Dark, Solarized Light, Gruvbox and Catppuccin. The video area always stays black.
- **English and Arabic.** Switch the whole interface, including right-to-left layout, from Settings.
- **Open with.** Installs itself as an option for video files, so you can double-click any episode.

## Keyboard shortcuts

| Key | Action |
|---|---|
| `Space` | Show or hide the interface |
| `K` or click | Play / pause |
| `I` | Skip the intro |
| `N` / `P` | Next / previous episode |
| `L` | Episode list |
| `H` | Watch history |
| `B` | Back to the home screen |
| `,` | Settings |
| `←` `→` | Seek 5 seconds |
| `↑` `↓` | Volume |
| `M` | Mute |
| `[` `]` | Playback speed |
| `F` or double-click | Fullscreen |
| `S` | Save a screenshot to the desktop |
| `O` | Open a folder |

## Updating

Veyra Player updates itself from this repository. Open **Settings**, click **Check for updates**, then **Update now**. It also checks quietly each time it starts, and shows a banner on the home screen when a new version is ready.

## Supported formats

Veyra Player is built on the Chromium engine, so it plays what Chromium plays: MP4, WebM and most MKV files with common codecs (H.264, VP9, AAC, Opus, MP3). A few things are not supported:

- Some audio formats such as AC3 and DTS
- HEVC (H.265) on computers without hardware support for it
- Subtitles embedded inside MKV files, and `.ass` subtitles. Use external `.srt` or `.vtt` files instead

If an episode can't be played, the app tells you and you can jump to the next one.

## Privacy

Everything stays on your computer: history, playback positions, thumbnails and settings. The only network request the app makes is the update check to GitHub.

## About this repository

This repository hosts the Veyra Player releases and website. The app reads the **Releases** page to find updates, so please don't delete published releases.

---

<div dir="rtl">

<a name="العربية"></a>

## العربية

# Veyra Player

مشغل فيديو لويندوز ما يقف في طريقك. واجهة مخفية، مجلدات حلقات، استكمال من وين وقفت، وثيمات.

## التحميل

**[حمّل آخر نسخة](https://github.com/nova-faye/veyra-updates/releases/latest)** وشغّل الملف `Veyra-Player-Setup-x.x.x.exe`.

- ويندوز 10 أو 11، 64 بت
- الموقع: https://nova-faye.github.io/veyra-updates/

> ممكن يطلع تحذير SmartScreen من ويندوز لأن المثبّت غير موقّع رقمياً بعد. اضغط **More info** ثم **Run anyway**.

## المميزات

- **شاشة نظيفة.** الواجهة مخفية دايماً حتى لو حركت الماوس. اضغط `مسافة` تظهر وتختفي، فما تغطي لقطاتك أي أزرار.
- **المجلدات تصير مواسم.** اختر مجلد وكل فيديو فيه يطلع كحلقة، مرتبة بالطريقة الصحيحة (حلقة 2 قبل حلقة 10)، مع المجلدات الفرعية.
- **كمّل من وين وقفت.** الصفحة الرئيسية تعرض آخر حلقة شاهدتها مع صورة اللقطة اللي وقفت عندها بالضبط، وتحتها آخر الحلقات والحلقات اللي ما تابعتها.
- **تخطي الانترو.** زر واحد يقفز فوق المقدمة. حدد المدة مرة وحدة وتنحفظ.
- **سجل المشاهدة.** كل مسلسل أو مجلد فتحته مع تقدمك ووقت آخر مشاهدة.
- **لقطات نظيفة.** اضغط `S` تنحفظ اللقطة على سطح المكتب بدون أي واجهة فيها.
- **الترجمة.** حط ملف `.srt` أو `.vtt` بنفس اسم الفيديو جنبه وتنحمل تلقائياً.
- **الثيمات.** Veyra وDark وLight وDracula وNord وSolarized Dark وSolarized Light وGruvbox وCatppuccin. وخلفية الفيديو تبقى سوداء دايماً.
- **عربي وإنجليزي.** غيّر لغة الواجهة كاملة، مع اتجاه الكتابة من اليمين لليسار، من الإعدادات.
- **فتح باستخدام.** يضيف نفسه كخيار لملفات الفيديو، فتقدر تضغط دبل كليك على أي حلقة.

## الاختصارات

| الزر | الوظيفة |
|---|---|
| `مسافة` | إظهار أو إخفاء الواجهة |
| `K` أو كليك | تشغيل / إيقاف |
| `I` | تخطي الانترو |
| `N` / `P` | الحلقة التالية / السابقة |
| `L` | قائمة الحلقات |
| `H` | سجل المشاهدة |
| `B` | الرجوع للصفحة الرئيسية |
| `,` | الإعدادات |
| `←` `→` | تقديم وترجيع 5 ثواني |
| `↑` `↓` | الصوت |
| `M` | كتم |
| `[` `]` | سرعة التشغيل |
| `F` أو دبل كليك | ملء الشاشة |
| `S` | حفظ لقطة على سطح المكتب |
| `O` | فتح مجلد |

## التحديث

البرنامج يتحدث من هذا الـ repository. افتح **الإعدادات**، اضغط **تحقق من التحديثات** ثم **حدّث الآن**. وهو يتحقق بهدوء كل ما تشغله، ويطلع لك شريط في الصفحة الرئيسية لو فيه نسخة جديدة.

## الصيغ المدعومة

البرنامج مبني على محرك Chromium، فيشغّل اللي يشغله Chromium: ملفات MP4 وWebM ومعظم ملفات MKV بالكودكات الشائعة (H.264 وVP9 وAAC وOpus وMP3). وفيه أشياء غير مدعومة:

- بعض صيغ الصوت مثل AC3 وDTS
- HEVC (H.265) على الأجهزة اللي ما تدعمه بالعتاد
- الترجمة المدمجة داخل ملفات MKV وترجمة `.ass`. استخدم ملفات `.srt` أو `.vtt` خارجية بدلها

لو حلقة ما اشتغلت، البرنامج ينبهك وتقدر تنتقل للحلقة اللي بعدها.

## الخصوصية

كل شي يبقى على جهازك: السجل ومواضع الحلقات والصور المصغرة والإعدادات. الطلب الوحيد اللي يرسله البرنامج للإنترنت هو التحقق من التحديثات من GitHub.

## عن هذا الـ repository

هذا الـ repository يحتوي على إصدارات Veyra Player وموقعه. البرنامج يقرأ صفحة **Releases** عشان يلقى التحديثات، فلا تحذف الإصدارات المنشورة.

</div>
