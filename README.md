# **OGDev-SpeedSystem** 🚗💨  
**OGDev-SpeedSystem** is a **custom speed enforcement system** designed to regulate vehicle speeds in specific zones while allowing players to set their own speed limits. This script **prevents players from removing the limit inside restricted zones**, ensuring realistic and immersive gameplay.  


📌 **Join our official Discord for support & updates:** **[Click Here](https://discord.gg/uzVkdfK7Qm)**  

---

## **📌 Features**  
✅ **Speed Zone Enforcement** – Automatically applies a speed limit when entering predefined zones.  
✅ **Manual Speed Limit** – Players can manually set a speed cap for their vehicle.  
✅ **Speed Limit Locking** – Prevents players from removing the limit while inside a speed zone.  
✅ **MPH/KPH Toggle** – Configurable speed units based on preference.  
✅ **Real-Time Speed Adjustment** – Actively limits vehicle speed to prevent exceeding the set threshold.  

---

## **📜 Commands**  

| Command | Description | Usage |  
|---------|------------|--------|  
| `/limitspeed [speed]` | Sets the vehicle’s speed limit. | `/limitspeed 60` (Limits to 60 MPH/KPH) |  
| `/limitspeed` | Removes the speed limit (if outside a speed zone). | `/limitspeed` |  

### **⚠ Restrictions:**  
- You **cannot remove the speed limit** while inside a designated speed zone.  
- The **speed unit (MPH or KPH)** is configurable in the settings.  

### **🔹 Example Command Usage:**  
✅ `/limitspeed 80` → Sets speed limit to **80 MPH/KPH**  
✅ `/limitspeed` → Removes speed limit (if outside a speed zone)  

---

## **⚠ WARNING: DO NOT USE THE "LUMEN-STUDIOS" VERSION**  
### ❌ **The stolen version of this script (Lumen-SpeedSystem) contains hidden malware.**  

🚨 **The Truth Behind the Scam:**  
- I originally wrote this script but **lost access to my old GitHub account**.  
- After creating a new account and re-uploading my work, I discovered that **someone had stolen my script and uploaded it under a different name**.  
- **Even though their repository has an earlier upload date, that’s because my original account was lost.**  
- **Their version includes hidden malware** that could allow backdoor access to your server, steal sensitive data, or execute malicious commands.  

🔹 **How to Check for Malware**  
If you accidentally installed the "Lumen-SpeedSystem" version, follow these steps:  
1. **Search your server files** for any suspicious `.lua` or `.dll` files.  
2. **Look for obfuscated code** (random characters, base64 encoding).  
3. **Monitor server logs** for unusual activity (unauthorized commands or IP connections).  
4. **Completely remove the stolen script** and replace it with **OGDev-SpeedSystem** from the official source.  

---

## **⚙️ How It Works**  

### **🚧 Speed Zone Enforcement**  
- When a player **enters a speed zone**, their vehicle is **automatically limited** to the preset speed.  
- Exiting the zone removes the limit **unless** the player has manually set a limit.  

### **🛠 Manual Speed Limit**  
- Players can use `/limitspeed [speed]` to **set a personal speed limit**.  
- This overrides the zone speed **until they enter another zone**.  

### **⏳ Speed Limit Enforcement**  
- If the vehicle **exceeds the allowed speed**, the script **gradually reduces velocity** to stay within limits.  
- Players cannot bypass this restriction while inside a zone.  

---

## **📂 Installation Guide**  

### **1️⃣ Download & Install**  
1. **Download the official version** of **OGDev-SpeedSystem** from **OGDev Studios' repository** (*not from Lumen Studios*).  
2. Extract and rename the folder to **`OGDev-SpeedSystem`**.  
3. Move it to your FiveM **resources folder** (`server-data/resources/`).  

### **2️⃣ Add to Server Config**  
Open **server.cfg** and add:  
```ini
ensure OGDev-SpeedSystem
```

---

## **🚀 Troubleshooting & FAQs**  

### **🚗 Speed Limit Not Working?**  
✅ Ensure **OGDev-SpeedSystem** is installed correctly.  
✅ Check if the vehicle speed limit is set (`/limitspeed [speed]`).  
✅ Restart the server and test again.  

### **⚠ Can’t Remove Speed Limit?**  
✅ You **cannot** remove the speed limit while inside a **speed zone** (this is intentional).  
✅ Exit the zone first, then run `/limitspeed`.  

### **🌍 Want Custom Speed Zones?**  
✅ Edit the **speed zone configuration file** to add new areas.  
✅ Customize limits based on server preferences.  

---

## **📢 Credits & Legal Notice**  
👤 **Original Developer:** **OGDev Studios**
🔗 **Official Repository:** *[Click Here](https://github.com/SheLovesLqwid/OGDev-SpeedSystem)*  

⚠ **This script was stolen and falsely claimed by "Lumen Studios."**  

### 🚨 **How to Protect Yourself:**  
- **Only download from OGDev Studios' official GitHub.**  
- **Report the stolen repository if you see it.**  

---

### **Final Message**  
I appreciate the support from the FiveM community in fighting against stolen and malicious scripts. If you have any questions or concerns about the legitimacy of this script, feel free to reach out.  

📌 **Join our official Discord for support & updates:** **[Our Discord](https://discord.gg/uzVkdfK7Qm)**  

**Let’s keep FiveM development clean, fair, and secure!** 🔥🚀  
