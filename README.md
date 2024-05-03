<h1 align="center">Hi 👋, I'm Yunian Rezky, call me Rezky</h1>
<p align="left"> <img src="https://komarev.com/ghpvc/?username=rezu0&label=Profile%20views&color=0e75b6&style=flat" alt="rezu0" /> </p>
<h3 align="left">Aku adalah seorang Junior Web Developer dari indonesia, hanya manusia biasa yang sering melakukan kesalahan😊 Still learning, be Humble </h3>

- 🔭 Ex-Web Developer at Universitas International Semen Indonesia **Sistem Akreditasi, Sistem Omawa, Sistem Feeder Mahasiswa**
- 🔍 Project Freelance? Contact me!

```sh
#Ubuntu 22

root:~# sudo apt update
root:~# sudo rmdir Negative Vibes
root:~# sudo mkdir Positive Vibes
root:~# npm install hapi --save
root:~# npm install pm2 -g
root:~# sudo nano server.js
```

```css
const init = async () => {
  const server = Hapi.server({
    port: 2024,
    host: "yourhapiness",
  });

  server.route({
    method: "GET",
    path: "/quotes",
    handler: (request, h) => {
      return "Money is everything";
    },
  });

  await server.start();
  console.log(`Server running on ${server.info.uri}`);
};

init();
```

```sh
root:~# pm2 start server.js
#!if disconnect 'pm2 restart 0'

yourhapiness:2024/quotes
#!output Money is everything
```
<p><img align="left" src="https://github-readme-stats.vercel.app/api/top-langs?username=rezu0&show_icons=true&locale=en&layout=compact" alt="rezu0" /></p>
