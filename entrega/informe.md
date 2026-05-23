# 📄 Informe Técnico del Taller

## 🔖 Nombre del Taller
_Taller 7 - Integración de Vistas de Arquitectura_

https://miro.com/welcomeonboard/OGJHS1c1UW00QU1vQVhwWGdyK0x6dVdqZXArTUV3UUZTYjFkOGV4RStvTGl1K2hjdGVvUy9maWtoUGVsVXV1MHVBN2YrWXdjcnpHdmJnbFpXcVoxM0laeVpXN2ZyN0FGYlh0bU8vRVFTT1JJaXRXY2xHRFNPWUdNTGNWS1B1Q1ZhWWluRVAxeXRuUUgwWDl3Mk1qRGVRPT0hdjE=?share_link_id=13758644422

## 👥 Integrantes del equipo
- Isabela Díaz Acosta
- Samuel Esteban López Huertas
- Sebastián Sánchez Sandoval

## 🧠 Descripción general del trabajo
El objetivo del taller fue integrar las cinco vistas arquitectónicas desarrolladas previamente para el cliente real Falek Latina S.A.S., identificando la relación entre las capas de negocio, información, aplicaciones, infraestructura y seguridad. El trabajo se enfocó en analizar cómo las debilidades actuales de la arquitectura afectan directamente los objetivos estratégicos de la empresa, especialmente su intención de expansión internacional.

Durante el desarrollo del taller se consolidaron los hallazgos de los talleres anteriores, permitiendo construir una narrativa arquitectónica unificada del estado actual (AS-IS) de la organización. También se identificaron riesgos operacionales, tecnológicos y regulatorios, además de posibles decisiones arquitectónicas para una futura arquitectura TO-BE.

## 🔧 Proceso de desarrollo
El trabajo inició revisando los resultados obtenidos en los talleres previos relacionados con infraestructura, seguridad y modelado arquitectónico. A partir de ello, el equipo organizó la información según las cinco vistas empresariales.

Primero se modelaron los procesos de negocio críticos, especialmente el flujo de cotizaciones y la dependencia de herramientas manuales como Excel. Luego se identificaron las entidades de información involucradas y las aplicaciones que soportan dichos procesos. Posteriormente se documentó la infraestructura tecnológica actual, destacando el SPOF en Bogotá y la falta de redundancia.

Finalmente se integró el análisis de seguridad utilizando los hallazgos STRIDE y el cumplimiento normativo de la Ley 1581. Se utilizaron herramientas de documentación y diagramación digital para estructurar el informe y representar las relaciones entre capas.

## 🧩 Análisis del modelo propuesto
El modelo entregado se estructura alrededor de las cinco vistas arquitectónicas clásicas: negocio, información, aplicaciones, infraestructura y seguridad. Cada una permite identificar problemas específicos y entender cómo estos afectan al resto de la arquitectura.

El análisis muestra que Falek Latina posee una arquitectura fragmentada, donde los procesos críticos dependen de herramientas no diseñadas para operaciones empresariales complejas. El modelo representa las necesidades del cliente al evidenciar la necesidad de integración, escalabilidad y transformación digital para soportar la expansión internacional y mejorar la eficiencia operacional.

Se asumió que la empresa continuará utilizando Helisa como ERP principal durante una etapa de transición tecnológica y que una futura arquitectura TO-BE deberá construirse de manera gradual, manteniendo continuidad operativa mientras se modernizan los sistemas actuales.

## 📈 Diagrama final entregado
> (Insertar aquí el enlace o imagen del modelo arquitectónico final realizado en draw.io, PDF o herramienta equivalente)

## 📋 Tabla de actores, entidades o componentes

| Nombre del elemento | Tipo | Descripción | Responsable |
|---------------------|------|-------------|-------------|
| Cliente | Actor | Solicita cotizaciones y realiza pedidos | Área Comercial |
| Asesor Comercial | Actor | Genera cotizaciones y gestiona clientes | Ventas |
| Excel | Aplicación | Herramienta utilizada para cotizaciones manuales | Comercial |
| Helisa | ERP | Sistema contable principal de la empresa | Administración |
| Google Drive | Aplicación | Almacenamiento compartido de archivos | Organización |
| Inventario | Entidad | Información de productos disponibles | Logística |
| Cotización | Entidad | Documento comercial generado para clientes | Ventas |
| CRM SaaS | Aplicación futura | Fuente única de verdad para clientes y ventas | Arquitectura Empresarial |

## 🔍 Investigación complementaria

### Tema investigado:
Integración de vistas arquitectónicas, TOGAF ADM y transformación digital en PYMES.

### Resumen:
Se investigó el marco TOGAF ADM y su enfoque para documentar arquitecturas empresariales mediante la integración de vistas de negocio, datos, aplicaciones y tecnología. TOGAF resalta la importancia de construir primero una arquitectura AS-IS antes de definir una arquitectura TO-BE, permitiendo identificar brechas, riesgos y oportunidades de mejora.

También se analizaron estrategias de transformación digital para pequeñas y medianas empresas, especialmente el enfoque “Bimodal IT” de Gartner. Este modelo propone mantener sistemas legacy operando mientras se implementan nuevas capacidades digitales en paralelo, reduciendo riesgos de migración y evitando interrupciones operativas.

Finalmente, se investigaron casos reales de empresas distribuidoras B2B que implementaron CRM integrados con ERP locales para centralizar información y mejorar procesos de cotización, logrando reducir tiempos operativos y mejorar la trazabilidad de datos.

## 📚 Referencias
- The Open Group. *TOGAF Standard, Version 9.2*. https://www.opengroup.org/togaf
- Brown, Simon. *The C4 Model for Software Architecture*. https://c4model.com
- Gartner. *Bimodal IT: How Gartner Helps CIOs*. https://www.gartner.com
- Microsoft. *STRIDE Threat Model*. https://learn.microsoft.com/azure/security/develop/threat-modeling-tool-threats
- Superintendencia de Industria y Comercio. *Ley 1581 de 2012*. https://www.sic.gov.co
- Google Cloud Platform. *Documentación oficial*. https://cloud.google.com/docs

---

_Este documento hace parte de la entrega del Taller 7 del curso AREM (Arquitectura Empresarial) - Universidad de La Sabana._
