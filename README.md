<div align="center">

<sub>THE SECURITY WORKBENCH OF</sub>

# Arun Kumar

### Build it. Question it. Make it safer.

Application security &nbsp; / &nbsp; Authorization &nbsp; / &nbsp; Developer tools

[Explore the work ↓](#the-workbench) &nbsp; · &nbsp; [Browse repositories ↗](https://github.com/chermanarun?tab=repositories)

</div>

---

```text
arun@workbench:~$ whoami

A builder exploring the space between
"it works" and "it works securely."

> identity       Who are you?
> authorization  What can you do?
> remediation    How do we make it safer?
```

## The workbench

Two projects. Two sides of the security problem: designing access and fixing weaknesses.

<table>
<tr>
<td valign="top" width="50%">

### 01 / Control the access
#### <a href="https://github.com/chermanarun/SecureShare">SecureShare ↗</a>

**Sharing a document is easy. Getting the boundaries right is the interesting part.**

A reference app for document sharing across tenants, with identity, authorization, and delegation kept separate.

- Relationship-based access with OpenFGA
- Constrained, temporary read tokens
- Threat modeling and authorization tests

<sub>PYTHON · FASTAPI · OPENFGA · POSTGRESQL · DOCKER</sub>

<br><br>

<a href="https://github.com/chermanarun/SecureShare/blob/main/docs/architecture.md">Read the architecture</a> · <a href="https://github.com/chermanarun/SecureShare/blob/main/docs/threat-model.md">Explore the threat model</a>

</td>
<td valign="top" width="50%">

### 02 / Understand the weakness
#### <a href="https://github.com/chermanarun/cwe-lookup">CWE Lookup ↗</a>

**A weakness ID is a starting point. A useful fix is the destination.**

A security workbench that connects CWE entries with remediation examples and developer-ready issue descriptions.

- Search weaknesses by ID or keyword
- Explore fixes across programming languages
- Generate structured Jira descriptions

<sub>JAVASCRIPT · VITE · TAILWIND CSS · MITRE CWE API</sub>

<br><br>

<a href="https://github.com/chermanarun/cwe-lookup">Explore the project</a>

</td>
</tr>
</table>

## Follow the questions

| The question | Where I explore it |
| :--- | :--- |
| Who should have access—and for how long? | Tenant isolation, relationship checks, delegated access |
| What turns a finding into a useful fix? | CWE intelligence, remediation examples, developer workflows |
| How do we check the boundaries? | Threat models, architecture notes, security-focused tests |

<details>
<summary><b>Open the toolbox</b></summary>

<br>

Technologies used across these projects:

**Backend & data**  
Python · FastAPI · SQLAlchemy · PostgreSQL

**Authorization & security**  
OpenFGA · JWT identity claims · Macaroon-style delegation · CWE

**Web & delivery**  
JavaScript · HTML · Tailwind CSS · Vite · Docker · GitHub Actions · Pytest

</details>

---

<div align="center">

**Good questions belong next to good code.**

<sub>Explore a project. Read the decisions. Inspect the boundaries.</sub>

<br><br>

<a href="https://github.com/chermanarun?tab=repositories">All repositories ↗</a>

</div>
