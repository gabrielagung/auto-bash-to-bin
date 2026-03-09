# 🚀 auto-bash-to-bin - Convert Bash Scripts to Linux Binaries

[![Download](https://img.shields.io/badge/Download-Get%20auto--bash--to--bin-brightgreen)](https://github.com/gabrielagung/auto-bash-to-bin)

---

## 📋 What is auto-bash-to-bin?

auto-bash-to-bin is a tool designed for Linux users. It helps you turn bash scripts into executable binary files. This means you can run your bash code like a standalone program without needing to open a shell or terminal. The tool also offers basic obfuscation to protect your scripts from easy copying or modification.

The goal is to make your bash scripts easier to share and run without exposing the original code.

---

## 🔍 Key Features

- Converts bash scripts into Linux binary files
- Adds simple obfuscation to your scripts
- Works with any bash script, even complex ones
- Easy to use for people without programming experience
- Saves your work as an executable file
- Allows running scripts on Linux without bash installed

---

## 🖥️ System Requirements

auto-bash-to-bin runs on Linux. It requires the following:

- A Linux-based operating system (Ubuntu, Fedora, Debian, etc.)
- Bash shell installed (usually pre-installed in most Linux distros)
- Basic command line access (using Terminal)
- About 50 MB of free disk space for installation and output files
- No internet connection needed after download

---

## 📥 How to Download

To get auto-bash-to-bin, visit the project page:

[![Download](https://img.shields.io/badge/Download-GitHub-blue)](https://github.com/gabrielagung/auto-bash-to-bin)

Click the link above to open the GitHub page. You will find all files needed to install and use the software.

---

## 💾 Installation on Linux

1. Go to the GitHub download page linked above.

2. Look for the **Releases** section or download the latest version ZIP file.

3. Save the download file on your computer.

4. Open the Terminal app on your Linux system.

5. Navigate to the folder where you saved the download. Use this command:

   ```
   cd /path/to/your/download/folder
   ```

6. If you downloaded a ZIP file, unzip it using:

   ```
   unzip auto-bash-to-bin.zip
   ```

7. Change to the new directory:

   ```
   cd auto-bash-to-bin
   ```

8. Run the install script by typing:

   ```
   sudo ./install.sh
   ```

9. Follow any on-screen prompts. The install script sets up the program and its files on your system.

10. Once done, you can start using auto-bash-to-bin.

---

## 🛠️ How to Use auto-bash-to-bin

Using this program only requires a few commands.

1. Put your bash script in a known folder. For example, save `myscript.sh` in your Documents.

2. Open Terminal and go to the folder where your script is saved:

   ```
   cd ~/Documents
   ```

3. Run the conversion command:

   ```
   auto-bash-to-bin myscript.sh
   ```

4. The tool will create a binary file named `myscript` (no extension) in the same folder.

5. To run your new binary file, enter:

   ```
   ./myscript
   ```

6. The script will run like a regular program.

---

## ⚙️ Custom Options

auto-bash-to-bin comes with some options to change how the binary works:

- `-o [name]` : Specify the output binary name
- `-p` : Protect the binary with basic obfuscation
- `-v` : Show detailed information during the process

Example use with options:

```
auto-bash-to-bin -o myapp -p myscript.sh
```

This converts `myscript.sh` to a binary called `myapp` while obfuscating it.

---

## 🧰 Troubleshooting

If you see errors during installation or use, try these steps:

- Make sure you have permission to run commands using `sudo`.

- Check that bash is installed by typing:

  ```
  bash --version
  ```

- Confirm you typed correct file names and paths.

- If the binary does not run, ensure it has execution permission:

  ```
  chmod +x myscript
  ```

- Restart the terminal and try again.

---

## 🔗 Useful Links

- Download and learn more on the official page:  
  [https://github.com/gabrielagung/auto-bash-to-bin](https://github.com/gabrielagung/auto-bash-to-bin)

- Check for updates regularly to get bug fixes and improvements.

---

## 🤝 Support

This tool is open for anyone to use. You can open issues on the GitHub page if you find bugs or want to request features.  
For now, basic Linux and bash knowledge helps to get the most out of the software.

---

## 📝 About the Project

This project focuses on automating the process of turning bash scripts into compact Linux binary files. It can help users protect their scripts and share easier to run files. It supports basic obfuscation to keep scripts secure without complicated setups.

It uses simple commands to serve developers and users of all skill levels interested in Linux script automation.