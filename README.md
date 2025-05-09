# 🐾 Pokemon-Apps
Selamat datang di Pokemon-Apps! Proyek ini merupakan implementasi sederhana namun powerful dari React menggunakan konsep useReducer untuk manajemen state. Cocok bagi Anda yang ingin mempelajari React lebih dalam dengan pola state management yang rapi dan scalable.


![image](https://github.com/user-attachments/assets/08d7edf8-f24f-46be-88be-dffc18a665da)

![image](https://github.com/user-attachments/assets/390ca6b7-12a3-4a8e-a51f-c7fd6c4c72d9)

![image](https://github.com/user-attachments/assets/3c1e5ac7-6c07-4951-afff-d1f6cd58e9a1)



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

JavaScript (ES6+)

PokéAPI

Tailwind CSS (opsional, jika digunakan)

# 📂 Struktur Proyek
pgsql
Salin
Edit
Pokemon-Azis/
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
