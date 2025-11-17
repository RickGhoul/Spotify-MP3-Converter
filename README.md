# 🎧 Spotify MP3 Converter

Converte playlists, álbuns e músicas do Spotify para MP3 usando o Google Colab.

---

## ▶️ Abrir no Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/18E5p9n6z6HHDA-Q86EKtw1gXNEedz-lW?usp=sharing)


🎧 Spotify API – How to Get Your Credentials

To access Spotify’s API, you need to create an app inside Spotify for Developers.

1. Create a Spotify Developer Account

Go to the Spotify Developer Dashboard:
<a href="https://developer.spotify.com/dashboard" target="_blank"><img src="https://img.shields.io/badge/Open%20Spotify%20Dashboard-1DB954?style=for-the-badge&logo=spotify&logoColor=white"/></a>

Log in with your Spotify account.

2. Create a New Application

Click “Create an App”.

Give it a Name and Description.

Accept the terms and press Create.

3. Find Your API Keys

After creating the app:

Go to Dashboard → Your App

You will see:

Client ID:  xxxxxxxxxxxxxxxxx
Client Secret:  xxxxxxxxxxxxxxxxx


⚠️ NEVER share your Client Secret publicly. Treat it like a password.

4. Configure Redirect URI (If Needed)

Some Spotify API flows require a redirect URI.

Open your app settings

Scroll to Redirect URIs

Click Add Redirect URI

Enter something like:
http://localhost:8888/callback

Save

🍪 Installing the “Get cookies.txt” Chrome Extension

This extension allows you to export your own browser cookies in a file.
This is often used for debugging or personal automation.

⚠️ Only export cookies from sites you own or have permission to access.
⚠️ Do NOT upload cookie files anywhere—they contain sensitive login info.

1. Install Extension

<a href="https://chromewebstore.google.com/search/get%20cookies.txt" target="_blank"><img src="https://img.shields.io/badge/Open%20Chrome%20Webstore-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white"/></a>

2. How to Use

Install the extension

Visit the site you want to export cookies from

Click the extension icon in Chrome

Choose “Export cookies to cookies.txt”

A file named cookies.txt will be saved to your computer

📁 File Overview

IMFO.md — This documentation

cookies.txt — Exported cookies (keep private!)

Spotify API credentials — Retrieved from the Spotify developer dashboard
