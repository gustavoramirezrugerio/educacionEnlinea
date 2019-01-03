# Documentación para usar electronJS
https://electronjs.org/
https://electronjs.org/docs/tutorial/quick-start
https://electronjs.org/docs
https://github.com/electron/electron/tree/master/docs
https://electronjs.org/docs/api

# Video de referencia para crear app de Escritorio
https://www.youtube.com/watch?v=8rVqMFIrfTY&t=1899s   	// Crear un Dashboard
https://youtu.be/8rVqMFIrfTY  							// Crear un Dashboard
https://www.youtube.com/watch?v=hOU9wNw9rTs  			// Crear un Editor 
https://www.youtube.com/watch?v=0BWzZ6c8z-g				// Ejemplo de empaquetado de archivos 


# Plantilla inicial del dashboard
https://github.com/rdash/rdash-angular
	git clone https://github.com/rdash/rdash-angular
	cd rdash-angular

	sudo apt install gulp

	sudo npm install -g bower	
	sudo npm install -g gulp
	

	sudo npm install
	bower install


	gulp build
	gulp

# Pagina demostrativa del dashboard
http://rdash.github.io/#/

# Creando poyecto con ElectronJS
	# Crear el directorio del proyecto
	cd ..
	mkdir app-electron
	cd mkdir app-electron

	# Copiar archivos base de nuestra plantilla inicial del Dashboard de Angular que se encuentra en el directorio "dist" (Esta directorio contiene los archivos minificados)
	
	# Iniciar el proyecto electron con
	npm init  // Este comando genera un archivo package.json

	sudo npm install electron-prebuilt --save-dev    // Al parecer esta dependencia dejo de existir
	// npm install electron-prebuilt-compile --save-dev
	

	# Para validar le ejecución de nuestro proyecto se debe ejecutar el siguiente comando
	npm start


	# Ruta donde se encuentra la aplicación ejecutable con base a la dependencia electron-prebuilt
	path/node_modules/electron-prebuilt/dist

# Nota: Para potencializar las app se puede utilizar siti plass
# Creando archivo ejecutable
	> EJEMPLO previo 
	Copiar el ejecutable "electron" que se genero en "node_modules/electron-prebuilt/dist" a un directorio nuevo donde  ejecutaremos nuestra APP de escritorio

	> EJEMPLO 1
	
	sudo npm install -g asar
	asar pack path-miapp app.asar

	> EJEMPLO 
	npm install -g electron-forge
	electron-forge init my-new-project
	cd my-new-project
	electron-forge start
	
	
## Ejemplo de la creación del empaquetado con electron-forge
	npm install -g electron-forge
	electron-forge import
	npm run package

## Construcción del paquete
	npm run package-win
	npm run package-linux
	npm run package-mac

## Creación del ejecutable
	electron-forge make ./
	
## Desistalar la herramienta
	sudo dpkg -r Santander-Spotlight








# Trabajando con AngularJS
	Para agregar mas rutas a nuestra APP se debe ingresar a la ruta:
		src/routes.js




# Proyecto final con electronJS
https://github.com/dialnco/rdash-electron


# rdash-electron
using  [Electron](https://github.com/atom/electron) and [rdash-template](https://github.com/rdash/rdash-angular) for testing.

# Comando para instalar las dependencias del proyecto
npm install
# Comando para iniciar el proyecto
npm start



# Cesar On-primes

config server
gateway

ClientID
SecretID
