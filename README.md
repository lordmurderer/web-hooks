#GitHub WebHooks

##Introduction
WebHooks to use on a remote server.

##Installation

1. Clone the repo: `git clone https://github.com/arielcr/web-hooks.git`
2. Upload the __web-hooks__ folder to your site root

##Usage

##### Update Server WebHook
This WebHook updates the files on a remote server every time your make a push to GitHub

1. Go to __[Your Repo]->[Settings]->[Service Hooks]->[WebHook URLs]__
2. Place the URL to `http://yoursite.com/web-hooks/update-server.php`
3. Commit/Push your site
4. Your site will be under `http://yoursite.com/your-repo-name`

For every repo there is a log file located in the __logs__ folder indicating all the commits made for every repo. Be sure that this folder is writable by the web server.


_More WebHooks to be added soon ..._

Estos son los pasos que necesitas realizar:

Clonar el repositorio con los WebHooks
1
git clone https://github.com/arielcr/web-hooks.git
Subir la carpeta web-hooks a la raiz de tu servidor web.
Te vas a tu repositorio en tu cuenta de GitHub, a Settings -> Service Hooks -> WebHooks URLs
Una vez ahi copias la dirección con la ruta al archivo update-server.php (ej: http://tusitio.com/web-hooks/update-server.php)
Presionas Update Settings
