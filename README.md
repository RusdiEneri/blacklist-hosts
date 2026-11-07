# 🛡️ DNS Blocklist Registry

Koleksi blocklist DNS terkurasi untuk **AdGuard Home, Pi-hole, dan resolver pemblokir DNS lainnya**. Berkas di repositori ini disinkronkan otomatis dari sumber upstream dan disediakan melalui GitHub Raw, jsDelivr, serta RawGitHack.

> **Catatan:** pilih daftar sesuai kebutuhan. Mengaktifkan beberapa daftar dengan cakupan serupa dapat menambah duplikasi dan risiko false positive. HaGeZi Multi PRO++ bersifat lebih agresif; uji kompatibilitas perangkat dan situs yang biasa digunakan.

## Daftar Blocklist

| Daftar | Kegunaan | RawGitHack | jsDelivr | GitHub Raw | Jumlah entri* |
|---|---|---|---|---|---:|
| **HaGeZi Gambling** | Memblokir konten perjudian | [RawGitHack](https://raw.githack.com/RusdiEneri/blacklist-hosts/main/hosts/HaGeZi/gambling.txt) | [jsDelivr](https://cdn.jsdelivr.net/gh/RusdiEneri/blacklist-hosts@main/hosts/HaGeZi/gambling.txt) | [GitHub](https://raw.githubusercontent.com/RusdiEneri/blacklist-hosts/main/hosts/HaGeZi/gambling.txt) | 633,305 |
| **HaGeZi NSFW** | Memblokir konten dewasa | [RawGitHack](https://raw.githack.com/RusdiEneri/blacklist-hosts/main/hosts/HaGeZi/nsfw.txt) | [jsDelivr](https://cdn.jsdelivr.net/gh/RusdiEneri/blacklist-hosts@main/hosts/HaGeZi/nsfw.txt) | [GitHub](https://raw.githubusercontent.com/RusdiEneri/blacklist-hosts/main/hosts/HaGeZi/nsfw.txt) | 78,050 |
| **HaGeZi Multi PRO++** | Perlindungan umum yang lebih agresif | [RawGitHack](https://raw.githack.com/RusdiEneri/blacklist-hosts/main/hosts/HaGeZi/pro.plus.txt) | [jsDelivr](https://cdn.jsdelivr.net/gh/RusdiEneri/blacklist-hosts@main/hosts/HaGeZi/pro.plus.txt) | [GitHub](https://raw.githubusercontent.com/RusdiEneri/blacklist-hosts/main/hosts/HaGeZi/pro.plus.txt) | 243,518 |
| **HaGeZi Threat Intelligence Feeds — Medium** | Daftar threat intelligence versi medium | [RawGitHack](https://raw.githack.com/RusdiEneri/blacklist-hosts/main/hosts/HaGeZi/tif.medium.txt) | [jsDelivr](https://cdn.jsdelivr.net/gh/RusdiEneri/blacklist-hosts@main/hosts/HaGeZi/tif.medium.txt) | [GitHub](https://raw.githubusercontent.com/RusdiEneri/blacklist-hosts/main/hosts/HaGeZi/tif.medium.txt) | 365,665 |
| **StevenBlack Fake News & Misinformation** | Memblokir sumber fake news dan misinformasi | [RawGitHack](https://raw.githack.com/RusdiEneri/blacklist-hosts/main/hosts/StevenBlack/fakenews.txt) | [jsDelivr](https://cdn.jsdelivr.net/gh/RusdiEneri/blacklist-hosts@main/hosts/StevenBlack/fakenews.txt) | [GitHub](https://raw.githubusercontent.com/RusdiEneri/blacklist-hosts/main/hosts/StevenBlack/fakenews.txt) | 2,187 |

**Jumlah file:** 5

**Total entri lintas daftar:** 1,322,725

<sub>*Jumlah entri dihitung dari baris aturan nonkosong yang bukan komentar/header. Total ini bukan jumlah domain unik; duplikasi antar-daftar dapat terjadi.</sub>

---
*Sinkronisasi konten terakhir: 2026-11-08 05:06 WIB*

Sumber dan URL upstream dikelola melalui [`sources.md`](sources.md).
