# Laboratorio 03 – OSPF y EIGRP

Laboratorio  sobre enrutamiento dinámico con los protocolos **OSPF** y **EIGRP**, simulado en Cisco Packet Tracer.

## Contenido del repositorio

| Archivo | Descripción |
|---|---|
| `Lab_OSPF_EIGRP.pkt` | Topología y configuración del laboratorio en Cisco Packet Tracer. |
| `direccioanamiento y conceptos.pdf` | Plan de direccionamiento IP y conceptos teóricos del laboratorio. |
| `evidencias.pdf` | Evidencias (capturas) de la configuración y verificación de los protocolos. |

## Requisitos

- [Cisco Packet Tracer](https://www.netacad.com/cisco-packet-tracer) para abrir el archivo `.pkt`.
- Un lector de PDF para la documentación.

## Uso

1. Clonar el repositorio:
   ```bash
   git clone <url-del-repositorio>
   ```
2. Abrir `Lab_OSPF_EIGRP.pkt` con Packet Tracer.
3. Consultar `direccioanamiento y conceptos.pdf` para la tabla de direccionamiento.
4. Comparar con `evidencias.pdf` para validar los resultados.

## Comandos de verificación habituales

```
show ip route
show ip protocols
show ip ospf neighbor
show ip eigrp neighbors
ping <ip-destino>
```

