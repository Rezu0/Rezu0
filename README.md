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
