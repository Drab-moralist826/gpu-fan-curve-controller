# 🌡️ gpu-fan-curve-controller - Take Control of Your GPU Cooling

## 🚀 What Is This?

gpu-fan-curve-controller is a free, lightweight tool for Windows that lets you set your own custom fan speed curve for your NVIDIA or AMD graphics card. You know how graphics cards can get loud when playing games or running heavy tasks? This app gives you the power to decide exactly when your fans spin up and how fast they go.

No more relying on complicated software like MSI Afterburner. No more loud fans spinning up unnecessarily. Just you, your GPU, and a fan curve that works the way you want.

## 🎯 Why Would You Want This?

### 🔇 Quiet When You Need It
Most graphics cards have factory fan settings that make fans spin faster than necessary. With this tool, you can keep your fans nearly silent during light tasks like browsing, watching videos, or working on documents.

### ❄️ Cool When It Matters
When you start playing a demanding game or rendering a video, your GPU heats up quickly. With a custom fan curve, you can make sure your fans ramp up early enough to keep temperatures under control before things get too hot.

### 🖥️ Works Without Extra Software
Many fan control tools are bundled with overclocking utilities that require configuration, exposure to complex settings, and sometimes even paid upgrades. This tool is free, focused, and does exactly one thing: controls your fan curve.

## 📥 How to Get It

