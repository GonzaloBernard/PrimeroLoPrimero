# Clonar el proyecto usando consola cmd o powershell. 
Abris la consola, te paras en algúna carpeta y tiras los comandos:

git clone https://github.com/GonzaloBernard/Arrancanding

code ./Arrancanding

Con el primer comando clonas el repositorio en la carpeta donde estes parado en la consola
El segundo comando abre Visual Studio en la carpeta que acabas de Clonar

# Escribir algo en archivo readme y pushear esos cambios al repositorio 

git add -A

git commit -m "Comentario del commit"

git push

Si ningún comando tiró error, los cambios ya se actualizaron en github.com

//////////////////////////////////////////////////////////

# HTML

Aprovechando para meter un poco de html, en el Visual Studio andá a las extensiones (en la barra de la izquierda arriba, el ultimo icono que son 4 cuadraditos) e instalate Live Server.
Cuando se instala, bien abajo a la derecha aparece un "Go Live", hacele clic y te levanta el archivo index.html como si fuera una pagina web.
Cualquier cambio que hagas te lo muestra en el navegador, esto sería un entorno Local (lo que cambies o agregues solamente vos desde tu pc lo podes ver), para meterlo el github tenes que tirar devuelta los 3 comandos 

git add -A

git commit -m "Comentario del commit"

#Loguear en github
git config --global --add user.name UserName
git config --global --add user.email correo@example.com

git push

(como es una nueva rama, te pide que especifiques a que rama queres pushear los cambios, si tiras una sola vez git push --set-upstream origin develop ya lo dejas seteado y despues tiras directamente git push)



HOla