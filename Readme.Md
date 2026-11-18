# Campus Parking

Campus Parking es una aplicación web sencilla para administrar el ingreso y la salida de vehículos en un estacionamiento. Permite registrar vehículos, consultar los espacios disponibles y llevar un historial de los pagos.

## Inicio de sesión

Utiliza estas credenciales para ingresar:

| Campo | Credencial |
| --- | --- |
| Usuario | `Admin1` |
| Correo electrónico | `admin1@gmail.com` |
| Contraseña | `admin123` |

Estas credenciales están definidas directamente en el código de JavaScript y sirven para probar el proyecto. El inicio de sesión no utiliza un servidor ni es adecuado para proteger información real.

## Funciones principales

- **Inicio de sesión:** acceso a las páginas del sistema con las credenciales de prueba.
- **Registro de vehículos:** guarda la placa, el tipo de vehículo, la fecha de ingreso y el espacio asignado.
- **Control de espacios:** muestra los 20 espacios disponibles y señala cuáles están ocupados.
- **Gestión de vehículos:** permite modificar el tipo y el espacio asignado, eliminar un registro y procesar el pago al salir.
- **Historial de salidas:** conserva los vehículos que ya pagaron, junto con su hora de salida y el total cobrado.
- **Panel de control:** muestra vehículos en el parqueo, vehículos atendidos, ingresos acumulados y un gráfico de ingresos por tipo de vehículo. También permite consultar ingresos por fecha.
- **Almacenamiento local:** guarda vehículos, historial e ingresos en `localStorage` del navegador.

## Tarifas por hora

| Tipo de vehículo | Tarifa |
| --- | ---: |
| Moto | Q10 |
| Carro | Q20 |
| Bus | Q25 |
| Camión | Q35 |

La tarifa se selecciona durante el proceso de pago.

## Cómo abrir el proyecto

1. Descarga o clona este repositorio.
2. Abre `login.html` en un navegador.
3. Ingresa las credenciales indicadas arriba.
4. Usa la navegación para acceder a **Operaciones** o al **Dashboard**.

El proyecto no requiere un proceso de compilación. El gráfico del panel carga Chart.js desde una CDN, por lo que esa función requiere conexión a internet.

## Tecnologías

- HTML para la estructura de las páginas.
- CSS para los estilos y la adaptación a distintos tamaños de pantalla.
- JavaScript para las operaciones y la manipulación de la página.
- `localStorage` para conservar los datos en el navegador.
- Chart.js para el gráfico del panel.

## Estructura del proyecto

```text
Campus_parking/
├── Estilos/
│   ├── Estilos.css
│   └── responsive.css
├── JavaScript/
│   ├── login.js
│   └── main.js
├── Multimedia/
├── dashboard.html
├── index.html
├── login.html
└── Readme.Md
```

## Capturas de pantalla

### Panel de control

![Panel de control de Campus Parking](./Multimedia/Dashboard.png)

### Sistema de operaciones

![Registro y control de espacios](./Multimedia/Sistema%20part1.png)

### Tabla de entradas

![Tabla de vehículos en el parqueo](./Multimedia/Sistema%20part2.png)

### Tabla de salidas

![Historial de vehículos que salieron](./Multimedia/Sistema%20part3.png)

## Autor

Jose Luis Tot
