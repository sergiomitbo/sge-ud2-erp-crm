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

### 4.1 Licencia de ERPNext

- **Qué dice el tema (apartado 6):** ERPNext "cuenta con una versión de código abierto bajo licencia LGPLv3".
- **Qué es correcto hoy:** el código de ERPNext se publica bajo la **GNU General Public License v3 (GPLv3)**, no la LGPLv3. La diferencia importa: la GPLv3 es copyleft completo (cualquier obra derivada que se distribuya debe ser también GPL), mientras que la LGPLv3 permite enlazarla desde software no libre.
- **Fuente:** [Repositorio oficial de ERPNext - GitHub](https://github.com/frappe/erpnext) (apartado License), consultado el 25/09/2026.

### 4.2 Versión actual de Odoo

- **Qué dice el tema (apartado 6):** "su versión actual es la 14" y que el servidor "requiere la versión 3.10 o posterior de Python".
- **Qué es correcto hoy:** la versión vigente es **Odoo 19**. Además, el propio tema es incoherente: exigir Python 3.10 o superior corresponde a versiones recientes de Odoo, no a la 14.
- **Fuente:** [Documentación oficial de Odoo 19](https://www.odoo.com/documentation/19.0/) y [Odoo 19 - Source install](https://www.odoo.com/documentation/19.0/administration/on_premise/source.html), consultados el 25/09/2026.

### 4.3 Versión y SGBD de SuiteCRM

- **Qué dice el tema (apartado 8):** SuiteCRM "puede funcionar en gestores de bases de datos como MySQL, MariaDB o SQL Server" y su versión es la 7.14.5.
- **Qué es correcto hoy:** la versión vigente es **SuiteCRM 8.10.2** (publicada el 31/07/2026), y la matriz de compatibilidad de la versión 8.10 solo admite **MariaDB y MySQL**; SQL Server ya no aparece como compatible.
- **Fuente:** [8.10 Releases - SuiteCRM Docs](https://docs.suitecrm.com/8.x/admin/releases/8.10/) y [Compatibility Matrix - SuiteCRM Docs](https://docs.suitecrm.com/8.x/admin/compatibility-matrix/), consultados el 25/09/2026.

### 4.4 Otras incoherencias menores

- El tema escribe "Phyton" en lugar de **Python** en los apartados de ERPNext y Odoo.

## 5. Matriz de decisión y recomendación

Empresa: **N.º 6 - Consultora internacional** (400 empleados en 5 países, multimoneda, varias sociedades, cumplimiento normativo y todo en la nube).

Opciones evaluadas:

- **Opción 1:** Oracle Fusion Cloud ERP + Salesforce (propietario, SaaS).
- **Opción 2:** Odoo Enterprise en Odoo.sh (ERP y CRM integrados, open core de pago).
- **Opción 3:** Odoo Community + SuiteCRM alojados en una nube propia (libre).

Los datos completos están en `matriz_decision.csv`. Escala: 1 (muy malo) a 5 (muy bueno).

### 5.1 Justificación de las puntuaciones

**Multimoneda y multisociedad (peso 25).** Es el criterio más importante porque la empresa opera con varias sociedades y monedas.
- Opción 1 (5): Oracle está diseñado para grandes grupos multinacionales, con consolidación entre sociedades y varias monedas.
- Opción 2 (4): Odoo Enterprise gestiona varias empresas y monedas, pero la consolidación de un grupo en 5 países es menos madura que en Oracle.
- Opción 3 (2): Odoo Community tiene funciones contables más limitadas y SuiteCRM es un sistema aparte, así que habría que unir los datos a mano o con desarrollos propios.

**Cumplimiento normativo en 5 países (peso 20).** Cada país tiene su fiscalidad, facturación y protección de datos.
- Opción 1 (5): Oracle y Salesforce ofrecen localizaciones legales para muchos países y certificaciones de seguridad propias del proveedor.
- Opción 2 (3): Odoo tiene localizaciones fiscales, pero su calidad varía según el país y puede requerir módulos de terceros.
- Opción 3 (2): las adaptaciones legales dependen de la comunidad o de desarrollos propios, y el cumplimiento recae por completo en la empresa.

**Coste total de propiedad (peso 15).**
- Opción 1 (1): es la opción más cara: suscripción de dos productos para 400 usuarios, más la implantación con consultores especializados.
- Opción 2 (4): la suscripción de Odoo Enterprise es bastante más barata y un único producto reduce el coste de implantación.
- Opción 3 (3): no hay coste de licencia, pero sí de alojamiento, administración, desarrollo de localizaciones e integración entre ERP y CRM, que en una empresa de este tamaño es elevado.

**Nube y escalabilidad (peso 15).** La empresa exige que todo esté en la nube.
- Opción 1 (5): ambos productos son SaaS puro; el proveedor gestiona servidores, copias y actualizaciones.
- Opción 2 (4): Odoo.sh es nube gestionada por Odoo, aunque con más responsabilidad técnica para el cliente que un SaaS puro.
- Opción 3 (3): se puede desplegar en una nube pública, pero la empresa tiene que administrar servidores, bases de datos y copias.

**Soporte del proveedor (peso 10).**
- Opción 1 (5): soporte oficial de Oracle y Salesforce, con red amplia de partners en todos los países.
- Opción 2 (4): soporte oficial de Odoo incluido en la suscripción Enterprise, y red de partners.
- Opción 3 (1): no hay soporte oficial del fabricante; habría que depender de la comunidad o contratar a una empresa externa.

**Independencia del proveedor y migración futura (peso 10).**
- Opción 1 (1): máxima dependencia: el código Apex de Salesforce y las extensiones de Oracle solo funcionan en sus plataformas, y cambiar de sistema sería muy costoso.
- Opción 2 (3): la base de Odoo es abierta y se puede volver a Community o autoalojar, pero los módulos Enterprise son de pago y se perderían.
- Opción 3 (5): todo el código es libre (LGPLv3 y AGPLv3); los datos y el sistema pueden llevarse a cualquier proveedor.

**Integración ERP-CRM (peso 5).**
- Opción 1 (3): son productos de dos fabricantes distintos y hace falta un conector o una plataforma de integración.
- Opción 2 (5): ERP y CRM son el mismo sistema, sin integración que mantener.
- Opción 3 (2): son dos sistemas distintos sin conector oficial entre ellos, así que habría que desarrollarlo.

### 5.2 Totales ponderados

Total ponderado = suma de (peso × puntuación) / 100.

| Opción | Cálculo | Total |
|---|---|---|
| Opción 1: Oracle + Salesforce | (125 + 100 + 15 + 75 + 50 + 10 + 15) / 100 | **3,90** |
| Opción 2: Odoo Enterprise (Odoo.sh) | (100 + 60 + 60 + 60 + 40 + 30 + 25) / 100 | **3,75** |
| Opción 3: Odoo Community + SuiteCRM | (50 + 40 + 45 + 45 + 10 + 50 + 10) / 100 | **2,50** |

### 5.3 Recomendación final

Se recomienda la **opción 1: Oracle Fusion Cloud ERP + Salesforce**. Es la que mejor cubre lo que más pesa en esta empresa: varias sociedades, varias monedas y cumplimiento legal en 5 países, todo en la nube y con soporte oficial. La opción 2 queda muy cerca y sería la alternativa si el presupuesto no permite la primera. La opción 3 se descarta: es libre y barata en licencias, pero no está a la altura de una consultora de 400 empleados con estas exigencias legales.

### 5.4 Riesgos de la recomendación

- **Coste total:** es la opción más cara, tanto en suscripciones (dos productos para 400 usuarios) como en implantación. Hay que negociar contratos plurianuales y controlar el número de licencias.
- **Dependencia del proveedor:** la empresa queda atada a Oracle y Salesforce. Si suben precios o cambian condiciones, cambiar de sistema es caro y lento.
- **Soporte:** aunque es oficial, el soporte avanzado suele pagarse aparte, y conviene contar con un partner de implantación en cada país.
- **Migración futura:** los desarrollos en Apex y las personalizaciones de Oracle no se pueden llevar a otro sistema. Para reducir el riesgo, conviene limitar las personalizaciones y exportar los datos periódicamente en formatos abiertos.
- **Integración:** al ser dos fabricantes, la conexión entre ERP y CRM es un punto de fallo que hay que mantener en cada actualización (Oracle publica 4 al año y Salesforce 3).