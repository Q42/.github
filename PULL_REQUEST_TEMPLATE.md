Ticket: <!-- ticket link -->

## Description of changes

<!-- Replace this with a short description of the changes made, specifically focused on the choices you have made within those changes. -->

## How to validate the changes

<!-- Describe how to validate the changes that are made. -->

## ✅ Definition of Done
Deze checklist helpt bij risicobeheersing tijdens softwareontwikkeling. Het is geen verplichte lijst om volledig af te vinken, maar een basis om na te denken over kwaliteit, veiligheid en best practices. Pas gerust aan voor je eigen project — zolang de risico’s maar bewust worden beheerst.

### 📄 Documentation & Knowledge Sharing

- [ ] Changes are documented in the code and/or `README.md`
- [ ] Relevant Notion pages are updated

### 🧪 Testing & Quality

- [ ] Changes are covered by unit/integration/end-to-end tests
- [ ] GitHub Actions (CI/CD) pass successfully
- [ ] Reviewer has tested and verified the changes locally

### 📊 Monitoring & Performance

- [ ] Relevant metrics (e.g. in Datadog) are added or updated
- [ ] Performance and scalability have been considered and tested if needed

### 🔐 Security & Privacy

- [ ] The changes comply with our [Secure software development policy](https://www.notion.so/q42/12-Secure-software-development-policy-3be5262f736c4a2a854fa2543d90c8be?pvs=4)
- [ ] No personal data or privacy-sensitive information is affected
- [ ] Input validation, authentication, and authorization are properly handled

### 🧩 Traceability & Readiness

- [ ] A Jira ticket is linked, and the ticket number is in the PR title (e.g. `[R2025-1234] Meaningful title`)
- [ ] No unresolved `TODO`s remain in the code (unless followed up with a Jira ticket)

### 🤝 Review & Collaboration

- [ ] Code is reviewed by at least one team member
- [ ] Merge responsibility and timing are agreed upon
- [ ] Team members are informed (e.g. via Slack or daily stand-up)
