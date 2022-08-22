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

# Siguiente paso, cambiar de rama 

Git te permite trabajar en distintas ramas, lo más común es tener una rama principal (generalmente se llaman master) y una rama para ior tirando lo nuevo que no está testeado a fondo (generalmente se llama develop).
Para cambiarte a una rama que ya existe lo haces con el comando checkout

git checkout develops

Y seguir las instrucciones del readme que está en esa rama

Programar para vivir