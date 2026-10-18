<p align="right"><a href="README.zh_CN.md">简体中文</a> · <strong>English</strong></p>

# Xingyu Pocket 1.0

**English comes first, with room for play.** A pink-and-plum learning and entertainment companion.

![Xingyu Pocket cover](cover.png)

## Explore

- English: eight practical themes, 64 words and 128 offline word/example recordings; cards, listening choices, starred/missed review and an example challenge.
- AI Partner: XiaoZhi-based continuous free conversation plus three English situations and nine practice cards.
- Radio: six Kunming/Yunnan Internet stations with direct station switching.
- Games: Tetris, Pocket Bunny and Memory Match.
- Personal badge: portrait, nickname, signature, clock, editable city and online weather.
- Wi-Fi: scan, enter passwords and switch networks on the device; optional phone web setup.

| English | AI and radio |
| --- | --- |
| ![English preview](english.png) | ![Companion and radio preview](companion-radio.png) |

![Play preview](play.png)

Images are native UI renders with generic fixture data, not a child's photo or personal device data.

## Install

Find the Chinese title in the [AI Passport play community](https://ai-passport.folotoy.cn/plays/); the actual page determines its review/publication status.
Alternatively download the [merged 1.0 firmware](xingyu-pocket-1.0-full.bin) and use the [official flasher](https://ai-passport.folotoy.cn/tools/web-flasher/).
The merged image is for a full refresh at `0x0`, which may clear existing settings and records. Save anything you need first; never substitute an app-only image at that offset.

On home, Up opens English; Down/OK opens the menu. Up/Down selects, OK enters and held OK returns. See the [user guide](MANUAL.md) for Wi-Fi, portraits, independent XiaoZhi pairing and controls.
Bind AI Partner to your own account with the activation code shown on your own device. The distribution contains no author's pairing credentials, Wi-Fi passwords, personal portraits or learning records.

## Version and limits

Product version 1.0 maps to the unchanged tested build `0.1.0-rc10`; later unflashed work is excluded.
The first 64-word catalog is a supplement, not a full course or learning guarantee. AI/radio/weather need Internet and third-party services. Radio may buffer; optional AQI may stay `--` and uses US AQI when available. Portrait effects are image processing, not generative redrawing. Muse is not implemented. Build/host checks and scoped device feedback passed, while exhaustive long-duration/adverse-network/power-loss/conversation coverage remains incomplete.

## Distribution

This repository provides presentation material, documentation and firmware. Core source is private. Binary distribution cannot guarantee resistance to reverse engineering. No source archive, ELF/MAP debug file, raw log or device-storage dump is included.
See [checksums](SHA256SUMS), [release details](release.json) and [third-party notices](THIRD_PARTY_NOTICES.txt). Third-party licenses remain in force; the complete firmware is not being relicensed as MIT.
