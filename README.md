# ARehman's Dispatcher Tool

## 📌 Overview
A simple web-based tool to help truck dispatchers quickly **parse and organize raw load board text** into a clean, structured format.  
Built with **HTML, CSS, and JavaScript**, it runs entirely in the browser with no setup required.

## 🚀 Features
- Paste raw load text directly from load boards (e.g., DAT).
- Automatically extracts key details:  
  - Price (or `-` if missing)  
  - Miles  
  - Deadhead (dh)  
  - Pickup (PU) & Delivery (Del) locations  
  - Weight (shown as `weight= ...`)  
  - Length & Type (e.g., `17 ft - Partial`)  
  - Broker Contact (email or phone, if available)  
- Generates a dispatcher-friendly formatted load instantly.
- **Copy Output** button copies the organized load, even without clicking format.
- **Side-by-side view**: raw load on the left, formatted output on the right.

## 🛠️ Tech Stack
- **HTML** — structure  
- **CSS** — styling & layout (grid for side-by-side view)  
- **JavaScript** — parsing, extracting, and formatting logic

## 📖 Usage
1. Open the tool in your browser.  
2. Paste a raw load text into the left textarea.  
3. Click **Format** (or directly **Copy Output**) to get the structured version.  
4. The organized load appears on the right panel, ready to copy or use.

## 📌 Example Output
```
$1,111
Mile=1143
dh=(144)
PU=Augusta,GA--
Del=Cheney,KS--

COM=
weight= 3000 lbs
17 ft - Partial

Broker Name:
Broker Contact: jgartner@warnert.com
Broker MC:
```

## 🤝 Contribution
Contributions, issues, and feature requests are welcome!  
Feel free to fork the repo and submit pull requests.

## 📄 License
This project is open source and available under the **MIT License**.
