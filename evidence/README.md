# Evidencias

Capturas del laboratorio en Cisco Packet Tracer. Los hash de contraseñas fueron tapados.

| Archivo | Contenido |
|---|---|
| 00-topologia-packet-tracer.png | Topología completa con todos los enlaces activos |
| 00-vlan-trunk-sw-core.png | `show vlan brief` y `show interfaces trunk` en SW-CORE |
| 01-conectividad-entre-vlan.png | Pings entre VLAN y hacia la DMZ antes de aplicar ACL |
| 02-salida-a-internet.png | Ping de ADMINISTRACION a PC-INTERNET (NAT/PAT) |
| 03-publicacion-web-dmz.png | Página de SRV-WEB cargada desde PC-INTERNET |
| 04-show-access-lists.png | `show access-lists` en R-EDGE con contadores |
| 05-acl-bloqueos-administracion.png | Desde ADMINISTRACION: SRV-ARCHIVOS responde, VENTAS y TI bloqueados |
| 05-acl-bloqueos-dmz.png | Desde SRV-WEB: acceso a la red interna bloqueado |
| 06-acl-permitidos-ti.png | Desde TI: acceso permitido a VENTAS y SRV-ARCHIVOS |
| 07-wifi-conectado.png | Laptop asociado al AP (enlace inalámbrico) y `ipconfig` con 192.168.50.10 |
| 08-invitado-bloqueos-1.png | Desde INVITADO: Internet responde, redes internas bloqueadas |
| 08-invitado-bloqueos-2.png | Desde INVITADO: DMZ bloqueada |
| 09-guest-acl-contadores.png | `show access-lists GUEST_IN` con contadores |
| 10-ssh-desde-ti-redge.png | SSH a R-EDGE desde TI con banner |
| 10-ssh-desde-ti-swcore.png | SSH a SW-CORE desde TI con banner |
| 11-telnet-rechazado.png | Telnet cerrado sin sesión utilizable |
| 11-ssh-administracion-bloqueado.png | SSH desde ADMINISTRACION con timeout |
| 12-vty-acl-contadores.png | `show access-lists VTY_MGMT` con contadores |
| 13-claves-cifradas-redge.png | Contraseñas cifradas en R-EDGE (hash tapados) |
| 13-claves-cifradas-swcore.png | Contraseñas cifradas en SW-CORE (hash tapados) |
| 14-nat-estatico-dmz.png | NAT estática del servidor web y `show ip nat translations` |
