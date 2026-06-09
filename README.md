# House Rent App (MERN Stack) - HouseHunt

A comprehensive, user-friendly MERN stack application designed to streamline the real estate journey by connecting renters, owners, and administrators.

---

## 🚀 How to Run the App in VS Code (English)

### 1. Prerequisites
- **Node.js**: Make sure Node.js is installed on your computer.
- **MongoDB**: Make sure MongoDB is installed locally and running (typically on `mongodb://localhost:27017`), or obtain a MongoDB Atlas connection string.
- **VS Code**: Install Visual Studio Code.

### 2. Open in VS Code
- Open **VS Code**.
- Go to `File` -> `Open Folder...` and select the `house-rent` directory:
  `C:\Users\navya\.gemini\antigravity\scratch\house-rent`

### 3. Environment Variables Config (.env)
We have already created a `.env` file inside the `backend` folder. It looks like this:
```env
PORT=8001
MONGO_DB=mongodb://localhost:27017/house-rent
JWT_KEY=house_rent_secret_jwt_key_2026
```
*(If you want to use MongoDB Atlas cloud database, replace `mongodb://localhost:27017/house-rent` with your Atlas URI).*

### 4. Running the Servers
You need to run both the backend and frontend servers simultaneously.

#### Step 4.1: Start Backend Server
1. Open a new terminal in VS Code (`Ctrl + ~` or Terminal -> New Terminal).
2. Go to the backend folder:
   ```bash
   cd backend
   ```
3. Start the server:
   ```bash
   npm start
   ```
   *(The server will start running on port `8001` and connect to MongoDB).*

#### Step 4.2: Start Frontend Server
1. Open a **second** terminal tab in VS Code.
2. Go to the frontend folder:
   ```bash
   cd frontend
   ```
3. Start the React app:
   ```bash
   npm start
   ```
   *(This will automatically open the app in your browser at `http://localhost:3000`).*

---

## 🚀 VS Code లో యాప్‌ను ఎలా రన్ చేయాలి (Telugu)

### 1. ముందుగా కావలసినవి (Prerequisites)
- **Node.js**: మీ కంప్యూటర్‌లో Node.js ఇన్‌స్టాల్ అయి ఉండాలి.
- **MongoDB**: మోంగోడిబి లోకల్‌గా రన్ అవుతూ ఉండాలి (`mongodb://localhost:27017`), లేదా మోంగోడిబి అట్లాస్ (MongoDB Atlas) కనెక్షన్ లింక్ ఉండాలి.
- **VS Code**: విజువల్ స్టూడియో కోడ్ ఇన్‌స్టాల్ చేసి ఉండాలి.

### 2. VS Code లో ఓపెన్ చేయండి
- **VS Code** ఓపెన్ చేయండి.
- `File` -> `Open Folder...` క్లిక్ చేసి `house-rent` ఫోల్డర్‌ను సెలెక్ట్ చేయండి:
  `C:\Users\navya\.gemini\antigravity\scratch\house-rent`

### 3. కన్ఫిగరేషన్ ఫైల్ (.env)
మేము ఇప్పటికే `backend` ఫోల్డర్ లోపల ఒక `.env` ఫైల్‌ను క్రియేట్ చేసాము. అందులో ఈ క్రింది విధంగా ఉంటుంది:
```env
PORT=8001
MONGO_DB=mongodb://localhost:27017/house-rent
JWT_KEY=house_rent_secret_jwt_key_2026
```
*(మీరు ఆన్‌లైన్/క్లౌడ్ డేటాబేస్ ఉపయోగించాలనుకుంటే, మోంగోడిబి అట్లాస్ లింక్‌ను ఇక్కడ MONGO_DB స్థానంలో పెట్టండి).*

### 4. సర్వర్‌లను రన్ చేయడం
యాప్‌ను రన్ చేయడానికి బ్యాకెండ్ మరియు ఫ్రంటెండ్ రెండింటినీ స్టార్ట్ చేయాలి.

#### స్టెప్ 4.1: బ్యాకెండ్ రన్ చేయండి
1. VS Code లో కొత్త టెర్మినల్ ఓపెన్ చేయండి (`Ctrl + ~` లేదా Terminal -> New Terminal).
2. `backend` ఫోల్డర్‌కు వెళ్ళండి:
   ```bash
   cd backend
   ```
3. సర్వర్ రన్ చేయండి:
   ```bash
   npm start
   ```
   *(సర్వర్ పోర్ట్ `8001` లో రన్ అవుతుంది మరియు డేటాబేస్‌కు కనెక్ట్ అవుతుంది).*

#### స్టెప్ 4.2: ఫ్రంటెండ్ రన్ చేయండి
1. VS Code లో **మరొక** కొత్త టెర్మినల్ ఓపెన్ చేయండి.
2. `frontend` ఫోల్డర్‌కు వెళ్ళండి:
   ```bash
   cd frontend
   ```
3. రియాక్ట్ యాప్‌ను రన్ చేయండి:
   ```bash
   npm start
   ```
   *(ఇది ఆటోమేటిక్‌గా బ్రౌజర్‌లో `http://localhost:3000` వద్ద ఓపెన్ అవుతుంది).*

---

## 📂 How to Upload to GitHub (గ్రీట్ హబ్ లో ఎలా అప్‌లోడ్ చేయాలి)

Follow these commands in the root `house-rent` folder:

1. Open terminal in the root directory:
   ```bash
   # Make sure you are in C:\Users\navya\.gemini\antigravity\scratch\house-rent
   ```
2. Initialize git repository:
   ```bash
   git init
   ```
3. Add all files to staging:
   ```bash
   git add .
   ```
4. Commit the changes:
   ```bash
   git commit -m "Initial commit - MERN House Rent app setup"
   ```
5. Create a new repository on your GitHub account (do not add README, license, or gitignore there).
6. Copy the repository link and run:
   ```bash
   git remote add origin <your-github-repo-link>
   git branch -M main
   git push -u origin main
   ```
