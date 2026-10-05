# Portales de empleo — Telecomunicaciones en Argentina y sus colaboradores

**Perfil de referencia:** Augusto Devesa — Senior Project Manager / Ingeniero en Telecomunicaciones · https://augustodevesa.github.io
**Base:** Buenos Aires, Argentina · **Actualizado:** 5 de octubre de 2026
**Contenido:** 52 direcciones verificadas — 49 portales de empleo propios y 3 sitios corporativos de empresas que reclutan sin portal propio.

Índice armado a partir del ecosistema de tu repositorio (`cv/AugustoDevesa_CV_2026.md`): operadores donde trabajaste (Telefónica/Movistar, Telecom, empresas del sector), clientes y los partners con los que vendiste e integraste soluciones (Cisco, Avaya, Siemens).

---

## Cómo se verificó esta lista

Las 52 URLs fueron abiertas una por una antes de entrar en este archivo:

1. Chequeo HTTP con `curl` (código de estado, redirección efectiva y peso de la respuesta).
2. Extracción del `<title>` de cada página y cotejo contra la empresa esperada.
3. Las páginas que dependen de JavaScript o bloquean IP de datacenter (Telecentro, American Tower, Ciena, Telecom institucional) se abrieron además con un navegador real.

Resultado de la última pasada: **50 de las 52 responden 200**. Las salvedades son dos y quedan marcadas en su entrada:

- **Telecom Argentina (institucional)** y **Ciena**: responden 403 a IP de datacenter/VPN por WAF (CloudFront y Cloudflare). La URL es la oficial, pero hay que abrirla desde una conexión local.
- **Telecentro**: responde 200, pero la página se renderiza por JavaScript, así que el `<title>` llega vacío por HTTP; se confirmó por el enlace interno del propio sitio.

Ejemplos descartados durante la verificación, para que se vea el filtro aplicado:

- **American Tower (`/us/careers`)** bloquea el rastreo: se reemplazó por el portal que sí responde (`careers.americantower.com`).
- **Grupo Núcleo** e **IPLAN** bloquean el rastreo y no exponen una página de empleo verificable: quedan fuera del índice.
- **Ecosistemas** (`ecosistemas.com.ar`) tiene el certificado TLS roto y **Crossnet** no resuelve: no entran aunque aparezcan como empleadores en tu lista de búsquedas.
- **FiberHome** publica un único sitio global cuyo `/en/` devuelve error: no hay portal de empleo verificable.
- Publicaciones de bolsas (Computrabajo/Bumeran) o de LinkedIn **no** se usan como dirección principal: cambian de URL y vencen.

---

## A. Operadores, carriers e ISPs de Argentina

*Telecom fijo/móvil, cable, ISP y mayoristas que operan en el país.*

- **Telecom Argentina — Personal / Fibertel / Flow** — Portal de empleo
  - `https://empleos.personal.com.ar/`
  - Portal de empleo propio (buscador de vacantes).
- **Telecom Argentina — institucional** — Portal de empleo
  - `https://institucional.telecom.com.ar/trabajar-en-telecom`
  - Página "Unite al equipo". Bloquea accesos desde IP de datacenter/VPN: abrir desde tu red.
- **Movistar / Telefónica Argentina** — Portal de empleo
  - `https://jobs.telefonica.com/MovistarArgentina/`
  - Sitio de empleo de Movistar Argentina dentro del portal global de Telefónica.
- **Telefónica (matriz global)** — Portal de empleo
  - `https://jobs.telefonica.com/`
  - Portal global; útil para roles corporativos que cubren Hispam.
- **Claro Argentina** — Portal de empleo
  - `https://claroempleos-aup.com/`
  - Portal regional Claro para Argentina, Uruguay y Paraguay; enlazado como "Trabajá con nosotros" desde claro.com.ar.
- **Telecentro** — Portal de empleo
  - `https://www.telecentro.com.ar/vacantes`
  - *(verificación: 200, título vacío por JS)* Aplicación JS: el título llega vacío por HTTP; confirmado por enlace interno del sitio.
- **Supercanal / ARLINK (Grupo Uno, Mendoza)** — Portal de empleo
  - `https://supercanal-sa.pandape.computrabajo.com/`
  - Portal Pandapé de la empresa; también lista búsquedas de Arlink.
- **Metrotel** — Portal de empleo
  - `https://metrotel.com.ar/sumate-m/`
  - Sección "Sumate" del sitio oficial.
- **Metrotel — vacancies** — Portal de empleo
  - `https://metrotel.hiringroom.com/jobs`
  - Portal HiringRoom con las búsquedas activas.
