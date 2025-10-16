# Train-Driver-2-Tool-for-track-occupation
Tool for mechanical Signal Boxes
# Mechanical Signal Box Track Board

Maybe some of you still remember:  
Back in **2023**, it was announced in *Week in the Simulator* that there would eventually be a board in the mechanical signal box where you could mark tracks as occupied:  
👉 [Week in the Simulator – Announcement (2023)](https://td2.info.pl/english-boards/week-in-the-simulator/msg82099/#msg82099)

![Original concept](https://img.ttsk.ngo/images/2023/08/25/r1.md.png)

Unfortunately, this feature never made it into the simulator — which is a real shame.  
So, I decided to create a **simple web application** that does exactly that.

It even includes an **optional automatic clearing feature**:  
if a train leaves the station (detected via the game log), the track will automatically be cleared.  
> Works only in **Chrome-based browsers**.

---

### 🖼️ Screenshots

![Log monitoring](https://img.ttsk.ngo/images/2025/10/16/2025-10-16-13_35_30-Logs---File-Explorer.jpg)
![App interface](https://img.ttsk.ngo/images/2025/10/16/2025-10-16-15_28_55-Downloads---File-Explorer.jpg)

---

### ⚙️ Usage

The app consists of a **single HTML file**.  
Just open it in your browser, and it’s ready to use immediately.

I’ll continue to improve it, but this first version is already fully functional —  
feel free to test it and share your feedback.

---

### 🦁 Note for Brave Users

You need to manually enable the File Access API first:  
```
brave://flags/#file-system-access-api
```

---

![Example config](https://img.ttsk.ngo/images/2025/10/16/2025-10-16-13_38_45-Fan-Control-V244-userConfig.json.jpg)

---

### 📦 Download

You can download the web app from the release attachments.

---

### 📝 Changelog

| Date | Version | Notes |
|------|----------|-------|
| 16.10.2025 | v1 | Initial Release |
| 16.10.2025 | v2 | Added Dark Theme |
