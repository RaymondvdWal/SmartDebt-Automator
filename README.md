# 🚀 SmartDebt Automator (2026)

<img src="img.shields.io_|_Flutter-blue?style=flat-square" alt="Stack">
<img src="img.shields.io" alt="License">
<img src="img.shields.io" alt="Security">

**SmartDebt Automator** is een volgende generatie fintech-applicatie die schuldenbeheer transformeert van passieve administratie naar actieve, AI-gestuurde automatisering. Gebouwd met een robuuste Java-backend en een vloeiende Flutter-frontend, helpt deze app gebruikers sneller schuldenvrij te worden door middel van real-time bankkoppelingen en intelligente aflosstrategieën.

---

## ✨ Kernfuncties

*   **🔗 Open Banking Integratie:** Volledig geautomatiseerde transactie-synchronisatie via PSD2 ([GoCardless](gocardless.com)). Geen handmatige invoer meer.
*   **📈 Avalanche Engine:** Automatische prioritering van schulden op basis van rentepercentages voor maximale besparing.
*   **🤖 AI Aflos-coach:** Een privacy-vriendelijke AI (Llama 3/Mistral) die proactief cashflow-overschotten identificeert en adviseert over extra aflossingen.
*   **💰 Smart Round-ups:** Automatische afronding van dagelijkse uitgaven, waarbij het wisselgeld direct wordt ingezet voor schuldaflossing via de [Bunq API](doc.bunq.com).
*   **🎮 Gamified Dashboard:** Een interactieve 3D "Schulden-berg" die de voortgang visualiseert en gebruikers motiveert met streaks en badges.

---

## 🛠 Tech Stack

### Backend
*   **Taal:** [Java 21+](www.oracle.com)
*   **Framework:** [Spring Boot 3.x](spring.io)
*   **Security:** Spring Security met JWT en OAuth2.
*   **Database:** PostgreSQL met Hibernate/JPA.
*   **API Doc:** [Swagger / OpenAPI 3.0](swagger.io)

### Frontend
*   **Framework:** [Flutter](flutter.dev) (Multi-platform: iOS & Android)
*   **State Management:** Riverpod of BLoC.
*   **Network:** Retrofit/Dio voor type-safe API calls.
*   **UI:** Glassmorphism design met CustomPaint voor data-visualisatie.

### AI & Data
*   **Engine:** Local LLM hosting (Ollama/vLLM) voor 100% privacy.
*   **Banking API:** GoCardless Account Information API.

---

## 🚦 Roadmap 2025

- [x] **Fase 0:** Core Java/Flutter infrastructuur & Security
- [ ] **Fase 1:** MVP met PSD2 koppeling en Avalanche algoritme
- [ ] **Fase 2:** Implementatie van de Smart Round-up engine
- [ ] **Fase 3:** Integratie van de lokale AI-coach
- [ ] **Fase 4:** Gamification-laag en community functies

---

## 🔒 Privacy & Veiligheid

Dit project is ontworpen met *Privacy by Design*. 
- Financiële data wordt versleuteld opgeslagen (AES-256).
- AI-analyses vinden plaats op geanonimiseerde data.
- Volledig conform de **AVG/GDPR**-richtlijnen van 2025.

---

## 🚀 Quick Start (Development)

### Backend
```bash
cd backend
./mvnw spring-boot:run
