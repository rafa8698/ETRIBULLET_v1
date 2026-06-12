# ETRIBULLET_v1
Avanzado Checker y Escanner Multi-Threaded

**ETRIBULLET** es un potente script en Python diseñado para la validación masiva de credenciales (*combos*) y auditorías de seguridad en servidores web. Destaca por su alta velocidad mediante procesamiento en paralelo y su capacidad para evadir sistemas modernos de protección contra bots.

Soporte completo para listas de proxies con opciones de rotación e inyección dinámica.

# Requisitos

Para aprovechar todas las funciones del script, necesitas instalar las siguientes dependencias:

```
pip install requests
pip install cloudscraper
pip install curl_cffi
```

# Configurar el Almacenamiento
El script interactúa automáticamente con la memoria de tu dispositivo. Asegúrate de crear o verificar las siguientes rutas requeridas (por defecto configuradas para /sdcard en entornos Android):

```
📁 /sdcard/combo/ — Coloca aquí tus listas de credenciales en formato .txt.
📁 /sdcard/proxy/ — Ubicación de tus archivos de proxies de navegación.
📁 /sdcard/ETRIBULLET/ — Carpeta automática donde se exportarán los resultados exitosos (Hits).
```

# Instrucciones

```
git clone https://github.com/rafa8698/ETRIBULLET_v1

cd ETRIBULLET_v1

ls

python3 ETRIBULLET_v1.py
```
