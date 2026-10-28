<h1 align="center">Precious Mutema</h1>

<p align="center">
  Software engineer building internal platforms for public health programmes
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Based_in-Zimbabwe-1f2937?style=flat-square" alt="Based in Zimbabwe">
  <img src="https://img.shields.io/badge/Focus-Health_systems_tooling-1f2937?style=flat-square" alt="Focus: health systems tooling">
  <img src="https://img.shields.io/badge/Open_to-Scholarships_and_collaboration-1f2937?style=flat-square" alt="Open to scholarships and collaboration">
</p>

---

I build the systems public health teams use every day: performance management, supplier
onboarding, resource mapping, programme reporting. Most of it is internal tooling, which
means it is judged on one thing only, whether it holds up when a country office depends
on it at month end. That constraint shapes how I write code. I care about access control
that is actually enforced, forms that fail loudly instead of silently, and data that
still reconciles after three people have touched it.

Most of my repositories are private, because the work belongs to the organisations it was
built for. The summaries below describe what each system does rather than what it contains.

---

### Selected work

| Project | What it does | Stack |
| --- | --- | --- |
| **Performance and programme platform** | OKR cycles from planning through check-in to calibration, programme performance indicators, and a shared resource library. Role-aware throughout: staff, line managers, programme directors, administrators. | React, TypeScript, Express, Prisma, PostgreSQL |
| **Supplier portal** | Supplier onboarding and reference workflows, with password recovery that still works when email delivery does not, and rate limiting on every sensitive route. | React, TypeScript, Express, PostgreSQL |
| **Recognition platform** | Peer recognition with anonymity controls, approval routing to line managers, and administrative oversight. | React, TypeScript |
| **Resource mapping dashboard** | Mapping funding and resource allocation across programme areas for planning and gap analysis. | JavaScript, Python |
| **Thrive LTFU Predict** | Modelling and interface work for anticipating loss to follow-up in care programmes. | Python, TypeScript |
| **PlantIQ** | Plant health identification and diagnostics. | TypeScript, React |
| **Zimsisters, Batana by Cleo, Community Portal** | Community and small-business web products, built end to end. | JavaScript, TypeScript |

---

### Toolkit

**Languages**

<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript">
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python">
<img src="https://img.shields.io/badge/SQL-336791?style=flat-square&logo=postgresql&logoColor=white" alt="SQL">

**Frontend**

<img src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React">
<img src="https://img.shields.io/badge/React_Router-CA4245?style=flat-square&logo=reactrouter&logoColor=white" alt="React Router">
<img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white" alt="Vite">

**Backend and data**

<img src="https://img.shields.io/badge/Node.js-5FA04E?style=flat-square&logo=nodedotjs&logoColor=white" alt="Node.js">
<img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white" alt="Express">
<img src="https://img.shields.io/badge/Prisma-2D3748?style=flat-square&logo=prisma&logoColor=white" alt="Prisma">
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL">
<img src="https://img.shields.io/badge/Zod-3E67B1?style=flat-square&logo=zod&logoColor=white" alt="Zod">

**Platform**

<img src="https://img.shields.io/badge/Vercel-000000?style=flat-square&logo=vercel&logoColor=white" alt="Vercel">
<img src="https://img.shields.io/badge/Railway-0B0D0E?style=flat-square&logo=railway&logoColor=white" alt="Railway">
<img src="https://img.shields.io/badge/GitHub_Actions-2088FF?style=flat-square&logo=githubactions&logoColor=white" alt="GitHub Actions">
<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git">

---

### How I work

- **Authorisation before features.** Every route that matters checks who is asking on the server, not in the component that renders the button.
- **Fail loudly.** A request that cannot succeed should say so to the person who made it, rather than disappear into a fire-and-forget promise.
- **Write the schema down.** Validation at the boundary, typed all the way through, so bad data has somewhere to stop.
- **Build for the slow connection.** On-demand loading and small payloads, because the office that needs the system most often has the worst link to it.

---

### Currently

Building programme management and supplier systems for public health teams, and looking
for a postgraduate scholarship where I can take this work further, particularly around
health data systems in low-resource settings.

---

<p align="center">
  <a href="https://github.com/PreciousMutema"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub"></a>
  <a href="mailto:preciouskmutema@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=flat-square&logo=gmail&logoColor=white" alt="Email"></a>
</p>
