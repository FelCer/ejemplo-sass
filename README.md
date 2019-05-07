# ejemplo-sass
Instalar Ruby para Windows o para el sistema operativo
despues en el cmd ejecutar:
gem install sass
gem install compass


se utiliza la extencion de vscode:
-live sass compiler, automaticamente cada ves que se cree o realize un cambio en sass crea o actualiza el archivo css,
  	    	     si se desea cambiar la ruta donde quede el archivo css creando un carpeta (.vscode) en raiz del
	             proyecto y dentro un json asi:
{"liveSassCompile.settings.formats":[
       {
           "format": "expanded",
           "extensionName": ".css",
           "savePath": "/styles/css" //ruta donde se desea el css
       },
       {
           "extensionName": ".min.css",
           "format": "compressed",
           "savePath": "/dist/css"
       }
   ],
   "liveSassCompile.settings.excludeList": [
      "**/node_modules/**",
      ".vscode/**"
   ],
   "liveSassCompile.settings.generateMap": true,
   "liveSassCompile.settings.autoprefix": [
       "> 1%",
       "last 2 versions"
]}



repositrio de la extencion :https://github.com/ritwickdey/vscode-live-sass-compiler
-para ver los cambios reflejados en el navegador se puede utilizar live server.
