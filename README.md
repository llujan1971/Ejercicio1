# Ejercicio1
Detalle del ejercicio 1 de curso de Kubernetes

Cree una carpeta con el nombre Ejercicio1.

Ahi guarde los archivos Laura.html y Dockerfile

Desde esa ubicacion corri los siguientes comandos:

	docker build -t hellolaura:v1 .
  
	docker images (para asegurarme que estuviera creado)
  
	docker run --name ej1-nginx -d -p 8080:80 hellolaura
  
	
Luego desde el navegador: localhost:8080/Laura.html y mostro la pagina con mi nombre.
