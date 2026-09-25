# Comparativa ERP-CRM libres y propietarios

## 1. Datos

- **propietario:** sergiomitbo
- **empresa:** N.º 6 - Consultora internacional
- **palabra_del_dia:** chorizo

## 2. Licencias y modelos

### 2.1 Software libre (FSF)

El software libre está hecho para que puedas desarrollarlo y ayudar a mejorarlo. Puedes usar y compartir tanto la versión original como la modificada. Según la FSF (Free Software Foundation), un programa es libre si cumple estas cuatro libertades:

- Libertad 0: puedes usarlo para lo que quieras.
- Libertad 1: puedes estudiarlo y editarlo, para lo cual necesitas el código fuente.
- Libertad 2: puedes hacer copias y compartirlas.
- Libertad 3: puedes evolucionar el sistema y compartir tu versión modificada con los demás.

### 2.2 Código abierto (OSI)

El código abierto lo define la OSI (Open Source Initiative). Consiste en que el código fuente del programa está disponible para que cualquiera pueda usarlo, modificarlo y distribuirlo, y así colaborar en su desarrollo.

En la práctica permite casi lo mismo que el software libre. La diferencia está en el motivo: la FSF defiende el software libre por ética, porque cree que el usuario debe tener libertad, mientras que la OSI defiende el código abierto por sus ventajas prácticas, ya que si mucha gente puede ver y mejorar el código, el software sale mejor.

### 2.3 Software propietario

El software propietario es aquel cuyo código fuente pertenece al fabricante y no se hace público. El usuario solo puede utilizarlo en las condiciones que marca la empresa: no puede ver el código fuente, no puede modificarlo a su gusto y no puede hacer copias ni compartirlas. Normalmente se paga mediante una licencia o una cuota mensual o anual. Ejemplos: SAP S/4HANA, Salesforce o Microsoft Dynamics 365.

### 2.4 Libre no significa gratuito

En "software libre", la palabra libre se refiere a la libertad, no al precio. La confusión viene del inglés, donde "free" significa tanto libre como gratis. De hecho, el software libre se puede vender, siempre que quien lo compre reciba también las cuatro libertades.

Además, aunque el programa no cueste nada, implantarlo en una empresa sí tiene costes: servidores o alojamiento, instalación y adaptación por parte de un consultor, formación de los empleados y soporte y mantenimiento.

### 2.5 Edición Community frente a Enterprise

Muchos ERP y CRM siguen el modelo open core: ofrecen una edición Community, libre y gratuita, y una edición Enterprise de pago. La Enterprise añade más módulos y funciones, soporte oficial del fabricante y, en muchos casos, alojamiento en la nube.

En la práctica, si una empresa usa solo la Community ahorra en licencias, pero puede quedarse sin funciones importantes y no tiene soporte oficial si algo falla, así que tendrá que resolverlo por su cuenta o contratar a una empresa externa.

### 2.6 Consecuencias prácticas de las licencias

El copyleft obliga a que las versiones modificadas de un programa sigan siendo libres. Con la licencia GPL, si modificas el programa y repartes tu versión, esta tiene que seguir siendo libre y con el código fuente disponible, así que no puedes cerrarla y venderla como propietaria.

La licencia AGPL va un paso más allá: si modificas el programa y lo ofreces como web o servicio online, los usuarios que lo usan por internet tienen derecho a recibir el código modificado, aunque no les hayas "repartido" el programa. Esto es importante en ERP y CRM, porque normalmente se usan a través del navegador.

### Fuentes