- **Cirion Technologies (ex Lumen LATAM)** — Portal de empleo
  - `https://career.ciriontechnologies.com/go/Argentina/4635119`
  - Portal de carreras filtrado por Argentina.
- **América Virtual** — Portal de empleo
  - `https://www.americavirtualsa.com/carreras.html`
  - Página "Trabajá con Nosotros" del sitio oficial.

## B. Fibra mayorista, data centers y holdings del sector

*Infraestructura de transporte y los grupos que controlan operadores.*

- **Grupo Werthein (holding: Vrio / DIRECTV Latin America)** — Portal de empleo
  - `https://grupowerthein.com/trabaja-con-nosotros/`
  - Holding telco/entretenimiento; es la puerta de entrada a las búsquedas de Vrio y DIRECTV LatAm.
- **Silica Networks (Grupo Datco)** — Sitio corporativo (sin portal propio)
  - `https://silicanetworks.com.ar/`
  - Sin portal de empleo propio; publica búsquedas por LinkedIn.
- **Grupo Datco** — Sitio corporativo (sin portal propio)
  - `https://grupodatco.com/`
  - Sin portal de empleo propio; publica búsquedas por LinkedIn.
- **Ufinet** — Sitio corporativo (sin portal propio)
  - `https://www.ufinet.com/`
  - Sin portal de empleo propio; publica búsquedas por LinkedIn.

## C. Fabricantes y proveedores de red (tus colaboradores/partners)

*Equipamiento, software de red y su canal: los socios con los que se despliegan los proyectos telco.*

- **Cisco** — Portal de empleo
  - `https://careers.cisco.com/global/en`
  - Partner histórico de tu etapa corporativa en Telefónica.
- **Cisco — buscador alternativo** — Portal de empleo
  - `https://jobs.cisco.com/`
  - Redirige al portal de carreras de Cisco.
- **Huawei** — Portal de empleo
  - `https://career.huawei.com/en`
  - Portal global de reclutamiento.
- **Huawei — portal LatAm** — Portal de empleo
  - `https://career.huawei.com/reccampportal/la/index.html`
  - Instancia para Latinoamérica.
- **Ericsson** — Portal de empleo
  - `https://jobs.ericsson.com/careers`
  - Portal global de carreras.
- **Nokia** — Portal de empleo
  - `https://careers.nokia.com/`
  - Portal global de carreras.
- **ZTE** — Portal de empleo
  - `https://job.zte.com.cn/cn`
  - Portal oficial en chino; las búsquedas LatAm salen por LinkedIn.
- **NEC** — Portal de empleo
  - `https://careers.nec.com/`
  - Portal global de carreras.
- **HPE / Juniper Networks** — Portal de empleo
  - `https://careers.hpe.com/juniper`
  - Juniper ya es parte de HPE; el portal de red vive dentro de HPE.
- **Fortinet** — Portal de empleo
  - `https://www.fortinet.com/corporate/careers`
  - Página de carreras del sitio oficial.
- **Palo Alto Networks** — Portal de empleo
  - `https://jobs.paloaltonetworks.com/en`
  - Portal de carreras.
- **Ciena** — Portal de empleo
  - `https://careers.ciena.com/us/en`
  - *(verificación: 403 desde datacenter)* URL oficial; su WAF (Cloudflare) bloquea IPs de datacenter, abrir desde red local.
- **CommScope** — Portal de empleo
  - `https://jobs.commscope.com/`
  - Portal de carreras.
- **Corning** — Portal de empleo
  - `https://corningjobs.corning.com/`
  - Portal de carreras.
- **Prysmian** — Portal de empleo
  - `https://latam.prysmian.com/people-and-careers`
  - Instancia LatAm de "People & Careers" (cables de fibra y energía).
- **Nexans** — Portal de empleo
  - `https://career.nexans.com/`
  - Portal de carreras (cables y conectividad).
- **Vertiv** — Portal de empleo
  - `https://www.vertiv.com/en-us/about/career-center/`
  - Career Center (infraestructura crítica de data centers).
- **Cambium Networks** — Portal de empleo
  - `https://www.cambiumnetworks.com/careers`
  - Página de carreras (radioenlaces y Wi-Fi de exterior).
- **Ubiquiti** — Portal de empleo
  - `http://careers.ui.com/`
  - Portal de carreras del fabricante de UniFi/airMAX.
- **TP-Link** — Portal de empleo
  - `https://www.tp-link.com/ar/about-us/career/`
  - Versión Argentina del sitio de carreras.
