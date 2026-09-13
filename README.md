**Sistema de Gestión de Inventario - TechStore**

## 1. Descripción del Proyecto
Este sistema permite **gestionar inventarios en tiempo real** y **optimizar las ventas** de forma automatizada. Fue desarrollado especialmente para *TechStore* con el fin de agilizar la atención a sus clientes.

## 2. Requisitos del Sistema
- [x] Python 3.10 o superior instalado
- [x] Base de Datos MySQL configurada
- [ ] Documentación técnica completada

## 3. Módulos del Sistema
| Módulo | Descripción | Estado |
| :--- | :--- | :--- |
| Autenticación | Control de acceso y roles de usuario | Completado |
| Inventario | Registro y conteo de productos | En Proceso |
| Facturación | Generación de comprobantes de pago | Pendiente |

## 4. Ejemplo de Código Fuente 

```python
def verificar_stock(cantidad):
    if cantidad > 0:
        return "Producto Disponible"
    else:
        return "Sin Stock"
```

## 5. Enlaces Útiles
- [Ver Arquitectura del Sistema](docs/arquitectura.md)
- [Ver Manual de Usuario](docs/manual_usuario.md)
- [Ver Especificación de API](docs/api_endpoints.md)
- [Repositorio Oficial GitHub](https://github.com/brenditaap/documentacion-sistema-v1)

