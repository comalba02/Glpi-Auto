# Contenedor Ubuntu con Apache2, PHP 8.3, MySQL, GLPI 10.0.19 🛠️


![GLPI Dashboard](https://i.postimg.cc/HxDZTSyv/glpi-auto.png)

**¡Todo lo que necesitas para gestionar tu infraestructura de TI en un solo contenedor!** 🚀

Este contenedor de Docker está preconfigurado con:

- **Apache2**: Servidor web confiable y optimizado para GLPI.
- **PHP 8.3**: Entorno de ejecución rápido y moderno para GLPI.
- **MySQL**: Base de datos robusta para almacenar tus datos de GLPI.
- **GLPI 10.0.19**: Sistema de gestión de activos, tickets y soporte para tu infraestructura de TI.
- **Herramientas de red**: Incluye **nano**, **ip a** y **ifconfig** para facilitar la configuración y gestión del contenedor.                                                                                                                  
                                                                                                               
   
![Contenedor Ubuntu 2204](https://i.postimg.cc/RCfwRDhr/glpi-auto2.png)


## 🚀 Características principales

- **Rápido de configurar**: Solo ejecuta el contenedor y empieza a usar GLPI de inmediato.
- **Todo preconfigurado**: Apache, PHP y MySQL listos para GLPI 10.0.19.
- **Escalable**: Ideal para pequeñas empresas o grandes corporaciones.
- **Herramientas útiles**: **nano** para editar archivos, **ip a** y **ifconfig** para gestionar la red directamente desde el contenedor.

## 📝 Cómo empezar

1. **Ejecuta el contenedor** con el siguiente comando:
```bash 
docker run -d -p 8080:80 -p 62354:62354 -p 3306:3306 --name glpi-auto comalba02/glpi-auto
```

## 🔐 Datos de acceso, abre tu navegador para empezar a usar GLPI

### 🌐 Interfaz web de GLPI  
🔗 URL: [http://localhost:8080](http://localhost:8080)  
👤 Usuario: `glpi`  
🔑 Contraseña: `*glpi-auto*`  


### 🗄️ Base de datos  
🛢️ Nombre: `glpi`  
👤 Usuario root: `root`  
🔑 Contraseña: `*glpi-auto*`

## ⚠️ Puertos expuestos

- 8080: Accede a la interfaz web de GLPI.
- 62354: Para la integración con GLPI Inventory.
- 3306: Para la conexión con la base de datos MySQL.

## 🔧 Requisitos

- Docker instalado en tu máquina.
- Puertos 8080, 62354 y 3306 habilitados en tu red.

## 🌍 ¿Por qué elegir GLPI Auto?

Todo en uno: GLPI, Apache, PHP y MySQL listos para funcionar.
Código abierto y gratuito: Sin costos adicionales, solo productividad.
Fácil de usar: Implementación rápida con solo unos comandos.

Herramientas incluidas: nano, "ip a" e "ifconfig" para facilitar la gestión y edición de archivos de configuración dentro del contenedor.

## 📖 Más información

Para más detalles sobre GLPI y cómo sacarle el máximo provecho, visita la documentación oficial de GLPI. https://glpi-project.org/es/documentacion/

## **Contacto adicional:**  

- 🔗 [LinkedIn](https://www.linkedin.com/in/macoronadob)  
- 📱 [WhatsApp](https://wa.me/573508207373)

### ¡Simplifica la gestión de tu TI con GLPI Auto! 🎉
