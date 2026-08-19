# 🚀 Adults Live Stream Resolver Script v2.0 (WORKING 2026)
### Auto-Resolving HLS Live Stream Script for Xtream Codes, Load Balancers & IPTV Panels

---

## 📌 Overview
This repository contains the updated, 100% working **Adults Live Stream Resolver Script v2.0**. The legacy endpoints (`cdnneedtv.ru` / `cdntvnet.com`) became dead/offline, causing channel links to fail with 404 errors.

This v2.0 update fixes the resolver engine to dynamically extract live HLS stream tokens (`wmsAuthSign`) in under 200ms from active remote servers, restoring **all 36 adult channels** to 100% working status!

---

## 🔥 Key Features

- ⚡ **Instant Token Resolver**: Sub-200ms automated HLS `.m3u8` extraction.
- 🛡️ **Protected Codebase**: Obfuscated PHP code protecting core extraction algorithms.
- 🌐 **Full CORS & IPTV Compatibility**: Works out of the box with VLC, Xtream Codes, Tivimate, Smart TV, and web players.
- 🔄 **Automatic Load Balancer URL Detection**: Auto-detects server IP, domain, HTTP/HTTPS scheme and port.

---

## 📋 System Requirements

- **Web Server**: Apache, Nginx, LiteSpeed, or Xtream Codes Load Balancer.
- **PHP Version**: PHP 7.4, 8.0, 8.1, 8.2, or 8.3.
- **PHP Extensions**: `curl`, `json`, `zlib`.

---

## 🛠️ Installation & Configuration

### Step 1: Upload Files
Upload all files into your load balancer or web server directory:
```text
/home/xui/www/adults/
# or
/public_html/adults/
```

### Step 2: Access Endpoints
- **Full Playlist M3U URL**:
  ```text
  http://YOUR_SERVER_IP:PORT/adults/list.php
  ```
- **Single Channel Stream Endpoint (for Panel Assignment)**:
  ```text
  http://YOUR_SERVER_IP:PORT/adults/master.php?id=brazzers_eu
  ```

---

## 📺 Supported Channel List (36 Channels)

| Channel Slug | Channel Name | Status |
| :--- | :--- | :---: |
| `brazzers_eu` | Brazzers TV Europe | 🟢 ONLINE |
| `olala` | O-La-La | 🟢 ONLINE |
| `dorcel-tv` | Dorcel TV | 🟢 ONLINE |
| `hustlerhd` | Hustler HD | 🟢 ONLINE |
| `sextosenso` | Sextosenso | 🟢 ONLINE |
| `hustler` | Hustler TV | 🟢 ONLINE |
| `pink` | Pink O TV | 🟢 ONLINE |
| `private-tv` | Private TV | 🟢 ONLINE |
| `passion` | PassionXXX | 🟢 ONLINE |
| `sct` | SCT TV | 🟢 ONLINE |
| `centoxcento` | Cento X Cento | 🟢 ONLINE |
| `redlight` | RedLight HD | 🟢 ONLINE |
| `nuart` | Nuart TV | 🟢 ONLINE |
| `dusk` | Dusk | 🟢 ONLINE |
| `jasmin` | Jasmin TV | 🟢 ONLINE |
| `playboy` | Playboy TV | 🟢 ONLINE |
| `xmuvi-tv` | XMuvi TV | 🟢 ONLINE |
| `candy-tv` | Candy TV | 🟢 ONLINE |
| `babes-tv` | Babes TV | 🟢 ONLINE |
| `vivid-red` | Vivid Red | 🟢 ONLINE |
| `fap-tv-2` .. `fap-tv-compilation` | FAP TV Network (8 Channels) | 🟢 ONLINE |
| `rusnoch`, `nochnoiclub`, `oh-ah`, `egoist`, `erox-hd`, `shalun-tv`, `penthouse-1`, `penthouse-2` | Adult Premium Bundle | 🟢 ONLINE |

---

## 🌐 Official Community & Support

Join our official community for updates, technical discussions, and announcements:

- 💬 **Telegram Community**: [Join Telegram Group](https://t.me/+XkuQS_QuD6g4Nzc0)
- 🌐 **Official Forum**: [Visit X1 Forum](https://forum.x1panel.space/index.php)

---

> *Created & Released by X1 Stream Engine Team.*
