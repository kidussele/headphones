# 🎧 headphones - Automatic Music Downloader for SABnzbd

[![Download headphones](https://img.shields.io/badge/Download-Headphones-blue?style=for-the-badge)](https://github.com/kidussele/headphones/releases)

---

## 📖 About headphones

headphones is an application designed to help you automatically find and download music through SABnzbd. SABnzbd is a tool that downloads files from Usenet, and headphones works alongside it to make sure your favorite music is collected without manual searching or downloading.

This app is built for users who want a simple way to gather music without spending time looking for each album or track. It runs quietly, scanning for new releases and sending download requests to SABnzbd. Whether you use a mobile device or desktop, headphones helps keep your music library up to date.

---

## 💻 System Requirements

Before you download headphones, make sure your device meets these basic needs:

- Operating System: Windows 7 or later, macOS 10.12 or later, or Linux distributions with Python support.
- Disk Space: At least 500 MB free for application files plus additional space for music.
- RAM: Minimum of 2 GB available memory.
- Software Dependencies: SABnzbd installed and running on your device or network.
- Internet Connection: Required to search for music and download files.

If you use SABnzbd on a separate computer or server, headphones must be able to connect to it on your local network.

---

## 🚀 Getting Started

Using headphones is easy. Follow these steps to set up and start your automatic music downloads.

### Step 1: Download headphones

Click the big download button at the top of this page or visit the [headphones releases page](https://github.com/kidussele/headphones/releases) to get the latest version.

The releases page contains all official versions. Look for the file that matches your operating system:

- For Windows, find a `.exe` or `.zip` file.
- For macOS, find a `.dmg` or `.zip` file.
- For Linux, you might find a source `.tar.gz` or binary package.

### Step 2: Install the software

- **Windows:** If you downloaded a `.exe` file, double-click it and follow the setup instructions. For a `.zip` file, extract the contents and run `headphones.exe`.
- **macOS:** Open the `.dmg` file and drag headphones to your Applications folder. If it is a `.zip`, extract and place headphones into Applications.
- **Linux:** Extract the archive if needed. Run headphones through terminal by navigating to the folder and starting the app with `./headphones`.

### Step 3: Configure headphones

When you first open headphones, it will ask for some settings:

- **SABnzbd connection details:** Enter the IP address and port where SABnzbd runs (for example, `http://localhost:8080`).
- **API Key:** This key allows headphones to talk with SABnzbd. You can find it in SABnzbd’s settings.
- **Music Sources:** Choose genres, artists, or albums you want headphones to look for.
- **Download folder:** Select where downloaded music files should be saved on your device.

### Step 4: Start automatic downloads

After configuration, headphones will begin checking for new music releases based on your preferences. It sends requests to SABnzbd, which downloads the files for you. You can monitor progress inside headphones or look for completed files in your chosen folder.

---

## 📂 How It Works

headphones connects with SABnzbd to automate music downloads using the following steps:

1. It searches for new music releases on Usenet and supported indexers.
2. When something matches your chosen artists or albums, headphones sends this request to SABnzbd.
3. SABnzbd downloads the files automatically in the background, handling complex tasks like repairing and unpacking music archives.
4. headphones checks the download status and can organize your music files into folders.

This process happens regularly, so your music library stays fresh without any extra effort.

---

## 🔧 Configuration Tips

Here are some tips to set up headphones for best results:

- **API Key Security:** Keep your SABnzbd API key private and do not share it online.
- **Network Settings:** Make sure headphones and SABnzbd are on the same network if running on different devices.
- **Indexers Setup:** Use reliable Usenet indexers in headphones for better music searching.
- **Download Folder:** Choose a folder with enough free space to store your music.
- **Schedule Checks:** Adjust how often headphones scans for new music based on your preferences and internet speed.

If you want to add or remove artists and albums, use the search and management features in the app.

---

## ⚙️ Troubleshooting

If you run into problems, try the following:

- **Unable to connect to SABnzbd:** Check the IP address, port, and API key in headphones.
- **No new music downloads:** Make sure you have added artists or albums to track.
- **Downloads stuck or fail:** Verify your internet connection and that SABnzbd is running without errors.
- **Missing files after downloads:** Check the SABnzbd download folder and headphones’ settings.

For detailed logs, headphones often has a logging function that can help identify issues.

---

## 📥 Download & Install

Visit the [headphones releases page](https://github.com/kidussele/headphones/releases) to download the latest version. You will find files for different operating systems.

Once downloaded, follow the installation steps for your device type as outlined in the Getting Started section. After install, open the app and follow the configuration guide to connect headphones to SABnzbd and start your automatic music downloads.

---

## 🙋 Contact & Support

For questions or help, check the GitHub repository Issues page or the community forums related to SABnzbd and music automation. Many users share setup tips and problem fixes that might help you.

The headphones repository is available at https://github.com/kidussele/headphones for updates and support.

---

## 🔖 Topics

- auto  
- mobile

---

This guide should help anyone with a basic computer setup get headphones up and running smoothly for automatic music downloads using SABnzbd.