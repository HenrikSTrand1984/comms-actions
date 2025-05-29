
# COMMS – Agent 06

COMMS er kommunikasjons- og koordineringsagenten i COMMS-systemet. Den initierer samhandling, validerer agentstatus og styrer informasjonsflyt mellom agenter.

## 📘 Agentbeskrivelse (JSON)
Full definisjon av agentens rolle, input/output og handlinger:

🔗 [Se JSON-definisjon på GitHub](https://raw.githubusercontent.com/BRUKERNAVN/REPO/branch/definitions/STV-COMMS-05-JS-06-001-V1.0.json)

> Erstatt `BRUKERNAVN/REPO/branch` med din faktiske GitHub-URL.

## 🧩 Handlinger

| ID         | Navn                    | Beskrivelse |
|------------|-------------------------|-------------|
| ACT-06-001 | Koordiner agenter       | Initierer tverragent-koordinering |
| ACT-06-002 | Sjekk agentstatus       | Validerer agenter før igangsetting |
| ACT-06-003 | Loggfør handling        | Logger handling og status |

## 🔁 Input / Output-format

**Input:**
- `scenario_id`: string
- `involverte_agenter`: liste
- `metadata`: objekt

**Output:**
- `status`: string
- `resultat`: objekt
- `logg_id`: (valgfri) string

## 📂 Relaterte filer

- `STV-COMMS-05-JS-06-001-V1.0.json` – JSON-definisjon
- `README_COMMS_with_JSON.md` – Denne filen

## 🧠 Bruk

- COMMS brukes til å koordinere samspill mellom agenter, validere systemstatus og sende endringssignaler.
- Den fungerer som kontrollsenter og mellomledd mellom strategi og operasjon.
