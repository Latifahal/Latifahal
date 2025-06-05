<div align="center"> 
  <h1> Hi! I'm <a href="https://github.com/Latifahal">Liv </a><img src="https://media.giphy.com/media/hvRJCLFzcasrR4ia7z/giphy.gif" width="25px"></h1>
</div>
<br />

  <mailto:liviaalbrecht@outlook.com>
    
<h2 align="center"> Projects </h2>
  &nbsp;
</div>
  <h3 align="center"><p>:arrow_down:</p><a href="https://latifahal.github.io/greenthumb.github.io/" name="GreenThumb">GreenThumb</a></h3>
  &nbsp;
  <div align="center"><div marign-bottom="10px"><kbd><img src="Screenshot from 2022-09-12 08-36-31.png" width="350" title="hover text" /></kbd></div>
  &nbsp;
  <div align="center"><kbd><img src="Screenshot from 2022-09-12 08-38-19.png" width="170" title="hover text" /></kbd>
  &nbsp;
  <kbd><img src="Screenshot from 2022-09-12 08-37-48.png" width="80" title="hover text" /></kbd></div>  
</div>
  &nbsp;
  
  <p align="center">:wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash::wavy_dash:</p>


  &nbsp;
 <h3 align="center">Garderoba App Intro 👕</h3>
  &nbsp;

[![Watch the video](https://img.youtube.com/vi/-5OaHI0zonk/maxresdefault.jpg)](https://youtu.be/-5OaHI0zonk)


<p> Garderoba is a mobile wardrobe management app built with React Native and Expo, designed to help users organize, add, and manage clothing items digitally. It includes user authentication, item creation, and profile management features.</p>

# 🚀 Features

- 🔐 **User Authentication** (Register / Login with Google)
- 👤 **Profile Management** (Update user details)
- 📸 **Create & Upload Items** (Add clothing items with photos)
- 📍 **Location Integration** (Context-aware functionality)
- 📄 **Terms & Conditions** screen
- 🧱 **Bottom Tab Navigation** across all screens

---

# 🧠 Tech Stack

- **React Native + Expo**
- **React Navigation**
- **Context API** (User, Location, Refresh)
- **Axios** for HTTP requests
- **Custom IP Resolver Utility** (`ip.js`)
- **Google OAuth** (Backend integration)
- **Android Emulator / Expo Go**

---

# 📸 Screens

- **Landing Page**
- **Login / Register**
- **Main Dashboard**
- **Create Item Screen**
- **User Profile**
- **Update Profile**
- **End Screen**

---

# 🛠️ Getting Started

> ⚠️ Note: This app has a separate backend server. Be sure to clone and run both projects.

```bash
### 1. Clone Both Frontend and Backend Repos

# Clone the frontend repo
git clone https://github.com/yourusername/garderoba.git
cd garderoba

# In a new terminal, clone the backend repo
cd ..
git clone https://github.com/yourusername/garderoba-backend.git

ttps://github.com/yourusername/garderoba-backend.git

### 2. Install Frontend Dependencies

cd garderoba
npm install

### 3. Install Backend Dependencies

cd ../garderoba-backend
npm install

### 4. Start the Backend Server
💡 Make sure the backend is running on port 9000:

npm start
5. Configure IP in ip.js (Frontend)
✏️ Go to utils/ip.js in the frontend and update the IP to match your local machine:

const currentIP = async () => {
  return "192.168.x.x"; // replace with your local IP
};
export default currentIP;
🔍 You can find your local IP by running:

# On Windows
ipconfig

# On macOS/Linux
ifconfig

### 6. Set Up Android Emulator
✅ Make sure you have:

Android Studio installed

A working AVD (Android Virtual Device)

adb configured in your system PATH

cd ~/AppData/Local/Android/Sdk/emulator
./emulator -avd Pixel_7

### 7. Run the Frontend App

cd garderoba
npx expo start
📲 Scan the QR code in Expo Go (on Android)
🖥️ Or press a to launch in the emulator

🧪 you might face those common Issues

- Emulator configuration may vary by OS and permissions
- Make sure port 9000 is open and backend server is running
- Ensure ip.js points to the correct backend IP

