function mostrarMensaje(mensaje) {
  alert(mensaje);
}

function moverOpcionNo() {
  const noBtn = document.getElementById('noBtn');
  const newPosition = Math.random() * (window.innerWidth - noBtn.clientWidth);
  const newTop = Math.random() * (window.innerHeight - noBtn.clientHeight);
  
  noBtn.style.position = 'absolute';
  noBtn.style.left = newPosition + 'px';
  noBtn.style.top = newTop + 'px';
}

 👋 Hi, I’m @Thiago206
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Thiago206/Thiago206 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
