# Proyecto 2

| Carnet | Nombre|
| ------ | ----- |
| [`201900042`](https://github.com/rodrialeh01) | Rodrigo Alejandro Hernández de León |
| [`201901772`](https://github.com/DanielDubonDR) | Daniel Reginaldo Dubón Rodríguez |

# Manual Técnico

## 1. Topología de red

![topologia](./Images/topologia.png)

## 2. Tabla de rangos de IPs disponibles en cada subred

### Villa Nueva

| VLAN | ID de VLAN | ID red       | Mascara de subred | Cantidad de IPs disponibles | Wildcard | Primera IP disponible | Ultima IP disponible | Dirección de broadcast |
| ---- | ---------- | ------------ | ----------------- | --------------------------- | -------- |--------------------- | -------------------- | ---------------------- |
| **Académico** | 318 | 173.118.2.0 | 255.255.255.224 | 30 | 0.0.0.31 | 173.118.2.1 | 173.118.2.30 | 173.118.2.31 |
| **Seguridad** | 218 | 173.118.2.32 | 255.255.255.240 | 14 | 0.0.0.15 | 173.118.2.33 | 173.118.2.46 | 173.118.2.47 |
| **Investigación** | 518 | 173.118.2.48 | 255.255.255.240 | 14 | 0.0.0.15 | 173.118.2.49 | 173.118.2.62 | 173.118.2.63 |
| **Administración** | 118 | 173.118.2.64 | 255.255.255.248 | 6 | 0.0.0.7 | 173.118.2.65 | 173.118.2.70 | 173.118.2.71 |

