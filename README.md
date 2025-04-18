<div align="center">
   <a href="https://github.com/coffinxp/loxs">
      <img src="https://github.com/user-attachments/assets/9fadee1e-a33c-46e3-9eca-c04aa47a443e" height="225" width="450"/>
   </a>
</div>

<br>

<div align="center">

| **🔍 Loxs** | **🛡️ Multi Vulnerability Scanner** | **🌐 for Web Applications**                |
| ----------- | ----------------------------------- | ------------------------------------------ |
| `L`         | =                                   | Local File Inclusion (LFI)                 |
| `O`         | =                                   | Open Redirection (OR)                      |
| `X`         | =                                   | Cross-Site Scripting (XSS)                 |
| `S`         | =                                   | SQL Injection (SQLi)                       |
|             |                                     | Carriage Return Line Feed Injection (CRLF) |

> **Loxs** is a powerful and user-friendly tool for identifying common web vulnerabilities such as `LFI`, `OR`, `SQLi`, `XSS`, and `CRLF`.\
> 👨‍💻 **Created by:** [`AnonKryptiQuz`](https://github.com/AnonKryptiQuz) × [`Coffinxp`](https://github.com/coffinxp) × [`HexShad0w`](https://github.com/HexShad0w) × [`Naho`](https://github.com/Naho666) × [`1hehaq`](https://github.com/1hehaq) × [`Hghost010`](https://github.com/Hghost0x00) × [`adperem`](https://github.com/adperem)

---

## 🚀 Features

| Feature                     | Description                                                         |
| --------------------------- | ------------------------------------------------------------------- |
| 🗂️ `LFI Scanner`           | Detects Local File Inclusion vulnerabilities.                       |
| 🔀 `OR Scanner`             | Identifies Open Redirect vulnerabilities.                           |
| 💉 `SQLi Scanner`           | Detects SQL Injection vulnerabilities.                              |
| 🧬 `XSS Scanner`            | Identifies Cross-Site Scripting vulnerabilities.                    |
| 🧾 `CRLF Scanner`           | Detects Carriage Return Line Feed Injection vulnerabilities.        |
| ⚡ `Multi-threaded Scanning` | Boosts performance with concurrent requests.                        |
| 🧰 `Customizable Payloads`  | Easily adapt payloads for different environments or specific needs. |
| 🧠 `Success Criteria`       | Configure patterns that determine successful exploitation.          |
| 💻 `User-friendly CLI`      | Clean, intuitive command-line interface.                            |
| 💾 `Save Vulnerable URLs`   | Option to store results for future reference.                       |
| 📊 `HTML Report Generation` | Automatically creates a detailed report in HTML format.             |

---

## 📦 Supported Environment

| Language    | Packages                                                                                                                                       |
| ----------- | ---------------------------------------------------------------------------------------------------------------------------------------------- |
| 🐍 Python 3 | `webdriver_manager`, `selenium`, `aiohttp`, `beautifulsoup4`, `colorama`, `rich`, `requests`, `gitpython`, `prompt_toolkit`, `pyyaml`, `flask` |

---

## ⚙️ Installation

### 1. 📥 Clone the Repository

```bash
git clone https://github.com/coffinxp/loxs.git
cd loxs
```

### 2. 📦 Install Dependencies

```bash
pip3 install -r requirements.txt
```

### 3. ▶️ Run the Tool

```bash
python3 loxs.py
```

---

## 🌐 Chrome & ChromeDriver Setup

### 🧩 Install Google Chrome

```bash
wget https://dl.google.com/linux/direct/google-chrome-stable_current_amd64.deb
sudo dpkg -i google-chrome-stable_current_amd64.deb
sudo apt -f install
```

### 🧰 Install ChromeDriver

```bash
wget https://storage.googleapis.com/chrome-for-testing-public/128.0.6613.119/linux64/chromedriver-linux64.zip
unzip chromedriver-linux64.zip
cd chromedriver-linux64
sudo mv chromedriver /usr/bin
```

---

## 🕵️ Tor Installation on Kali Linux

Tor can help anonymize your scanning activities.

### 1️⃣ Update Your System

```bash
sudo apt update && sudo apt upgrade -y
```

### 2️⃣ Install Tor

```bash
sudo apt install tor -y
```

### 3️⃣ Enable and Start Tor Service

```bash
sudo systemctl enable tor
sudo systemctl start tor
```

### 4️⃣ Verify Tor is Working

```bash
curl --socks5 127.0.0.1:9050 https://check.torproject.org/
```

You should see a message like: **"🎉 Congratulations. This browser is configured to use Tor."**

### 5️⃣ (Optional) Edit Configuration

```bash
sudo nano /etc/tor/torrc
```

Then restart:

```bash
sudo systemctl restart tor
```

---

## 🧪 Usage Options

| Option                         | Description                                                 |
| ------------------------------ | ----------------------------------------------------------- |
| 🔗 Input URL/File              | Provide a single URL or a file containing multiple targets. |
| 🧨 Payload File                | Use or create custom payloads for specific scanning needs.  |
| ✅ Success Criteria             | Define success indicators for different exploit types.      |
| 🚀 Concurrent Threads          | Configure the number of parallel requests.                  |
| 📋 Real-time and Saved Results | Display ongoing findings and save final results to file.    |

---

## 🛠️ Customization

| Customization Feature     | Description                                                    |
| ------------------------- | -------------------------------------------------------------- |
| ✏️ Payload Configuration  | Customize or add new payloads for various scan types.          |
| 🎯 Success Pattern Tuning | Modify success conditions based on the application under test. |
| ⚙️ Thread Optimization    | Improve performance by setting appropriate concurrency levels. |

---

> ⚠️ **Disclaimer:** This tool is intended solely for educational and authorized security testing. Unauthorized usage on systems you do not own or have explicit permission to test is strictly prohibited.

<br>

<p align="center">
<img src="https://github.com/user-attachments/assets/9ec3fed0-45ff-4cb3-988c-f8cd66e85082">
</p>


<br>