- [Qué es el software libre - GNU/FSF](https://www.gnu.org/philosophy/free-sw.es.html) (consultado el 24/09/2026)
- [The Open Source Definition - OSI](https://opensource.org/osd) (consultado el 24/09/2026)
- [¿Qué es el copyleft? - GNU](https://www.gnu.org/licenses/copyleft.es.html) (consultado el 24/09/2026)
- [GNU Affero General Public License - GNU](https://www.gnu.org/licenses/agpl-3.0.html) (consultado el 24/09/2026)
- [LICENSE de Odoo (texto de la GPL/LGPL) - GitHub](https://github.com/odoo/odoo/blob/master/LICENSE) (consultado el 24/09/2026)

## 3. Fichas técnicas

### 3.1 ERP libre: Odoo Community

| Dato | Valor | Fuente | Fecha de consulta |
|---|---|---|---|
| Licencia | LGPLv3 (GNU Lesser General Public License v3) | [LICENSE - GitHub odoo/odoo](https://github.com/odoo/odoo/blob/master/LICENSE) | 24/09/2026 |
| Versión vigente | Odoo 19 | [Documentación oficial de Odoo](https://www.odoo.com/documentation/19.0/) | 25/09/2026 |
| Lenguaje del servidor | Python (3.10 o superior) | [Odoo 19 docs - Source install](https://www.odoo.com/documentation/19.0/administration/on_premise/source.html) | 25/09/2026 |
| SGBD compatibles | PostgreSQL (12.0 o superior) | [Odoo 19 docs - Source install](https://www.odoo.com/documentation/19.0/administration/on_premise/source.html) | 25/09/2026 |
| Modalidad (local / nube) | Instalación local en servidor propio. La nube oficial (Odoo.sh) requiere pagar el hosting y además la licencia Enterprise | [Odoo.sh - Pricing](https://www.odoo.sh/pricing) | 25/09/2026 |
| Módulos principales | Contabilidad y facturación, CRM y ventas, inventario y compras, fabricación, recursos humanos, marketing, sitio web y comercio electrónico, proyectos (no todos están incluidos en la edición Community) | [Aplicaciones - Odoo](https://www.odoo.com/es_ES) | 25/09/2026 |
| Requisitos | Python 3.10+ con pip, PostgreSQL 12+, wkhtmltopdf 0.12.6 para PDF, Node.js y rtlcss para idiomas RTL | [Odoo 19 docs - Source install](https://www.odoo.com/documentation/19.0/administration/on_premise/source.html) | 25/09/2026 |

### 3.2 ERP propietario: Oracle Fusion Cloud ERP

| Dato | Valor | Fuente | Fecha de consulta |
|---|---|---|---|
| Licencia | Propietaria y comercial. Se contrata por suscripción SaaS (pago periódico por usuario/módulo); no hay licencia perpetua ni acceso al código fuente | [Oracle Fusion Cloud ERP - Oracle](https://www.oracle.com/erp/) | 25/09/2026 |
| Versión vigente | 26C (Oracle publica 4 actualizaciones al año: 26A, 26B, 26C y 26D) | [Oracle Fusion Cloud Financials 26C What's New](https://docs.oracle.com/en/cloud/saas/readiness/erp/26c/fins26c/index.html) · [Quarterly updates - Oracle Fusion Insider](https://blogs.oracle.com/fusioninsider/quarterly-updates-made-easy) | 25/09/2026 |
| Lenguaje del servidor | Java (aplicaciones Java EE sobre Oracle Fusion Middleware y WebLogic Server) | [Introduction to Oracle Fusion Applications - Oracle Docs](https://docs.oracle.com/cd/E25054_01/fusionapps.1111/e14496/intro.htm) | 25/09/2026 |
| SGBD compatibles | Solo Oracle Database. Al ser SaaS, lo gestiona Oracle y el cliente no elige ni administra la base de datos | [Introduction to Oracle Fusion Applications - Oracle Docs](https://docs.oracle.com/cd/E25054_01/fusionapps.1111/e14496/intro.htm) | 25/09/2026 |
| Modalidad (local / nube) | Solo nube (SaaS sobre Oracle Cloud Infrastructure). No existe instalación local de Fusion ERP | [Oracle Fusion Cloud Applications - Oracle](https://www.oracle.com/applications/) | 25/09/2026 |
| Módulos principales | Finanzas y contabilidad, gestión financiera, gestión de proyectos, compras, gestión del rendimiento empresarial (EPM) y, en la cadena de suministro, planificación, ejecución, gestión de pedidos y logística | [Oracle Fusion Cloud ERP - Oracle](https://www.oracle.com/erp/) | 25/09/2026 |
| Requisitos | Solo en el lado del cliente: navegador compatible en una versión mínima y conexión a Internet. En móviles solo se admite la versión más reciente del navegador. El complemento ADF Desktop Integration para Excel exige versiones concretas de Windows y Excel. No hay requisitos de servidor para la empresa | [Oracle Fusion Cloud Applications System Requirements - Oracle Docs](https://docs.oracle.com/en/cloud/saas/applications-common/25d/oacpr/computer-and-other-system-requirements.html) | 25/09/2026 |

**Observación:** al tratarse de SaaS, los campos de SGBD y requisitos no describen lo que instala la empresa, sino lo que gestiona Oracle. Esto supone menos carga técnica, pero más dependencia del proveedor.

### 3.3 CRM libre: SuiteCRM

| Dato | Valor | Fuente | Fecha de consulta |
|---|---|---|---|
| Licencia | AGPLv3 (GNU Affero General Public License v3). Si se modifica y se ofrece como servicio web, hay que dar el código modificado a los usuarios | [Licensing - SuiteCRM Docs](https://docs.suitecrm.com/8.x/admin/licensing/) | 25/09/2026 |
| Versión vigente | SuiteCRM 8.10.2 (publicada el 31/07/2026) | [8.10 Releases - SuiteCRM Docs](https://docs.suitecrm.com/8.x/admin/releases/8.10/) | 25/09/2026 |
| Lenguaje del servidor | PHP (8.2, 8.3 u 8.4). La interfaz está hecha en Angular | [Compatibility Matrix - SuiteCRM Docs](https://docs.suitecrm.com/8.x/admin/compatibility-matrix/) | 25/09/2026 |
| SGBD compatibles | MariaDB (10.6, 10.11, 11.4, 11.8) y MySQL (8.0, 8.4). La versión 8 ya no admite SQL Server | [Compatibility Matrix - SuiteCRM Docs](https://docs.suitecrm.com/8.x/admin/compatibility-matrix/) | 25/09/2026 |
| Modalidad (local / nube) | Instalación local en servidor propio, en un proveedor de nube pública o en hosting gestionado de pago ofrecido por SuiteCRM Ltd | [SuiteCRM - GitHub](https://github.com/SuiteCRM/SuiteCRM) | 25/09/2026 |
| Módulos principales | Ventas (clientes potenciales, cuentas, contactos, oportunidades, presupuestos, facturas y contratos), marketing (campañas, listas de público objetivo, encuestas, eventos), atención al cliente (casos, base de conocimiento), proyectos, calendario, correo e informes | [Documentación de usuario - SuiteCRM Docs](https://docs.suitecrm.com/8.x/user/) | 25/09/2026 |
| Requisitos | Linux, Unix o macOS con PHP 8.2-8.4, servidor web Apache 2.4 y MariaDB o MySQL. Navegador: Chrome 143+, Firefox 140 o 146+, Edge 143+ o Safari 26+ | [Compatibility Matrix - SuiteCRM Docs](https://docs.suitecrm.com/8.x/admin/compatibility-matrix/) | 25/09/2026 |

### 3.4 CRM propietario: Salesforce

| Dato | Valor | Fuente | Fecha de consulta |
|---|---|---|---|
| Licencia | Propietaria y comercial. Se contrata por suscripción SaaS por usuario y edición; no hay acceso al código fuente | [Salesforce Releases - Salesforce](https://www.salesforce.com/products/innovation/releases/) | 25/09/2026 |
| Versión vigente | Winter '27 (en despliegue desde septiembre de 2026). Salesforce publica 3 versiones al año: Spring (febrero), Summer (junio) y Winter (octubre) | [Salesforce Releases - Salesforce](https://www.salesforce.com/products/innovation/releases/) · [Winter '27 Release Notes - Salesforce Help](https://help.salesforce.com/s/articleView?language=en_US&id=release-notes.salesforce_release_notes.htm&release=264&type=5) | 25/09/2026 |
| Lenguaje del servidor | Apex, lenguaje propietario parecido a Java que se ejecuta solo en los servidores de Salesforce | [What is Apex? - Salesforce Developers](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apex/apex_intro_what_is_apex.htm) | 25/09/2026 |
| SGBD compatibles | No se elige: la base de datos es interna y multiinquilino (compartida entre clientes), gestionada por Salesforce. Los datos se consultan con su propio lenguaje, SOQL | [What is Apex? - Salesforce Developers](https://developer.salesforce.com/docs/atlas.en-us.apexcode.meta/apex/apex_intro_what_is_apex.htm) | 25/09/2026 |
| Modalidad (local / nube) | Solo nube (SaaS). No existe instalación local | [Salesforce Releases - Salesforce](https://www.salesforce.com/products/innovation/releases/) | 25/09/2026 |
| Módulos principales | Sales Cloud (ventas), Service Cloud (atención al cliente), Marketing Cloud, Commerce Cloud, Experience Cloud (portales), Data 360 (datos), Agentforce (agentes de IA) y analítica | [Winter '27 Release Notes - Salesforce Help](https://help.salesforce.com/s/articleView?language=en_US&id=release-notes.salesforce_release_notes.htm&release=264&type=5) | 25/09/2026 |
| Requisitos | Solo en el lado del cliente: última versión de un navegador compatible (Chrome, Edge, Firefox o Safari) y conexión a Internet. Internet Explorer 11 no está soportado desde el 01/01/2023. En móvil, app oficial de Salesforce | [Supported Browsers - Salesforce Developers](https://developer.salesforce.com/docs/platform/lwc/guide/get-started-supported-browsers.html) | 25/09/2026 |

**Observación:** igual que Oracle, Salesforce es SaaS puro: la empresa no instala ni administra servidor ni base de datos, pero depende totalmente del proveedor, y el código Apex solo funciona dentro de Salesforce, lo que dificulta una migración futura.

## 4. Fe de erratas del tema 2

## 5. Matriz de decisión y recomendación