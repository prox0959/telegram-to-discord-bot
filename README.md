# Telegram-to-Discord Forwarder Bot (Python)

[![Python](https://img.shields.io/badge/Python-3.10%2B-blue.svg)](https://python.org)
[![Discord.py](https://img.shields.io/badge/Discord-API-5865F2.svg)](https://discordpy.readthedocs.io/)
[![Telethon](https://img.shields.io/badge/Telegram-MTProto-0088cc.svg)](https://docs.telethon.dev/)
[![Status](https://img.shields.io/badge/Status-Completed-success.svg)](#)

An automated Python bridge that intercepts incoming messages, announcements, and media streams from specified Telegram channels/groups and forwards them to Discord channels in real time via Webhooks or Bot API.

---

## [EN] Features
* **Real-Time Event Listening:** Listens to incoming Telegram message streams asynchronously.
* **Webhook & Embed Formatting:** Re-formats text, usernames, and timestamps into clean Discord embeds.
* **Attachment Support:** Forwards images, files, and forwarded source references without data loss.
* **Error Resilience:** Automatic reconnection logic for intermittent network drops.

---

## [TR] Özellikler
Belirlenen Telegram kanallarından ve gruplarından gelen mesajları, duyuruları ve medyaları anlık olarak Discord sunucularına ileten Python botudur.
* Discord Webhook veya Bot API entegrasyonu ile zenginleştirilmiş (embed) mesaj iletimi.
* Asenkron mimari ile düşük gecikme süresi (low latency).
