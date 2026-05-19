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

Abre el archivo index.html (o DASHBOARD_MAESTRO_V51.html) directamente en cualquier navegador web moderno (Chrome, Edge, Safari, Firefox).

Para usar en la nube: Sube el proyecto a GitHub Pages y accede desde cualquier dispositivo a través del enlace generado.

🔒 Privacidad y Seguridad de Datos

Tus datos financieros están seguros. Esta aplicación no envía información a ningún servidor externo. Todas las transacciones, contratos y presupuestos que cargues se procesan y almacenan exclusivamente en la memoria local de tu navegador.

👨‍💻 Autor

Desarrollado para la administración y control interno de PROCODIMA.
