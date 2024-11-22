# Ejercicio1
## Instalación de prerrequisitos
Necesitaremos una version de ruby 2.5.0 o superior, Necesitaremos un gestor de paquetes, en este caso, utilizaremos RubyGems

Iniciaremos un sudo apt update -y, seguido utilizaremos el siguiente comando para instalar el ruby: sudo apt-get install ruby-full build-essential zlib1g-dev(este ultimo paquete no deberia ser necesario para debian 12)

Seguido utilizaremos el comando "echo '# Install Ruby Gems to ~/gems' >> ~/.bashrc
echo 'export GEM_HOME="$HOME/gems"' >> ~/.bashrc
echo 'export PATH="$HOME/gems/bin:$PATH"' >> ~/.bashrc
source ~/.bashrc" para instalar las gemas que son paquetes del Ruby (Es recomendable evitar instalarlo como root sino mejor con tu cuenta de usuario)

Creamos un repositorio vacio llamado myblog y nos cambiamos de rama a gh-pages.

Utilizamos jekyll new myblog para crear el directorio myblog y generar el sitio jekyll dentro de el.

Utilizamos bundle exec jekyll serve --host 10.0.22.213 para que con la url que nos da (http:// 10.0.22.213:4000/myblog/) poder ver como se a generado.

Agregamos el repositorio a github.

# Ejercicio2
## Uso de temas en Jekyll
Lo primero que haremos sera ir a la pagina de Jekyll Themes y buscamos el tema de Lagrange, acto seguido le daremos a homepage que nos llevara a una pagina de github, después haremos un fork para clonarlo en nuestro repositorio
![Fork](D:\Usuarios\asir2\Escritorio\actividad2IAW\forktema.png)