# Evaluaci-n-Formativa-2
El programa:

Lee un archivo de texto plano (máx 1 KB)
Genera una llave AES
Cifra el contenido del archivo
Luego lo descifra usando la misma llave
Y recupera el texto original


Se utilizo google colabs con python 3 y pycryptodome y se utilizó AES en modo EAX.

Elegí este modo porque es más fácil de implementar y además es seguro.
Permite cifrar el contenido y también verificar que no haya sido modificado, gracias al tag. el tamaño de la llave es de 32 bytes

no pude realizar la parte 5 no logré entender correctamente como implementarlo
