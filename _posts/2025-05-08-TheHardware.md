---
layout: post
title: "🖥️ My Homelab Setup: What's Running Behind the Scenes Part 1: The Hardware"
author: "Samundra Bajracharya"
categories: journal
tags: [documentation,sample]
image: cutting.jpg
---

Hey tech enthusiasts! I'm back with the third installment of my homelab series, where today we'll dig into the hardware powering my digital playground.

But first, let's address something important: the most valuable component of any homelab isn't the shiny equipment—it's the ideas you want to execute on them.

Many aspiring homelabbers get caught in the trap of thinking they need enterprise-grade equipment to start. The truth? You can begin your journey with practically anything:

- That old laptop collecting dust in your drawer
- A humble Raspberry Pi sitting on your shelf
- A retired enterprise server (if you're lucky enough to snag one)
- Or in my case, even an Android TV box an ISP didn't want back!

The beauty of homelabbing lies in creativity and problem-solving, not spending thousands on equipment. It's about squeezing every ounce of potential from whatever hardware you have access to.

## 🤖 From Android TV Box to Linux Server

My homelab journey began with an unexpected gift: an Android TV box that my ISP didn't bother collecting after I switched providers. Looking at this seemingly limited device, a thought struck me—Android is just Linux under the hood, so why couldn't I run a proper Linux distro on it?

The box ran on an ancient Rockchip processor, which presented numerous challenges. I had to implement various workarounds, dive deep into ARM architecture peculiarities, and get creative with limited resources. But eventually, I transformed this castaway device into my first functioning server!

This experience taught me something valuable: limitations breed innovation. Working within tight hardware constraints forces you to optimize in ways you might never discover with high-end equipment.

## 🖥️ My Current Hardware Setup

### Main Homelab Server

**Dell Optiplex 3050 (Mini Form Factor)**

- 🧠 CPU: Intel(R) Core(TM) i5-6500 CPU @ 3.20GHz
- 🧮 RAM: 16 GB
- 💾 Storage: 256GB SSD + 1TB HDD

This refurbished business PC has become the cornerstone of my homelab. Its small footprint means it tucks away neatly while hosting most of my containers and services. Business machines like these are homelab gold—reliable, energy-efficient, and often available at great prices on the secondary market.

### AI Workstation & Gaming/Work PC

- 🧠 CPU: AMD Ryzen 7 3700X
- 🧮 RAM: 16GB
- 💾 Storage: 256GB NVMe SSD + 256GB SSD + 1 TB HDD
- 🎮 GPU: Nvidia RTX 3060 OC 12GB

This system pulls double-duty as my daily driver for work and gaming, but also handles my more GPU-intensive homelab experiments. The RTX 3060 with 12GB VRAM makes it perfect for running local AI models and handling visualization tasks that would overwhelm the Optiplex.

### IoT & Home Automation Fleet

- 📡 Various ESP32 and ESP8266 devices

These incredible little microcontrollers are scattered throughout my home, handling everything from environmental monitoring to home automation tasks. They're the perfect example of how powerful modern computing can be at even the smallest scale.

## 🔄 Evolution, Not Revolution

My hardware setup wasn't built overnight—it evolved gradually based on specific needs and opportunities. The Android TV box taught me ARM Linux, the Optiplex gave me virtualization capabilities, and the ESP devices opened the door to physical computing and IoT.

Each component entered my homelab when I had a specific problem to solve or project to tackle. This organic growth approach kept costs reasonable while ensuring every piece of hardware earned its space.

## 🚀 Getting Started With What You Have

If you're hesitating to start your homelab because you don't have "proper" equipment, take this as your sign to begin anyway! Some suggestions:

- **Old laptops** make excellent starter servers with built-in UPS (the battery!)
- **Mini PCs and NUCs** offer surprising power in tiny, energy-efficient packages
- **Repurposed business desktops** (like my Optiplex) provide enterprise reliability on a budget
- **Single-board computers** teach valuable lessons about resource optimization

## 🔮 What's Next?

As my projects grow more complex, I'm contemplating adding a dedicated NAS for centralized storage. But for now, I'm focused on maximizing what I have—constantly finding new ways to distribute workloads efficiently across my modest hardware collection.

In my next post, I'll dive deeper into how I've configured the software stack on my Optiplex to handle diverse workloads despite its limited resources. There's something magical about coaxing enterprise-grade performance from consumer hardware!

What unexpected devices have you repurposed for your homelab? Share your creative hardware solutions in the comments!

_#HomeLab #BudgetTech #Repurposing #DIYServer #TechRecycling #SelfHosted_