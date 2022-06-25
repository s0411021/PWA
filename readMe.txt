Update before Use

1. <link rel="canonical" href="repository link" />
2. <link rel="manifest" href="/repositoryName/manifest.webmanifest">

3. <script class="swReg">
    if ('serviceWorker' in window.navigator) {
        navigator.serviceWorker.register('/RepositoryName/sw.js', { scope: '/RepositoryName/' })}
    </script>

4. manifest.json 
	{
  "name": "Github Page PWA",
  "short_name": "GPPWA",
  "description": "Github Page as a Progressive Web App",
  "scope": "/RepositoryName/",
  "start_url": "/RepositoryName/",
  "background_color": "#ffffff",
  "theme_color": "#ffffff",
  "display": "standalone", 
  "icons": [
      {
        "src": "/RepositoryName/img/icon.png",
        "type": "image/png",
        "sizes": "700x700"
      }
  ]
}