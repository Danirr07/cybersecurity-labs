# Configuración de red de Kali Linux

## Modo de conexión elegido

Host-Only Adapter



![Configuración Host-Only](host-only.png)

## Justificación técnica

Elegí el modo Solo-Anfitrión (Host-Only) porque me permite mantener Kali conectada únicamente con mi computadora, creando una red más privada para realizar las prácticas. De esta manera puedo trabajar y hacer pruebas sin que la máquina virtual quede directamente conectada a mi red doméstica. No elegí el modo Puente (Bridged) porque conectaría Kali directamente a la misma red que utilizan los demás dispositivos de mi casa, algo que no considero necesario para las prácticas y que podría generar una mayor exposición.