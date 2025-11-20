# Sub2Me Pls

Sub2Me Pls is a lightweight, single-file web application designed to help creators grow their YouTube channels through a discovery-based subscription system. Users can explore new channels, watch videos, share feedback, and support the creators that genuinely match their interests — all while earning in-app coins for participation.

Everything runs inside one self-contained `index.html` file. No build tools. No complex folder structures. Just a compact, portable project you can open or host anywhere.

---

## ✨ Overview

This project blends:

- **Firebase Web SDK** (loaded via CDN)  
- **YouTube Data API integration**  
- **User authentication** (email, username, Google sign-in/linking)  
- **Coins & campaign system**  
- **Viewer feedback prompts**  
- **Optional anti-abuse protections**  
- **Simple, expandable UI logic**  

The goal is to create a platform where users naturally discover content they enjoy — not just subscribe blindly — while still giving creators a fair way to grow.

---

## 🎯 Key Features

### 📌 One-File Architecture  
The entire app — HTML, CSS, JavaScript, Firebase setup, API calls — is bundled into a single page.  
Easy to host, easy to modify.

### 🔐 Flexible Login Options  
Users can sign in using:
- Email + password  
- Username + password  
- Google account  
- Google-to-email account linking  

### 💰 Coin System  
Users earn coins by:
- Watching campaigns  
- Providing feedback  
- Completing mini-games (expandable)  

Coins can then be used to launch their own subscriber campaigns.

### 📺 Content Discovery  
After watching a video, users can answer:
- Did this match your interests?  
- How well did it fit your vibe?  
- What could have been better?  

Simple, direct feedback leads to more meaningful recommendations.

### 🚫 Abuse Prevention (Expandable)  
Includes a framework for:
- Warning unsubscribers  
- Temporary cooldowns  
- Permanent bans for repeat offenders  
- Optional IP/VPN detection (to be implemented responsibly)

This system is designed to encourage genuine engagement — not forced or artificial numbers.

---

## 🛠️ Installation & Hosting

Because everything is in one file, setup is simple:

1. Download or clone this repository.  
2. Open `index.html` in your browser to run it locally.  
3. Host it anywhere that accepts static files, including:
   - GitHub Pages  
   - Vercel  
   - Netlify  
   - Render  
   - Any static hosting provider  

No special build process or CLI required.

---

## 🧩 Customization & Improvements

You are absolutely welcome to:

- Improve the layout or UI  
- Add animations or themes  
- Enhance the feedback system  
- Implement stronger safety tools  
- Create new mini-games  
- Expand Firebase services  
- Clean or reorganize the logic  

This project is intentionally simple so it can grow in any direction.  
If you can make it better, please do — future users will thank you (probably).

---

## 🤝 Contributions

Contributions from collaborators are encouraged and appreciated.  
All pull requests will be reviewed, and constructive changes are always welcome.

Please avoid adding anything malicious, exploitative, spammy, or harmful.  
This platform should empower creators — not abuse YouTube, users, or anyone’s time.

---

## 🐞 Reporting Issues

If you encounter bugs, unexpected behavior, or areas for improvement, feel free to open an issue.  
Clear reports help the project grow stronger and smoother over time.

---

## 📜 License

Free to use, modify, and improve.  
Please keep enhancements respectful, secure, and aligned with the project’s purpose.  

A little creativity is always welcome — just nothing that sets off alarm bells.
