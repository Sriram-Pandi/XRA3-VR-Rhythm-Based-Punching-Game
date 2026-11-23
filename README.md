# XR App 3 - VR Rhythm-Based Punching Game

## Downloads and project files

The APK and Unity project are hosted externally using the links below. This repository contains the project documentation.
- **APK File** - Install and play the VR rhythm game on Meta Quest [**Here**](https://drive.google.com/file/d/1EjXiawAs6rCxf8a1LJtAuaKfe6zApaXJ/view?usp=sharing)
- **Unity Project Files** - Explore the source code and scene setup [**Here**](https://drive.google.com/file/d/12RDyJYfWOTiOj1puYga9odBK0n1ScqJh/view?usp=sharing)

## 📌 Project Summary
**XR App 3** is an **immersive VR rhythm-based punching game**, inspired by **Beat Saber and HitStream**. This game challenges players to **punch incoming diamonds in sync with music beats**, ensuring correct hand coordination while avoiding obstacles. The experience is designed to enhance **hand-eye coordination, reaction time, and overall engagement** in VR.

## 🔹 Key Features
- **🎵 Music-Driven Gameplay:** Objects spawn in sync with the beat, creating a rhythm-based challenge.
- **🕹️ Multi-Level Experience:** Includes a **Lobby Menu** and three different levels with increasing difficulty.
- **💥 Object Punching & Breaking:**  
  - **Correct hand interaction:** Punch the diamonds with the right hand based on their color.  
  - **Break Mechanics:** Diamonds shatter into small, medium, or large fragments based on punch strength.  
- **🚀 Velocity-Based Destruction:**  
  - **Weak Punch (0.5 - 1):** Small break effect.  
  - **Moderate Punch (1 - 2):** Medium break effect.  
  - **Strong Punch (>2):** Large break effect with explosion force.  
- **🎨 Dynamic Environment:** Features immersive visuals, fog effects, and neon-styled aesthetics.
- **⚠️ Avoidable Obstacles:** Moving block obstacles add challenge, requiring players to dodge and stay agile.
- **📊 Scorekeeping System:**  
  - Points increase for successful hits and decrease for mistakes.  
  - Survive until the song ends to win the level.  

## 🛠️ Technologies Used
- **Unity** with **Meta’s XR SDK**
- **Physics-based interactions using C#**
- **OVRInput for controller velocity tracking**
- **Custom beat synchronization for object spawning**

This project delivers an **engaging, interactive VR rhythm experience** that combines music, motion, and reaction speed for an exciting challenge.

🚀 *Test it out and let me know what you think!*

## Local evaluation

Use the linked APK on the target headset, or open the linked Unity project with the editor version in its project settings. Check that the target timing, punch input, and score feedback work together. A source build requires the external project archive.
