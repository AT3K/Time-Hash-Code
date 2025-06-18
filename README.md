# 🚀 Time Hash Code (THC)

[![Codacy Badge](https://app.codacy.com/project/badge/Grade/16012cb426db4d91ba48b4bd484d117a)](https://app.codacy.com/gh/AT3K/Time-Hash-Code/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)

## ❓ What is THC?  

**Time Hash Code (THC)** is an Apple Shortcut designed to quickly generate unique IDs based on the current date and time. It uses the **MD5 hashing algorithm** to create these IDs.  

---

## ⚙️ How Does THC Work?

1. 🕒 **Capture Current Date and Time:** THC records the precise current date and time.  
2. 🔑 **Generate MD5 Hash:** It creates an MD5 hash from this date and time.  
3. 🆔 **Extract Unique ID:** The first 10 digits of the hash are used as the unique ID.  

---

## 💡 Use Cases

Use this unique ID in various scenarios, such as:

- 📂 Creating database records  
- 📜 Logging events  
- 🖇️ Naming files uniquely  
- 👤 Generating usernames  

*💡 Tip:* Don’t like the generated ID? Simply wait a second and try again for a new one!  

---

## 🛠️ How to Set Up THC

Follow these steps to set up THC on your iPhone:

1. **📥 Import the Shortcut:**  
   Go to the **Releases** section of this repository to find the download link for the shortcut. Once downloaded, add it to your Siri Shortcuts app.  

2. **🎛️ Set Up Action Button (Optional):**  
   If your iPhone has an Action Button, configure it for quick access:  
   - Go to **Settings → Action Button → Shortcut → Time Hash Code (THC) v1.0.1**  

---

## ✨ Customizing the Length of the ID  

You can configure the number of characters for the generated unique ID. By default, THC generates a 10-character ID, but you can customize this up to a maximum of **32 characters**.  

To adjust the length:

1. Open **Shortcuts**.  
2. Find **Time Hash Code (THC)**.  
3. **Hold** the shortcut and select **Edit**.  
4. Scroll down to the comment that says:  
   **‘Change the "10" below if you want a longer string. Maximum is 32.’**  
5. Modify the **"10"** to your desired length (between 10 and 32 characters).

---

🎉 Enjoy the simplicity and functionality of **Time Hash Code (THC)**!  
