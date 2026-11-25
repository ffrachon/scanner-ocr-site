---
title: Scanner OCR — Privacy Policy
---

# Scanner OCR — Privacy Policy

_Last updated: 30 October 2026_

Scanner OCR ("the app") is an application for Windows and macOS that scans paper
documents from your printer/scanner and turns them into searchable PDFs using
on-device Optical Character Recognition (OCR). This policy explains what the app
does and does not do with your data.

## Summary

**Scanner OCR does not collect, transmit, sell, or share any personal data.**
Everything you scan stays on your computer. There are no user accounts, no
advertising, and no analytics or telemetry.

## What the app processes, and where

| Data | Where it is processed | Leaves your device? |
|------|----------------------|---------------------|
| Scanned images, photos and PDFs you open | On your computer | No |
| Recognized text (OCR) | On your computer (Tesseract, PaddleOCR) | No |
| AI-suggested file names (Windows, Copilot+ PCs only) | On your PC (on-device Phi Silica model) | No |
| Saved PDFs / images | Saved to the folder you choose | No |

On Copilot+ PCs, the optional "Suggest name" feature uses the **Phi Silica** small
language model that runs **entirely on your device's NPU**. The document text is
processed locally to propose a file name; it is never uploaded.

## Network connections

The app makes only these local/Internet connections, and none of them carry your
document contents or personal information:

- **Your local network** — to discover and communicate with your scanner/printer
  over the standard eSCL/AirScan protocol. This traffic stays on your LAN. On macOS
  the system asks your permission first (Local Network).
- **github.com** — only to download additional **OCR language data files** on
  demand if you select a language that is not already bundled. These are generic
  language models, not your documents.

## Purchases

- **Windows:** the free trial and the purchase are handled by the Microsoft Store.
- **macOS:** the in-app purchase is handled by Apple through the App Store. To know
  how many of the free pages you have used, the app keeps a page count on your Mac,
  in your Keychain and in your own iCloud storage (iCloud key-value store), so that
  reinstalling the app or using another of your Macs doesn't reset it. This count is
  a single number; it is only readable by the app on your devices and is never sent
  to us.

We receive no personal information about you from either store beyond the
aggregate sales reports the stores provide to all developers.

## Data storage

Scanned documents and recognized text are stored only where you choose to save
them on your own device. The app keeps a small local log file (for
troubleshooting) and your app settings on your computer. Neither contains your
document contents and neither is transmitted anywhere.

## Children's privacy

The app is a general-purpose productivity tool and is not directed at children.
It collects no personal information from anyone.

## Changes to this policy

If this policy changes, the updated version will be posted at this URL with a new
"Last updated" date.

## Contact

Publisher: **Enohp** (Microsoft Store) · **Fabrice Frachon** (Mac App Store)
For privacy questions, contact: [scanocr@outlook.com](mailto:scanocr@outlook.com)
