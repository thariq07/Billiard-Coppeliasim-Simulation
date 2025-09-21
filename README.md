🎱 Billiard Game Simulation with Python & CoppeliaSim

This project is an interactive billiard game simulation built using Python and CoppeliaSim through the ZMQ Remote API.
Players can input force and torque via the terminal to control the cue ball (white ball). The simulation supports a multiplayer turn-based system, integrates physics-based motion and collision dynamics, and demonstrates the application of real-world physics in a computational environment.

Proyek ini merupakan sebuah simulasi permainan biliar yang dibangun dengan memanfaatkan bahasa pemrograman Python serta perangkat lunak CoppeliaSim melalui integrasi dengan ZMQ Remote API. Pada proyek ini, pemain dapat memberikan input berupa gaya (force) dan torsi (torque) melalui terminal yang kemudian input tersebut diteruskan ke bola putih (cue ball sphere 6) di dalam simulasi. Setelah gaya dan torsi diterapkan, bola putih akan bergerak dan menabrak bola-bola lain sehingga menghasilkan interaksi fisika yang sesuai dengan hukum dinamika serta tumbukan antar benda. Tujuan utama dari proyek ini adalah untuk memperlihatkan bagaimana konsep fisika dasar dapat diterapkan secara nyata dalam sebuah lingkungan komputasi. Konsep gaya digunakan untuk menggerakkan bola ke arah tertentu, sedangkan torsi digunakan untuk memberikan efek rotasi. Selain itu, simulasi ini juga menekankan pada dinamika tumbukan (collision dynamics) dimana bola-bola biliar akan saling bertumbukan, memantul, dan bergerak sesuai hukum kekekalan momentum serta energi. Dengan pendekatan ini, proyek tidak hanya menghadirkan sebuah permainan sederhana, tetapi juga menjadi media pembelajaran yang efektif bagi mahasiswa maupun pelajar dalam memahami penerapan fisika dalam bentuk simulasi digital. Selain sebagai implementasi konsep fisika, proyek ini juga memiliki tujuan sebagai tutorial dan panduan pengguna. Laporan yang disusun menjelaskan langkah-langkah mulai dari persiapan lingkungan, instalasi perangkat lunak, hingga cara menjalankan simulasi. Dengan demikian, proyek ini dapat digunakan kembali oleh orang lain yang ingin belajar membuat simulasi serupa atau mengembangkannya lebih lanjut.

🔹 Key Features:
Player input for force and torque through terminal.
Multiplayer turn-based system (alternating shots).
Physics-based collision and realistic ball movement.
Terminal logs showing ball positions before and after shots.

🔹 Tech Stack:
Language: Python
Simulation Platform: CoppeliaSim
API: ZMQ Remote API

🔹 Learning Outcomes:
Applied physics concepts (force, torque, momentum, collision) in a simulated environment.
Hands-on experience in Python API integration with CoppeliaSim.
Improved skills in simulation control, debugging, and documentation.

🚀 Features
- Player input for force and torque through the terminal.  
- Multiplayer turn-based gameplay (alternating shots).  
- Physics-based motion and realistic ball dynamics.  
- Terminal logs showing cue ball and target ball positions.  
- Planned: scoring system, visualization, and video demo.  

📦 Requirements
- Python  
- CoppeliaSim EDU (with ZMQ Remote API enabled)  
- Python package: pip install coppeliasim-zmqremoteapi-client

Adapun Alat dan kebutuhan yang diperlukan dalam pengerjaan project ini sebagai berikut,
1.	Python VsCode
2.	CoppeliaSim (dengan ZMQ Remote API aktif)
3.	Library Python: coppeliasim-zmqremoteapi-client

Adapun tutorial memainkan biliar ini dengan mengikuti langkah-langkah berikut,
1.	Buka CoppeliaSim dan muat scene meja biliar beserta bola-bola (Sphere).
2.	Pastikan bola putih (cue ball) adalah Sphere[6], sedangkan bola lainnya Sphere[0...n].
3.	Tekan tombol Start Simulation di CoppeliaSim.
4.	Masukkan nilai gaya (Fx, Fy, Fz) dan torsi (Tx, Ty, Tz) di terminal saat diminta.
5.	Amati pergerakan bola putih yang menabrak bola lainnya di dalam CoppeliaSim.
6.	Untuk mode multiplayer, pemain bergantian memasukkan input sesuai giliran.
7.	Ketik n jika ingin mengakhiri permainan dan y jika melanjutkan.
