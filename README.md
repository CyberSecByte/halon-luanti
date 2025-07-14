# 🧱 Oldosfan Minetest / Luanti Build for Mineclonia

A stripped-down, performance-optimized version of Minetest — tailored for **Mineclonia** gameplay — that includes essential server-side hooks for the [`mcl_localplayer`](https://codeberg.org/halon/mcl_localplayer/) client-side mod.

---

## ⚙️ What This Build Does

Mineclonia replaces Minetest's default player physics with a more Minecraft-like system. This fork enables:

- 🏊‍♂️ Swimming & ✈️ elytra-style fall flying
- 🏇 Client-side horse riding (no lag!)
- 🏹 Bow charging & dynamic FOV, all client-driven
- 🕹️ Physics calculated entirely client-side — no more input latency

Since Mineclonia requires a modified Minetest server to support these features, this repository provides ready-to-download builds for both Windows and Linux.

---

## 🔄 Ongoing Integration Efforts

A pull request is currently open to merge these server-side enhancements upstream:
- **Mineclonia Minetest fork:** https://codeberg.org/mineclonia/mineclonia/pulls/2516

This PR bundles all necessary modifications to support `mcl_localplayer`, and has seen positive initial feedback from testers.

---

## 🚦 Usage Impact

> _“Once installed, there’s no going back.”_

Players consistently report smoother gameplay and far lower lag — a testament to the mod’s benefits, even during early testing.

---

## 🧩 This Package Includes

- Prebuilt Minetest engine with [`required patches`](https://codeberg.org/halon/Minetest)
- Auto-cloned [`mcl_localplayer`](https://codeberg.org/halon/mcl_localplayer) mod


## 📦 For Windows

Go to the [Actions tab.](https://github.com/CyberSecByte/halon-luanti/actions/workflows/win-build.yml)

Click on the latest successful "Build on Windows" workflow run.

Scroll to the Artifacts section at the bottom.

After Downloading, Extract it and run bin\minetest.exe.



## 🐧 For Linux

Go to the [Actions tab.](https://github.com/CyberSecByte/halon-luanti/actions/workflows/linux-build.yml)

Click on the latest successful "Build on Linux" workflow run.

Scroll to the Artifacts section at the bottom.

After Downloading, Extract it and run ./bin/minetest

>🔒 Note: You must be logged into a GitHub account to download workflow artifacts from the Actions tab. This is a GitHub restriction — downloads are not available to anonymous users.
