# SCBP — Boccia Competition System

**Professional software for managing para boccia competitions** — from the draw to the
awards ceremony: automatic bracketing (BISFed manual), live digital scoresheet, real-time
scoreboard and World Boccia (BCMS) integration.

> This repository is a **public demonstration**. It runs 100% in the browser with
> **fictional data**, no database, no login and **no proprietary source code**
> (draw engine, BCMS integration and official ranking are not included here).
> The full system is proprietary and licensed under contract.

**Live demo:** https://gabrielrdesousa123.github.io/bocciacompetition/
(or open `index.html` in your browser by double-clicking it).

**Languages:** the demo and this document are available in **English**, **Spanish** and
**Portuguese** (language switch in the top-right of the demo).

---

## EN — What the system does

### Registration & base data
- Athletes, clubs, delegations, officials and functional classes.
- Multiple clubs/delegations per athlete.
- Data saved in a consistent format (uppercase) to avoid duplicates.

### Competitions
- Create and manage competitions, classes and schedules.
- Automatic **draw / bracketing** following the official BISFed manual
  (round-robin groups + knockout, including **playoff** for 3, 5, 6 and 7 groups).
- Automatic BIB numbering and re-sequencing.

### Live game management
- **Digital scoresheet** with timer, ends, score, violations and signatures.
- **Scoreboard / big screen** with real-time results.
- **Call Room** with PIN-based check-in and colour control (companion app).

### Rules & ranking (official)
- Automatic standings with the **8 official tie-break criteria**
  (including the mini-group between 3+ tied sides).
- W.O. / forfeit handling, including **double forfeit**.
- Tie-break "extra end" excluded from the recorded score.

### Integration & reporting
- **World Boccia (BCMS)** import/sync of results and schedule.
- PDF scoresheets, final ranking, Technical Delegate report.
- CSV import/export.

### Access levels (roles)
- **General Admin (owner):** full access to everything.
- **National Admin:** works on the main site and all federations. Can **edit**:
  - Competitions (create/manage)
  - Athletes · Clubs · Classes · Officials
  - User registration / access management
  - Approve exemptions & declarations
  - Functional classification
  - CSV import/export · Simulator
  - Can **view** additionally: results, data search, system status, scoreboard, history.
- **Local Admin:** same as National, scoped to a single federation, **without**
  exemptions approval, data search and CSV.
- **Referee / Classifier / Coach / Athlete:** view-focused, role-appropriate access.

### Platform
- Multi-language (PT / EN / ES), multi-federation, responsive, runs in any browser.

---

## ES — Qué hace el sistema

### Registro y datos base
- Atletas, clubes, delegaciones, oficiales y clases funcionales.
- Varios clubes/delegaciones por atleta.
- Datos guardados en formato consistente (mayúsculas) para evitar duplicados.

### Competiciones
- Crear y gestionar competiciones, clases y calendario.
- **Sorteo / cuadro** automático según el manual oficial BISFed
  (grupos todos contra todos + eliminatoria, incluyendo **playoff** para 3, 5, 6 y 7 grupos).
- Numeración y re-secuenciación automática de BIB.

### Gestión de juego en vivo
- **Planilla digital** con cronómetro, parciales, marcador, violaciones y firmas.
- **Marcador / pantalla** con resultados en tiempo real.
- **Cámara de llamada** con registro por PIN y control de colores (app de apoyo).

### Reglas y clasificación (oficial)
- Clasificación automática con los **8 criterios oficiales de desempate**
  (incluye el mini-grupo entre 3+ empatados).
- Manejo de W.O. / forfeit, incluyendo **doble forfeit**.
- Parcial de desempate excluido del marcador registrado.

### Integración e informes
- Importación/sincronización con **World Boccia (BCMS)** de resultados y calendario.
- Planillas en PDF, clasificación final, informe del Delegado Técnico.
- Importación/exportación CSV.

### Niveles de acceso (roles)
- **Admin General (dueño):** acceso total.
- **Admin Nacional:** actúa en el sitio principal y todas las federaciones. Puede **editar**:
  - Competiciones (crear/gestionar)
  - Atletas · Clubes · Clases · Oficiales
  - Registro de usuarios / gestión de accesos
  - Aprobar dispensas y declaraciones
  - Clasificación funcional
  - Importar/exportar CSV · Simulador
  - Además puede **ver**: resultados, búsqueda de datos, estado del sistema, marcador, historial.
- **Admin Local:** igual que el Nacional, limitado a una federación, **sin**
  aprobación de dispensas, búsqueda de datos ni CSV.
- **Árbitro / Clasificador / Técnico / Atleta:** acceso de consulta según el rol.

### Plataforma
- Multi-idioma (PT / EN / ES), multi-federación, responsivo, funciona en cualquier navegador.

---

## PT — O que o sistema faz

### Cadastro e dados base
- Atletas, clubes, delegações, oficiais e classes funcionais.
- Vários clubes/delegações por atleta.
- Dados salvos em formato consistente (maiúsculas) para evitar duplicidades.

### Competições
- Criar e gerenciar competições, classes e agenda.
- **Sorteio / chaveamento** automático conforme o manual oficial BISFed
  (grupos todos contra todos + eliminatória, incluindo **playoff** para 3, 5, 6 e 7 grupos).
- Numeração e re-sequenciamento automático de BIB.

### Gestão de jogo ao vivo
- **Súmula digital** com cronômetro, parciais, placar, violações e assinaturas.
- **Scoreboard / telão** com resultados em tempo real.
- **Câmara de Chamada** com check-in por PIN e controle de cores (app de apoio).

### Regras e classificação (oficial)
- Classificação automática com os **8 critérios oficiais de desempate**
  (inclui o mini-grupo entre 3+ empatados).
- Tratamento de W.O. / forfeit, incluindo **duplo forfeit**.
- Parcial de tie-break excluída do placar registrado.

### Integração e relatórios
- Importação/sincronização com a **World Boccia (BCMS)** de resultados e agenda.
- Súmulas em PDF, classificação final, relatório do Delegado Técnico.
- Importação/exportação CSV.

### Níveis de acesso (papéis)
- **Admin Geral (dono):** acesso total a tudo.
- **Admin Nacional:** atua no site principal e em todas as federações. Pode **editar**:
  - Competições (criar/gerenciar)
  - Atletas · Clubes · Classes · Oficiais
  - Cadastro de usuários / gestão de acessos
  - Aprovar dispensas e declarações
  - Classificação funcional
  - Importar/exportar CSV · Simulador
  - Além disso pode **visualizar**: resultados, pesquisa de dados, status do sistema, scoreboard, histórico.
- **Admin Local:** igual ao Nacional, restrito a uma federação, **sem**
  aprovação de dispensas, pesquisa de dados e CSV.
- **Árbitro / Classificador / Técnico / Atleta:** acesso de consulta conforme o papel.

### Plataforma
- Multi-idioma (PT / EN / ES), multi-federação, responsivo, roda em qualquer navegador.

---

## Contact / Contacto / Contato

- **E-mail:** gabrielrdesousa@gmail.com
- **Gabriel Sousa** — PE teacher, MSc in Public Health, para sport researcher (para boccia).

Licensing per event or annual subscription. Request a personalized demo.

---

<sub>© 2026 SCBP. Public demonstration. The system source code is proprietary and NOT
included in this repository. Third-party names (World Boccia, BISFed, BCMS) belong to
their respective owners.</sub>
