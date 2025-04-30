## AutoAura: Vehicle Health Copilot for the AI_Agents_Hackathon

**AutoAura** is a no-code agentic application built entirely within **Microsoft Copilot Studio** for the AI_Agents_Hackathon. It empowers everyday car owners by transforming confusing vehicle maintenance data into clear, actionable insights through an intelligent chat interface.

### 🚀 Features

- **🔧 Explain Diagnostic Trouble Codes (DTCs)**  
  Users can input codes like P0420 or P0171 and receive simple explanations with suggested actions, referencing internal data and public automotive sources.

- **📑 Summarize Maintenance Reports**  
  Users can paste service reports or error descriptions and AutoAura summarizes the content using generative AI.

- **🛠 Predictive Maintenance Suggestions**  
  Based on mileage, last service date, and vehicle model, AutoAura proactively recommends likely maintenance needs.

- **📅 Book Service Appointments**  
  AutoAura interacts with users to schedule appointments using Microsoft 365 calendar integration (via Outlook or Power Automate).

- **📚 Document Intelligence**  
  The agent is connected to car manuals, diagnostic codes, and TSBs using Copilot Studio’s generative answers from uploaded content and online sources.

### 🧠 Built Using

- ✅ **Microsoft Copilot Studio**  
  (Topics, Generative AI, Variables, Plugins, and Knowledge Base)

This project demonstrates a real-world vertical application of Microsoft Copilot technology in the automotive domain — with no external code — ready to scale across service centers or consumer apps.

---

## 🌐 Public Automotive Knowledge Sources

AutoAura references publicly accessible vehicle data resources to enhance accuracy and support:

- [RepairPal – Common Car Problems](https://repairpal.com/problems)
- [CarMD – Diagnostic Data & Repair Info](https://www.carmd.com/wp/garage/)
- [NHTSA – Vehicle Recalls & Safety Issues](https://www.nhtsa.gov/recalls)
- [OBD-Codes – Trouble Code Definitions](https://www.obd-codes.com/trouble_codes/)

---

## 📁 Knowledge Base

All supporting documents (sample DTC dataset, architecture diagram, service manuals, and topic definitions) are included in the [`knowledgebase/`](./knowledgebase) folder for reference.
