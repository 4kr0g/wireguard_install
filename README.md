# wireguard_install
Instalación de servidor  WireGuard en Debian, Ubuntu, Fedora, CentOS, Arch Linux y mas

**Uso**

Baja y ejecuta el script. Contesta las preguntas que te haga y él se ocupará de todo lo demás.

`curl -O https://raw.githubusercontent.com/4kr0g/wireguard_install/refs/heads/main/wireguard_install`

`chmod +x wireguard-install.sh`

`./wireguard-install.sh`

Este proceso instalará WireGuard en tu servidor, incluyendo tanto el módulo necesario para el núcleo del sistema como las herramientas para que funcione correctamente. Además, configurará automáticamente el servicio para que se inicie con el sistema y generará un archivo de configuración para los clientes que se conecten.

Si necesitas añadir o quitar clientes más tarde, solo tienes que ejecutar el script de nuevo.
