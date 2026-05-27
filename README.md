![header](https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=200&section=header&text=Marco%20Costa&fontSize=60&fontColor=ffffff&fontAlignY=38&desc=Software%20Engineering%20Student&descSize=20&descAlignY=60&descColor=a78bfa&animation=fadeIn)
![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1000&color=A78BFA&center=true&vCenter=true&width=500&lines=Java+%7C+Spring+Boot+%7C+Docker;Back-end+Developer+in+progress;Building+things+that+work.)

---

## About me

```java
public class MarcoRicardo {
    String[] currentFocus = { "Java", "Spring Boot", "RabbitMQ", "Docker", "Oracle Cloud", "AWS" };
    String   background   = "Audiovisual post-producer — sharpened attention to detail";
    String   goal         = "First developer internship";
    String   location     = "Brazil";
}
```

---

## Projects

### Helpdesk API

REST API for support ticket management with WhatsApp notifications via Twilio.
Custom OAuth2 Authorization Server with password grant, JWT authentication, role-based access control across four roles, and service-layer integration tests against a real H2 database.

**Stack:** `Java 21` `Spring Boot 3` `OAuth2 / JWT` `Twilio` `PostgreSQL` `Docker` `Swagger/OpenAPI`

[View Repository](https://github.com/tonicostmarco/helpdesk-spring-api)

---

### GitHub PR Analyzer

Event-driven backend that ingests GitHub pull request webhooks, validates HMAC-SHA256 signatures, routes events asynchronously through a RabbitMQ Topic Exchange, and exposes PR analytics via a REST API.

Picks up where HelpDesk left off: while HelpDesk covers synchronous request handling and auth, this project adds distributed messaging, async consumers, idempotent event processing, and MongoDB aggregation pipelines.

**Stack:** `Java 25` `Spring Boot 4` `RabbitMQ` `MongoDB` `Docker` `Spring Security / JWT`

[View Repository](https://github.com/tonicostmarco/githubpranalyzer)

---

### GitHub PR Insights

AI-powered analytics layer that consumes the GitHub PR Analyzer API and uses an LLM to generate natural language insights about pull request data — summary, author metrics, and repository metrics — without manual interpretation.

Delegates the analysis to Groq (LLaMA 3.3 70B) and exposes the result via a FastAPI endpoint secured by token delegation to the Java API.

**Stack:** `Python 3.13` `FastAPI` `Groq (LLaMA 3.3 70B)` `requests` `python-dotenv`

[View Repository](https://github.com/tonicostmarco/github-pr-insights)

---

## Technologies and Tools

[![skillicons](https://skillicons.dev/icons?i=java,spring,rabbitmq,docker,postgresql,mongodb,git,linux,maven,postman,idea&theme=dark&perline=11)](https://skillicons.dev)

---

## Next steps

| Topic | Status |
|---|---|
| Oracle Cloud deploy | `in_progress` |
| TypeScript + React — frontend for Portfolio | `in_progress` |
| AWS Cloud Practitioner | `next` |
| Hexagonal Architecture | `planned` |
| Distributed Task Queue (from scratch, Java) | `planned` |

---

## Contact

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/marco-ricardo-07177a2b6/)
[![Gmail](https://img.shields.io/badge/Gmail-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:marcoricardo61b@gmail.com)

![footer](https://capsule-render.vercel.app/api?type=waving&color=0:24243e,50:302b63,100:0f0c29&height=100&section=footer)
