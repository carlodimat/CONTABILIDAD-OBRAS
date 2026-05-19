🏗️ Plataforma de Control Financiero de Obras

Una aplicación web (Single Page Application) diseñada para la gestión centralizada y administración delegada de múltiples obras de construcción. Permite llevar un control exacto de ingresos, egresos, presupuestos, contratos y honorarios en tiempo real, todo desde el navegador.

✨ Características Principales

Gestión Multi-Obra: Crea y alterna entre múltiples proyectos (ej. Rancho Flamboyant, Calle Dos Ojos) desde un solo lugar.

Almacenamiento Aislado: Los datos de cada obra se mantienen separados de forma segura en el almacenamiento local del navegador (LocalStorage).

Dashboards Interactivos: Gráficos dinámicos de evolución financiera, gastos por categoría, por área y por proveedor.

Migrador Mágico (Bulk Paste): Carga rápida de transacciones copiando y pegando directamente desde Excel.

Cuentas por Pagar: Control detallado de deudas, abonos parciales y saldos pendientes con proveedores y subcontratistas.

Exportación de Reportes: Generación automática de reportes financieros globales y detallados en formato PDF y Excel (CSV/XLSX).

🛠️ Tecnologías Utilizadas

Este proyecto no requiere de un servidor backend complejo (Node.js, PHP, etc.) ni bases de datos externas. Todo el procesamiento se realiza en el cliente (navegador).

Estructura y Estilos: HTML5, Tailwind CSS

Lógica y Estado: Vanilla JavaScript (ES6+), LocalStorage API

Gráficos: Chart.js

Manejo de Datos (CSV/Excel): PapaParse, SheetJS (xlsx)

Generación de PDFs: jsPDF, jsPDF-AutoTable

Iconografía: FontAwesome 6

🚀 Cómo usar (Instalación)

Al ser una aplicación basada puramente en tecnologías cliente, su despliegue es inmediato.

Clona o descarga este repositorio.

Abre el archivo index.html directamente en cualquier navegador web moderno (Chrome, Edge, Safari, Firefox).

Para usar en la nube: Sube el proyecto a GitHub Pages y accede desde cualquier dispositivo a través del enlace generado.

🔄 Trabajo Colaborativo (Sincronización vía OneDrive)

Como la aplicación guarda los datos en la memoria del navegador de cada computadora (LocalStorage), para compartir y actualizar la información con otros miembros del equipo utilizando una carpeta compartida de OneDrive, sigan este flujo de trabajo:

Guardar el progreso (Exportar): La persona que registre nuevos gastos o ingresos en la aplicación debe hacer clic en el botón "Respaldar". Esto descargará un archivo .csv con la base de datos actualizada.

Subir a OneDrive: Esa persona debe mover o guardar el archivo .csv recién descargado dentro de la carpeta compartida que usan en OneDrive (por ejemplo: OneDrive - PROCODIMA / Dashboard_Obras / Respaldos_CSV /).

Cargar el progreso (Importar): Cuando la otra persona (ej. tu hija) quiera ver los datos actualizados, solo debe abrir el enlace de la aplicación web en su computadora, seleccionar la obra en el menú, hacer clic en "Cargar CSV" y buscar ese mismo archivo dentro de la carpeta de OneDrive en su PC.

De esta manera, OneDrive funciona como el puente de conexión entre ambas computadoras sin necesidad de bases de datos complejas.

🔒 Privacidad y Seguridad de Datos

Tus datos financieros están seguros. Esta aplicación no envía información a ningún servidor externo. Todas las transacciones, contratos y presupuestos que cargues se procesan y almacenan exclusivamente en la memoria local de tu navegador y en los archivos CSV que decidas exportar.

👨‍💻 Autor

Desarrollado para la administración y control interno de PROCODIMA.
