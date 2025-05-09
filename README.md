# 🐾 Pokemon-Apps
Selamat datang di Pokemon-Apps! Proyek ini merupakan implementasi sederhana namun powerful dari React menggunakan konsep useReducer untuk manajemen state. Cocok bagi Anda yang ingin mempelajari React lebih dalam dengan pola state management yang rapi dan scalable.


![Screenshot 2025-05-09 223829](https://github.com/user-attachments/assets/bd097e12-0326-4fa4-92b3-4fed237a70ee)

![Screenshot 2025-05-09 223845](https://github.com/user-attachments/assets/0f178a7e-0405-4b1a-8fba-aa15e80945c7)

![Screenshot 2025-05-09 223858](https://github.com/user-attachments/assets/b3efcc59-82b0-499f-b925-53869ea9c405)




# ⚙️ Fitur Utama
⚛️ ReactJS — Library frontend paling populer di dunia.

🧠 useReducer Hook — Manajemen state yang lebih terstruktur.

🔄 Fetch Data Pokemon — Mengambil data dari API Pokemon.

🧩 Komponen Reusable — Modular dan mudah dipelihara.

📱 Desain Responsif — Cocok untuk semua perangkat.

# 🧠 Kenapa Menggunakan useReducer?
useReducer membuat pengelolaan state lebih sederhana untuk aplikasi dengan banyak kondisi. Dibandingkan dengan useState, useReducer membuat logika menjadi lebih jelas dan terorganisir.

Contoh penggunaan:

javascript
Salin
Edit
const [state, dispatch] = useReducer(reducer, initialState);

dispatch({ type: 'TANGKAP_POKEMON', payload: pokemon });
# 🛠️ Teknologi yang Digunakan
React

Vite

JavaScript

PokéAPI

Tailwind CSS (opsional, jika digunakan)

# 📂 Struktur Proyek
pgsql
Salin
Edit
Pokemon-apps/
├── public/
├── src/
│   ├── components/
│   ├── context/
│   ├── reducers/
│   ├── App.js
│   └── index.js
├── .gitignore
├── package.json
├── vite.config.js
└── README.md
