Paso 1 - 
Aprovisionar una carpeta llamada "vferrandisweb" con un index.html en su interior para poder mostrar una pagina web.

Paso 2 - 
Asegurarse que en el Vagrantfile aprovisionado, en la linea de "config.vm.synced_folder", esta escrito:
config.vm.synced_folder "./vferrandisweb", "/var/www"

Paso 3 -
La maquina usada es hashicorp/precise32, realizar "vagrant init" correspondiente o un "vagrant destroy" si fuese necesario.
Realizar un "vagrant up" con la nueva configuracion del Vagrantfile y el provision.sh aprovisionado. 
