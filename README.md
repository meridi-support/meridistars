# 🌌 MeridiStars

**A single-file planetarium that runs in your browser.**
ブラウザだけで動く、1 ファイルのプラネタリウムです。

▶ **Open MeridiStars → https://meridibrand.com/stars/**

> No Ads. No Subscriptions. Just Tools.

---

## Features / できること
- 🌠 **Night Sky** — 88 constellations with IAU lines & boundaries, the Milky Way, and 9,000+ real stars with color, distance and spectral type
  88 星座（線と境界）、天の川、9,000 個以上の実在の星（色・距離・スペクトル）
- 🌫 **Deep Sky** — 150 galaxies, nebulae and star clusters (all Messier objects + 41 famous targets), as a long-exposure photo or as seen by eye
  星雲・銀河・星団 150 個（メシエ天体すべて＋有名な 41 個）。写真の見え方と肉眼の見え方を切り替え
- 📷 **Camera mode** — try ISO, shutter, aperture, lens and sky darkness, and see roughly what a photo would capture (star trails, moonlight, the "500 rule")
  ISO・シャッター・F 値・レンズ・空の暗さを変えて「だいたいこう写る」を試せます（星の軌跡・月明かり・500 のルール）
- 🕳 **Journey to the black hole** — fly from the Solar System past Gaia BH1 to Sagittarius A\*, with real gravitational lensing (WebGL)
  太陽系から Gaia BH1 を通って、天の川の中心のいて座 A\* へ。重力レンズで曲がる光を WebGL で再現
- 📍 **119 locations** — cities, observatories, and even the North & South Poles
  世界の都市・天文台・北極と南極など 119 か所から星空を見られます
- 🕰 **Time control** — see the sky at any date and time
  好きな日時の空を再現できます
- 📱 **Touch & Lite mode** — drag, pinch and tap on phones; a lighter mode for older devices
  スマホでは指で動かす・広げる・押す。古い端末向けの軽量モードつき
- 🌐 **日本語 / English / both**
- 📦 **Single HTML file** — no install, no account
  インストールも登録もいりません

## 🌌 ↕ 🪨 ↕ 🌊 Sky, Land and Sea / 空・陸・海
MeridiStars looks **up**. Its sister tools take you the rest of the way:
- 🪨 [MeridiGround](https://meridibrand.com/ground/) — from your doorstep up to the edge of space and down to Earth's core
- 🌊 [MeridiDepths](https://meridibrand.com/depths/) — from the sea surface to the deepest ocean trenches

MeridiStars は空を見上げる道具です。🪨 MeridiGround は足もとから地球の中心まで、🌊 MeridiDepths は海面から海溝の底まで、いっしょに旅ができます。

## Notes / ご注意
- Star positions are calculated for viewing and learning, not for navigation or scientific use.
  星の位置は、眺めて楽しむ・学ぶための計算です。航海や研究には使わないでください。
- Deep-sky images and the black hole are illustrations drawn from catalog data and physics, not real photos.
  星雲・銀河の絵とブラックホールは、星表のデータと物理から描いた再現です（本物の写真ではありません）。
- Found something wrong? Let us know in [Discussions](https://github.com/meridi-support/meridi-square/discussions).
  おかしな所があれば、Discussions で教えてください。

## Data / データ
- Stars: Yale Bright Star Catalog (public domain)
- Deep-sky objects: [OpenNGC](https://github.com/mattiaverga/OpenNGC) by Mattia Verga (CC BY-SA 4.0)
- Planets: NASA Planetary Fact Sheet

## Privacy / プライバシー
- No ads, no account, no cookies.
- Only an anonymous page-view count via [GoatCounter](https://www.goatcounter.com/).
  GoatCounter によるページビューの数（匿名）だけを計測しています。

## Changelog
### v1.1.0 — 2026-11-24
- 🌫 Deep Sky: 150 galaxies, nebulae and clusters (Messier + 41 famous targets, OpenNGC), 📷 photo / 👁 naked-eye views, tap for details, search by name / M / NGC
  星雲・銀河・星団 150 個。写真／肉眼の見え方、押すと説明、名前・M・NGC 番号で検索
- 📷 Camera mode (C key): ISO, shutter, aperture, lens, sky darkness, moonlight, star trails, the "500 rule"
  カメラモード：ISO・シャッター・F 値・レンズ・空の暗さ・月明かり・星の軌跡・500 のルール
- 🕳 Journey to the black hole: Solar System → nearest star → Gaia BH1 → Sagittarius A\*, with WebGL gravitational lensing (shadow, photon ring, glowing disk, Einstein ring), 🖼 View mode (V key)
  ブラックホールへの旅：WebGL の重力レンズ（影・光の輪・光る円盤・アインシュタインリング）、🖼 眺めるモード
- 📱 Touch: drag to look around, pinch to zoom, tap for info (also in Solar System). 🪶 Lite mode (F key), on by default on phones
  指の操作（グリグリ・つまんで拡大・タップで説明）、軽量モード（スマホでは自動でオン）
- 🌐 Solar System in Japanese too; info-panel labels follow the selected language; your language is remembered
  Solar System も日英に。説明欄の項目名も選んだ言葉に。言葉を端末に記憶
- Planet data checked against the NASA Planetary Fact Sheet / 惑星の数字を NASA の値と照合
- Fixed: Pause did not stop the black-hole journey / ブラックホールへの旅で一時停止が効かなかった
- Fixed: Camera bar stayed visible in Solar System / Solar System でカメラの設定が残っていた
- Fixed: Removed ~24 KB of stray preview code from v1.0.0 / v1.0.0 に混ざっていた余計な部分（約 24KB）を削除

### v1.0.0 — 2026-11-10
- First release / 初回リリース

## Support
If you enjoy MeridiStars, you can support development here:
☕ **https://buymeacoffee.com/meridius**

## Other tools by Meridi Brand
- 📅 [MeridiMeet](https://meridibrand.com/meet/) — schedule polls across time zones
- 🐾 [MeridiLingo](https://meridibrand.com/lingo/) — 760+ real-world English expressions & AI prompts
- 💻 [MeridiSync](https://meridistore.booth.pm/items/8790105) — text snippet expander for Windows
- 🪨 [MeridiGround](https://meridibrand.com/ground/) — from the sky to Earth's core
- 🌊 [MeridiDepths](https://meridibrand.com/depths/) — deep-sea explorer
- 🎮 [MeridiPlay](https://meridibrand.com/play/) — 18 free browser games
- 🧮 [MeridiConvert](https://meridibrand.com/convert/) — unit converter & handy calculators
- 🧰 [Meridi Tools](https://meridibrand.com/tools/) — ad-free toolbox: timer & scoreboard, text cleaner, TRPG dice, QR codes, photo location remover, bill splitter, timecard & wage calculator
- 🏠 [meridibrand.com](https://meridibrand.com/)


## License
MIT © 2026 Meridi Brand
