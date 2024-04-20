# SkillPill

<div style="display: flex; flex-wrap: wrap; justify-content: center; align-items: center; text-align: center;">

  ![Static Badge](https://img.shields.io/badge/under-construction-yellow)
  
</div>

`LMS` = `Learning Management System` by default in a hybrid fashion - mix of on-premise and cloud solutions - maximizing cost effectiveness with the options of:
- full on-premise setup 
- and eventually full cloud setup 
depending on the needs.


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
  - logs?
- [ ] Redis?
  - frequently accessed vods?

* #### Instrumentalization
- [ ] Docker
- [ ] Kubernetes?/Podman?

* #### Monitoring
- [ ] Grafana
  - grafana cloud?
- [ ] Loki?
- [ ] Prometheus?
  - optimize hard
- [ ] Jaeger?/Tempo?


* #### Cloud
- [ ] AWS?/Azure?

* #### Authentication & Authorization
- [ ] JWT?
- [ ] Built-in?

* #### Miscellaneous
- SendGrid?/MailGun?/? - e-mail notif
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
- VueJS?
- Svelte?

## Docs
- github wiki?
- docs generator/page?
- Docusaurus?
