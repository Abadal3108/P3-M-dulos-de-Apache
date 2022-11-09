## 1. Añade en tu servidor el módulo mod_info y explique para que se utiliza este plugin.
Ejecutamos este comando para activarlo :
![image](https://user-images.githubusercontent.com/113515441/199713640-798aa0ee-3067-4dc5-a42c-8b08b80ca20c.png)

## 2. Oculta la versión del sistema y sistema de apache.
Ejecutamos este comando: sudo nano /etc/apache2/apache2.conf y ponemos estas 2 líneas para oculta la versión del sistema y sistema de apache

![image](https://user-images.githubusercontent.com/113515441/199681255-b465f46e-cdfe-4cbe-91e7-7333deaa4d23.png)

## 3. Crea una carpeta en la raíz del path del servidor con el nombre public y otra con el nombre private. Permite que la carpeta public se visualice y el resto de las carpetas que se creen, incluyendo private, no se muestren. A continuación, puede observar como se debe de mostrar la carpeta public:
Ejecutamos este comando y creamos 2 carpetas

sudo cd var/www/html

mkdir public 

mkdir private

![image](https://user-images.githubusercontent.com/113515441/200662658-ade67964-2cb7-48d2-8372-902e7070191e.png)

Ejecutamos :sudo nano /etc/apache2/apache2.conf y ponemos el contenido de la foto:
![image](https://user-images.githubusercontent.com/113515441/200664769-c7bf77c2-18ab-4b96-a0a1-d35ce07cb3c2.png)

él - es para hacerlo privado y el + público


Se nos tendría que ver así:
![image](https://user-images.githubusercontent.com/113515441/200397823-262c1205-cb0f-4cb1-a73e-0d407c10bd53.png)

En el público podemos acceder
![image](https://user-images.githubusercontent.com/113515441/200397870-a35fc90f-c5cd-48f1-ac08-5c5c7c6ffb32.png)

Y en el privado no tenemos permisos
![image](https://user-images.githubusercontent.com/113515441/200398052-9bd4a13b-ba13-4353-9dae-db82c03e6090.png)


## 4. Prueba de acceder poniendo www. delante de tu URL actual. ¿Funciona? En caso negativo, haz que funcione mediante el módulo mod_rewrite. Investigue como utilizar el archivo .htacess para implementarlo.
![image](https://user-images.githubusercontent.com/113515441/200398102-762dd25e-2ee8-4df2-a43f-1d130d888870.png)

## 5. Muestra los directorios de Apache con un tema diferente. Puedes utilizar https://github.com/ramlmn/Apache-Directory-Listing u otra alternativa que te llame la atención.
![image](https://user-images.githubusercontent.com/113515441/200405906-9ca9cd6d-4a89-454d-a3e4-957b931a0d30.png)

## 6. (Extra: 1 punto) Crea tu propio tema para el ejercicio anterior, sin dependencias externas.
![image](https://user-images.githubusercontent.com/113515441/200407126-11747a26-d12c-457d-832a-137d997bbd2a.png)

