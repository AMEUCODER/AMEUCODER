<div align="center">

# Hi, I'm Ameur 👋

**Student developer building real-time computer vision and full-stack web apps**

Python · OpenCV · Django · Next.js

<br />

[![Repositories](https://img.shields.io/badge/Repositories-AMEUCODER-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/AMEUCODER?tab=repositories)
[![Computer Vision](https://img.shields.io/badge/Computer_Vision-OpenCV_·_MediaPipe_·_YOLO-0b6e4f?style=for-the-badge&logo=opencv&logoColor=white)](https://github.com/AMEUCODER/Computer-Vision-py)
[![Full-Stack](https://img.shields.io/badge/Full--Stack-Django_·_Next.js-2b5fb3?style=for-the-badge&logo=django&logoColor=white)](https://github.com/AMEUCODER/inventory-management-system)

</div>

---

## 🚀 About me

I like building software that **works with the real world**: cameras that understand what they see, and apps that real shops could actually use. I focus on projects that run end to end, with clean structure, tests, documentation and one-command setup.

- 🔭 Building: computer vision tools, full-stack web apps and a face-recognition photo sorter (OpenCV)
- 🌱 Currently learning: C and embedded systems, Flutter, pandas, machine-learning classifiers and LangChain
- 🎯 Looking for: an **internship** in AI / ML, computer vision or full-stack development

---

## 🛠️ Tech stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,django,nextjs,react,ts,opencv,numpy,sqlite,docker,githubactions,git,github,linux&perline=13" alt="Python, Django, Next.js, React, TypeScript, OpenCV, NumPy, SQLite, Docker, GitHub Actions, Git, GitHub, Linux" />
</p>

| Area | What I use |
|---|---|
| **Computer vision** | OpenCV, MediaPipe (hands, face mesh), YOLOv4-tiny object detection |
| **Backend** | Python, Django, Django REST Framework, FastAPI, SQLite |
| **Frontend** | Next.js (App Router), React, TypeScript |
| **Desktop and games** | Tkinter, CustomTkinter, Pygame |
| **Tooling** | Git and GitHub, Docker, GitHub Actions, pytest |
| **Also learning** | C, Flutter, pandas |

---

## ⭐ Featured projects

### 📦 [Inventory Management System](https://github.com/AMEUCODER/inventory-management-system)

A full-stack inventory app. **Admins** manage products, stock, users and the full transaction history. **Cashiers** do one thing: scan a barcode with the camera to sell or return an item.

- **Django REST API** with JWT auth and roles that are checked on every request
- **Race-safe scanning:** stock changes and the audit log happen in one atomic transaction, so the last unit can never be sold twice
- **Next.js + React + TypeScript** UI with a live camera barcode scanner
- **28 automated tests** and **Docker Compose** one-command setup

`Django` `DRF` `Next.js` `TypeScript` `Docker`

<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/AMEUCODER/inventory-management-system">
        <img src="https://raw.githubusercontent.com/AMEUCODER/inventory-management-system/main/screenshots/scan.png" alt="Inventory system: camera scan page" />
      </a>
      <br /><sub>Camera scanning with a SELL / RETURN switch</sub>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/AMEUCODER/inventory-management-system">
        <img src="https://raw.githubusercontent.com/AMEUCODER/inventory-management-system/main/screenshots/transactions.png" alt="Inventory system: transaction history" />
      </a>
      <br /><sub>Admin view with a full, filterable audit trail</sub>
    </td>
  </tr>
</table>

---

### 🧑‍🤝‍🧑 [Face Sorter](https://github.com/AMEUCODER/image-classifier)

Sorts a folder of photos into one folder per person. One pipeline with swappable classifiers, so the same code can later sort by object, scene or date.

- **Face recognition** with a Haar cascade detector and an LBPH recognizer; new people are trained automatically from their folder
- **A log of every decision** (CSV), plus an evaluation tool with accuracy per person and a threshold sweep
- **Honest tooling:** a dataset checker that catches unusable photos and train/val leaks, and an explain tool that shows why one photo got its label
- **17 pytest tests** and a GitHub Actions workflow

`Python` `OpenCV` `pytest`

---

### 🖼️ [Image AI Studio](https://github.com/AMEUCODER/ImageToolsStudio) <sub>(in development)</sub>

One **reusable Python image engine** with three front doors: a desktop app, a FastAPI backend and a React + TypeScript PWA, packaged with Docker. The focus is architecture: the engine knows nothing about windows or HTTP, so the same tools power every interface without being rewritten.

- **Plug-in tools:** every tool found in `engine/tools/` appears in the sidebar automatically, and its sliders and dropdowns are generated from the tool's parameter list, so a new tool needs no UI code
- **7 tools so far:** Blur, Auto Enhance, Crop, Rotate / Flip, Adjust, Text Watermark and Face Blur
- **Responsive and safe:** processing runs on a worker thread, with 20 undo steps, one-click reset to the original, and PNG / JPEG / WebP export
- **Tested:** `pytest` suites cover the engine, the controller (undo, reset, errors) and face blur, without needing a display

`Python` `CustomTkinter` `OpenCV` `MediaPipe` `pytest`

---

### 👁️ [Computer Vision Playground](https://github.com/AMEUCODER/Computer-Vision-py)

A collection of **11 computer vision projects** plus a plug-in image toolkit, organized by category, each with its own README and setup steps.

| Project | What it does |
|---|---|
| [**WaterMark**](https://github.com/AMEUCODER/Computer-Vision-py/tree/main/ImgVision/WaterMark) | Add text (including Arabic) or logo watermarks, or remove one from a selected area with OpenCV inpainting |
| [**WatchDog**](https://github.com/AMEUCODER/Computer-Vision-py/tree/main/SafetyVision/WatchDog) | Webcam security monitor using YOLOv4-tiny: flags people, sounds an alarm, sends phone notifications and counts people leaving the frame |
| [**Background Outpainter**](https://github.com/AMEUCODER/Computer-Vision-py/tree/main/ImgVision/outpainting) | Tkinter desktop app that extends photo backgrounds to any resolution (Reels, Instagram, 4K, A4) for many photos at once |
| [**FaceBlur**](https://github.com/AMEUCODER/Computer-Vision-py/tree/main/ImgVision/face_blur) | Desktop app that finds every face in your photos (YuNet detector) and blurs them in one click, for single images or whole folders |
| [**Head-Tilt Traffic Racer**](https://github.com/AMEUCODER/Computer-Vision-py/tree/main/GameVision/2D-Car-Game) | A Pygame game you steer by tilting your head, with all sound and graphics generated in code |
| [**Tilt Flap**](https://github.com/AMEUCODER/Computer-Vision-py/tree/main/GameVision/FlappyBird) | Flappy Bird you play by tilting your head, with three difficulty modes and a top-5 leaderboard |
| [**Hand Gesture Filter Camera**](https://github.com/AMEUCODER/Computer-Vision-py/tree/main/HandVision/HandVision-filters) | Switch live filters by holding up fingers; hands-free photo countdown and video recording |
| [**Air Draw**](https://github.com/AMEUCODER/Computer-Vision-py/tree/main/HandVision/Air-Draw) | Draw in the air with your index finger; erase and clear with gestures |
| [**Sign Identification**](https://github.com/AMEUCODER/Computer-Vision-py/tree/main/HandVision/Sign-Identification) | Recognizes 11 hand signs with rule-based joint-angle geometry and no training data |
| [**Rock-Paper-Scissors**](https://github.com/AMEUCODER/Computer-Vision-py/tree/main/HandVision/Rock-papper-scissors) | Play against the computer using your real hand |
| [**SnapProps**](https://github.com/AMEUCODER/Computer-Vision-py/tree/main/FaceVision/SnapProps) | Face-tracked AR props and filters |

`OpenCV` `MediaPipe` `YOLO` `NumPy` `Pygame` `Tkinter` `CustomTkinter`

<table>
  <tr>
    <td align="center" width="50%">
      <a href="https://github.com/AMEUCODER/Computer-Vision-py/tree/main/GameVision/2D-Car-Game">
        <img src="https://raw.githubusercontent.com/AMEUCODER/Computer-Vision-py/main/GameVision/2D-Car-Game/screenshots/gameplay.png" alt="Head-Tilt Traffic Racer gameplay" />
      </a>
      <br /><sub>Head-Tilt Traffic Racer</sub>
    </td>
    <td align="center" width="50%">
      <a href="https://github.com/AMEUCODER/Computer-Vision-py/tree/main/ImgVision/face_blur">
        <img src="https://raw.githubusercontent.com/AMEUCODER/Computer-Vision-py/main/ImgVision/face_blur/screenshots/interface.png" alt="FaceBlur desktop app" />
      </a>
      <br /><sub>FaceBlur</sub>
    </td>
  </tr>
</table>

---

## 📚 Learning in public

| Repo | What it is |
|---|---|
| [**C-programming**](https://github.com/AMEUCODER/C-programming) | University lab exercises (TP1 to TP12) and mini projects in C |
| [**Data_Flow**](https://github.com/AMEUCODER/Data_Flow) | pandas practice and a Titanic data-analysis notebook |
| [**Flutter-to-do-app**](https://github.com/AMEUCODER/Flutter-to-do-app) | My first Flutter app |

---

## 🧭 How I like to work

- **Finish things.** Every project has setup instructions, a README and a working demo path.
- **Keep it readable.** Small modules, one `config.py` for tunable numbers, comments that explain why.
- **Test what matters.** Business rules such as stock limits and permissions are covered by automated tests.
- **Real-time first.** In computer vision, speed and responsiveness count as much as accuracy.

---

<div align="center">

**Want to see more?** Browse my [repositories](https://github.com/AMEUCODER?tab=repositories) or open an issue on any project. Feedback is welcome.

</div>
