# SkillPill

<div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center; text-align: center;">

  ![Static Badge](https://img.shields.io/badge/under-construction-yellow)
  
</div>

Zgodnie z założeniem będzie to `LMS`, czyli `Learning Management System`.


## Capabilities 
- Creating courses
  - modifying ToC
- Adding/removing videos
- Adding/removing comments
- Adding/Removing files (tasks/solutions)
- Posts for course creators?
- Paths?
  - consolidate similar courses into a track?
- Notifications?

## Technologies
* #### Core
- [ ] .NET 8
- [ ] Serilog
- [ ] RabbitMQ

* #### Databases
- [ ] Postgres
  - users only?
- [ ] Mongo?
  - comments/posts?
- [ ] Redis?
  - frequently accessed vods?

* #### Instrumentalization
- [ ] Docker
- [ ] Kubernetes?/Podman?

* #### Monitoring
- [ ] Grafana
  - [ ] Loki?
  - [ ] Prometheus?
- [ ] Jaeger?

* #### Cloud
- [ ] AWS?/Azure?

* #### Authentication & Authorization
- [ ] JWT?
- [ ] Built-in?

* #### Miscellaneous
- SendGrid?/MailGun? - e-mail notif
- disqus integration?/on-prem comments/posts

## Architecture
- WebAPI
- CQRS?/CQS?
- Clean Architecture?
- Microservices
- Event Driven?

## Tests?
- xUnit?

## Frontend
- React?/Angular?

## Docs
- github wiki?
