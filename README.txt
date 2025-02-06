***************************************
* Vamos a comenzar a utilizar Vagrant *
***************************************

Links interesantes:
https://www.youtube.com/watch?v=sgCojrRmYwM

Comandos:
# Iniciar un proyecto 
    - vagrant init hashicorp-education/ubuntu-24-04 --box-version 0.1.0
    -> Crear el archivo Vagrantfile

# Iniciar la configuración definida en el Vagrantfile
    - vagrant up
    -> crear la carpeta .vagrant que contiene el metadato de las configuración y genera las VM definidas en Vagrantfile    

# Borrar la configuración del Vagrantfile
    - vagrant destroy
    -> borra las vms creadas, no borra los directorios .vagrant ni el Vagrantfile