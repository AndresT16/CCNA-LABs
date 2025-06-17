# Enrutamiento Estático

Este laboratorio demuestra cómo configurar el **enrutamiento estático** entre dos o más routers en una red básica.

## 🎯 Objetivo

- Configurar rutas estáticas utilizando la dirección **next hop** (siguiente salto).
- Verificar la conectividad punto a punto y de extremo a extremo.

## 🖥️ Topología

![Topología de Enrutamiento Estático](topologia.png)

> Asegúrate de que la imagen `topologia.png` esté en esta misma carpeta para que se muestre correctamente.

## ⚙️ Comando utilizado

El comando principal que se usará en los routers es:

```bash
ip route [red-destino] [máscara] [next-hop]
```
