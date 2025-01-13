# LineFollower-Speedy-
Documentación del desarrollo del Seguidor de línea (El speedy)  

```plaintext
line_follower_project/
├── docs/                        # Documentación del proyecto
│   ├── README.md                # Descripción del proyecto
│   ├── schematics/              # Diagramas eléctricos y electrónicos
│   │   ├── circuit_diagram.png
│   │   └── PCB_design.pdf
│   └── requirements.md          # Lista de requisitos de hardware y software
├── hardware/                    # Archivos relacionados con el hardware
│   ├── BOM.csv                  # Lista de materiales (Bill of Materials)
│   ├── chassis_design/          # Diseños mecánicos (CAD)
│   │   ├── chassis.stl
│   │   └── chassis.fusion360
│   ├── sensors/                 # Información sobre sensores
│   │   └── sensor_datasheets/
│   │       └── IR_sensor.pdf
│   ├── motor_drivers/           # Archivos de controladores de motores
│   │   └── motor_driver_schematic.png
│   └── microcontroller/         # Configuración del microcontrolador
│       ├── pinout_diagram.png
│       └── firmware.hex
├── software/                    # Código fuente y programas
│   ├── main/                    # Código principal
│   │   ├── main.c
│   │   └── main.h
│   ├── libraries/               # Librerías reutilizables
│   │   ├── PID_controller.c
│   │   └── motor_control.c
│   ├── test/                    # Código para pruebas
│   │   ├── test_pid_controller.c
│   │   └── test_sensors.c
│   └── README.md                # Guía para compilar e instalar
├── tests/                       # Pruebas físicas y simulaciones
│   ├── simulations/             # Simulaciones virtuales
│   │   └── line_follower_simulation.py
│   ├── performance_logs/        # Registros de pruebas de rendimiento
│   │   ├── test_1_results.log
│   │   └── test_2_results.log
│   └── README.md                # Guía de pruebas
├── media/                       # Fotos, videos y otros recursos multimedia
│   ├── videos/
│   │   └── demo_video.mp4
│   └── images/
│       ├── prototype.jpg
│       └── testing.jpg
├── LICENSE                      # Licencia del proyecto
├── README.md                    # Introducción y explicación del proyecto
├── .gitignore                   # Archivos y carpetas a ignorar por Git
└── Makefile                     # Configuración para compilar el proyecto
```

## Descripción de las Carpetas y Archivos

### `docs/`
- **`README.md`**: Descripción general del proyecto.
- **`schematics/`**: Contiene diagramas eléctricos y diseños de PCB.
- **`requirements.md`**: Detalla los requisitos de hardware y software.

### `hardware/`
- **`BOM.csv`**: Lista de materiales necesarios para el proyecto.
- **`chassis_design/`**: Archivos de diseño mecánico del chasis.
- **`sensors/`**: Información técnica sobre los sensores utilizados.
- **`motor_drivers/`**: Esquemáticos de controladores de motores.
- **`microcontroller/`**: Configuración y firmware del microcontrolador.

### `software/`
- **`main/`**: Código principal del proyecto.
- **`libraries/`**: Librerías reutilizables (como controladores PID o control de motores).
- **`test/`**: Scripts para probar diferentes partes del sistema.

### `tests/`
- **`simulations/`**: Contiene simulaciones virtuales del robot.
- **`performance_logs/`**: Registros de pruebas realizadas en el hardware.

### `media/`
- **`videos/`**: Videos de demostración o pruebas del robot.
- **`images/`**: Fotos del prototipo, resultados de pruebas, etc.

### Archivos Raíz
- **`LICENSE`**: Licencia del proyecto.
- **`README.md`**: Introducción al proyecto.
- **`.gitignore`**: Archivos o carpetas que Git debe ignorar.
- **`Makefile`**: Instrucciones para compilar y ejecutar el proyecto.

---

## Notas Adicionales
