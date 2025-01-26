# Camagru
To [ Build ] and [ Launch ] the Infra ->
a simple: 
' docker compose up --build '

## Frontend 
### To Run
npm i <br>
npm start

### install
Télécharger et installer nvm :
curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.40.1/install.sh | bash

Télécharger et installer Node.js :
nvm install 22

Vérifier la version de Node.js :
node -v 		# Doit afficher "v22.13.0".
nvm current 		# Doit afficher "v22.13.0".

Verify npm version:
npm -v 			# Should print "10.9.2".

npm la version :
npm install -g npm

### set up new project 
npm config set legacy-peer-deps true   (solve version conflict)
npx create-react-app .

npm install ajv@latest ajv-keywords@latest

--> npm start  :)


## Backend

### PHP-FPM (PHP-FastCGI Process Manager) -> docs
https://itnext.io/how-to-serve-your-backends-with-nginx-a-comprehensive-guide-c8a74955c6ed

### Nginx / PHP docker -> docs
https://marc.it/dockerize-application-with-nginx-and-php8/