- **Samsung Argentina** — Portal de empleo
  - `https://www.samsung.com/ar/about-us/careers`
  - Carreras profesionales Samsung Argentina (incluye redes).
- **Motorola Solutions** — Portal de empleo
  - `https://www.motorolasolutions.com/en_us/about/careers.html`
  - Carreras globales (radio comunicaciones y redes críticas).
- **Motorola Solutions — Argentina** — Portal de empleo
  - `https://www.motorolasolutions.com/es_xl/about/careers/argentina-onboarding.html`
  - Página local para Argentina.
- **Avaya** — Portal de empleo
  - `https://careers.avaya.com/`
  - Partner histórico de tu etapa corporativa en Telefónica.
- **Siemens** — Portal de empleo
  - `https://jobs.siemens.com/en_US/externaljobs/SearchJobs/`
  - Partner histórico de tu etapa corporativa en Telefónica.

## D. Integradores y servicios de TI / telecom

*Despliegue, operación y OSS/BSS: donde suele estar el rol de Project / Delivery Manager.*

- **SONDA** — Portal de empleo
  - `https://carrera.sonda.com/viewalljobs/`
  - Portal de carreras LatAm; tener presente la variante https://www.sonda.com/carreras.
- **Indra / Minsait** — Portal de empleo
  - `https://careers.indragroup.com/?locale=en_US`
  - Portal de carreras del grupo (integró redes de operadores en Argentina).
- **NTT DATA (ex Everis)** — Portal de empleo
  - `https://careers.emeal.nttdata.com/s/careers`
  - Portal EMEAL (Europa, Medio Oriente, África y LatAm).
- **Tech Mahindra** — Portal de empleo
  - `https://careers.techmahindra.com/CurrentOpportunity.aspx`
  - Portal de búsquedas; tiene operación de servicios telco en Buenos Aires.
- **Amdocs** — Portal de empleo
  - `https://www.amdocs.com/careers/home`
  - Software y servicios para operadores (OSS/BSS).
- **Logicalis** — Portal de empleo
  - `https://www.logicalis.com/careers`
  - Integrador global con operación en Argentina (redes, data center, Cisco partner).

## E. Torrecos e infraestructura pasiva

*Dueños de torres y sitios: contratan PM de despliegue y operación.*

- **American Tower** — Portal de empleo
  - `https://careers.americantower.com/`
  - *(verificación: título confirmado en navegador)* Portal global de carreras (torres y sitios en LatAm).
- **Phoenix Tower International** — Portal de empleo
  - `https://www.phoenixintnl.com/careers`
  - Portal de carreras (torrecos, operación Argentina).
- **SBA Communications** — Portal de empleo
  - `https://www.sbasite.com/company/careers/`
  - Portal de carreras (torres y sitios).

## F. Sector público y satelital

*Empresas y organismos del Estado en el sector telecomunicaciones.*

- **ARSAT** — Portal de empleo
  - `https://www.arsat.com.ar/trabajar-en-arsat/`
  - Empresa estatal de telecomunicaciones y satélites (AR-SAT).
- **INVAP** — Portal de empleo
  - `https://www.invap.com.ar/trabajar-en-invap/`
  - Satélites, radar y telecomunicaciones; base en Bariloche.
- **Empleo público (concursos, incluye ENACOM)** — Portal de empleo
  - `https://www.argentina.gob.ar/jefatura/gestion-y-empleo-publico`
  - Portal de la Secretaría de Transformación del Estado: ahí se publican los concursos. ENACOM verificado en https://www.enacom.gob.ar/.

---

## Notas de uso

- **Aliados de tu CV dentro de la lista:** Cisco, Avaya y Siemens están en la sección C (los partners de reventa de tu etapa en el segmento corporativo de Telefónica).
- **Empresas relevantes sin portal de empleo propio** (reclutan por LinkedIn o bolsas, así que conviene seguirlas en vez de visitarlas): Silica Networks, Grupo Datco, Ufinet, OCP Tech, IG Networks, IPLAN, Crossnet, Grupo Núcleo, Air Computers, FiberHome y las vacantes LatAm de ZTE.
- **Vrio / DIRECTV Latin America** no publica portal propio: las búsquedas del grupo salen por el sitio del holding, [Grupo Werthein](https://grupowerthein.com/trabaja-con-nosotros/) (sección B).
- **Regulador:** el ENACOM no tiene portal de empleo; publica en https://www.enacom.gob.ar/ y sus concursos salen por el portal de empleo público de la sección F.
- Este archivo es un índice de **dónde** postular, no de búsquedas abiertas: para las vacantes activas, ver `busquedas-laborales/búsquedas.md`.