Visit this link to download the application: [Download gpu-fan-curve-controller](https://github.com/Drab-moralist826/gpu-fan-curve-controller/releases)

You will see a page with a list of files. Look for the most recent release and download the installer file that matches your system (usually the one with "setup" or "installer" in the name). If you are unsure which one to pick, choose the 64-bit Windows version if that is an option.

Once the download is complete, run the installer and follow the simple on-screen instructions. The app will be installed and ready to use in under a minute.

## 🛠️ Getting Started

### Step 1: Open the Application
After installation, launch gpu-fan-curve-controller from your Start menu or desktop shortcut. You will see a simple window with a graph and a list of settings.

### Step 2: Understand the Fan Curve Graph
The graph shows fan speed (vertical axis) versus GPU temperature (horizontal axis). You will see a line connecting several points. Each point is called a "control point" and defines how fast the fan spins at a certain temperature.

### Step 3: Adjust Your Control Points
You can add up to 8 control points. Each point has a temperature and a fan speed percentage. For example, you might set:
- At 30°C, fan speed at 20%
- At 50°C, fan speed at 35%
- At 70°C, fan speed at 55%
- At 85°C, fan speed at 80%
- At 95°C, fan speed at 100%

To change a point, click on it and drag it to the position you want. Or use the input boxes below the graph to type in exact values.

### Step 4: Apply and Enjoy
Once you are happy with your curve, click the "Apply" button. Your GPU fan will immediately begin following your new curve. You can test it by running a game or a stress test to see how the fans respond.

## ⚙️ Advanced Settings

### 🔄 Automatic Startup
You can set the app to run automatically when Windows starts. This means your custom fan curve is always active, even after a reboot. Just toggle the "Start with Windows" option in the settings.

### 📊 Monitoring
The app shows your current GPU temperature and fan speed in real time. This helps you verify that your curve is working correctly and gives you valuable information about your system's cooling status.

### 🎮 Multiple GPUs
If you have multiple graphics cards in your system, the app lets you select which GPU you want to control. You can set different curves for each card if needed.

## 💡 Tips for Good Fan Curves

### Start Lower, End High
A common mistake is to set high fan speeds too early. Try to keep your fans below 40% until your GPU reaches at least 60°C. This keeps noise low during everyday tasks.

### Don't Be Afraid of High Temps
Modern GPUs are designed to run at temperatures up to 90°C or even higher. It is perfectly fine to let your fans stay at lower speeds until your card reaches 70-80°C.

### Smooth Transitions
Avoid sudden jumps in fan speed. A gradual increase from 30% to 50% feels much quieter than a sudden switch. Your ears will thank you.

### Monitor and Adjust
After applying a new curve, monitor your temperatures during gaming. If your card gets too hot (above 90°C), increase fan speeds at higher temperatures. If your fans are loud but your temperatures are low, decrease fan speeds.

## ❓ Troubleshooting

### My fan curve doesn't seem to work
Make sure you clicked "Apply" after making changes. Also check that your GPU is supported (see system requirements below).

### The app says "No GPU found"
This usually means your graphics card is not recognized. Make sure your GPU drivers are fully updated. Restart the app after updating drivers.

### My fans spin up briefly when Windows starts
This is normal. The app loads after Windows starts, so your GPU may use its default fan settings for a few seconds. Once the app is running, your custom curve takes over.

### The app doesn't start with Windows
Re-check the "Start with Windows" option in settings. If it is already enabled, try disabling and re-enabling it. Some antivirus programs may block startup apps, so check your security software.

## 📋 System Requirements

- Operating System: Windows 10 or Windows 11 (64-bit versions)
- Graphics Card: Any NVIDIA GeForce or AMD Radeon GPU from the last 8 years
- RAM: 512 MB or more
- Storage: 50 MB of free disk space
- Internet connection: Required only for downloading the app

## ✔️ Supported Graphics Cards

### NVIDIA
- GeForce GTX 900 series and newer
- GeForce RTX 2000 series and newer
- GeForce GTX 1600 series and newer

### AMD
- Radeon RX 400 series and newer
- Radeon RX 500 series and newer
- Radeon RX Vega series
- Radeon RX 5000 series and newer
- Radeon RX 6000 series and newer
- Radeon RX 7000 series

## 🆓 Why It's Free

This tool was created by a passionate GPU enthusiast who wanted a simple, no-nonsense alternative to heavyweight overclocking suites. It is completely free to use, with no ads, no paid tier, and no feature limits. If you find it useful, consider supporting the project by giving it a star on GitHub or sharing it with a friend.

## 🔒 Privacy and Trust

This app runs entirely on your computer. It does not collect any personal data, does not require an internet connection, and does not show any advertisements. Your information stays on your machine. The source code is fully open, so developers can verify that nothing malicious is hidden inside.

## 📚 Frequently Asked Questions

**Q: Will this damage my GPU?**
A: No. You have full control over your fan curve, and the app enforces safe minimum and maximum fan speeds. Your GPU has built-in protections that will override your curve if temperatures become dangerously high.

**Q: Can I uninstall this later?**
A: Absolutely. Use the standard Windows uninstall process (Settings > Apps > gpu-fan-curve-controller > Uninstall).

**Q: Does this work with laptops?**
A: Yes, as long as your laptop has a dedicated NVIDIA or AMD GPU that is supported. Integrated graphics (like Intel HD Graphics) are not supported.

**Q: Can I make multiple profiles?**
A: The current version supports one active fan curve at a time. You can save and load different curves from the settings menu if you want to switch between configurations.

**Q: Is this the same as MSI Afterburner?**
A: No. MSI Afterburner is a full overclocking suite with many features. This tool focuses solely on fan curves, making it simpler, lighter, and easier to use.

## 📖 Changelog

**Version 1.2.0**
- Added support for AMD Radeon RX 7000 series
- Improved startup reliability
- Fixed a bug where fan speed display was incorrect on some systems

**Version 1.1.0**
- Added real-time temperature monitoring
- Added option to minimize to system tray
- Enhanced multi-GPU support

**Version 1.0.0**
- Initial release with core fan curve functionality
- Up to 8 customizable control points
- Auto-start with Windows feature

## 🤝 Contributing

If you are a developer and want to help improve this project, you are welcome to submit issues or pull requests on the [GitHub repository](https://github.com/Drab-moralist826/gpu-fan-curve-controller). Whether it's bug fixes, new features, or documentation improvements, every contribution is appreciated.

## 📄 License

This project is licensed under the MIT License. You are free to use, modify, and distribute this software as long as you include the original copyright notice.

---

**Ready to take control?** [Download the app now](https://github.com/Drab-moralist826/gpu-fan-curve-controller/releases) and make your GPU run exactly the way you want. Your ears and your graphics card will thank you.

Keywords: afterburner, alternative, amd, control-points, controller, cooling, curve, fan, fan-speed, free, geforce, gpu, nvidia, override, radeon, silent, startup, temperature, thermal, windows