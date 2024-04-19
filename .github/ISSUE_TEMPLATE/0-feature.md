---
name: "✨ Nouvelle fonctionnalité (*new feature*)"
about: Suggérer une idée (*suggest an idea*)
title: "✨"
labels: 'Type: Feature'
assignees: ''
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can we get in touch with you if we need more info?
      placeholder: ex. email@example.com
    validations:
      required: false
  - type: textarea
    id: what-happened
    attributes:
      label: What happened?
      description: Also tell us, what did you expect to happen?
      placeholder: Tell us what you see!
      value: "A bug happened!"
    validations:
      required: true
  - type: dropdown
    id: version
    attributes:
      label: Version
      description: What version of our software are you running?
      options:
        - 1.0.2 (Default)
        - 1.0.3 (Edge)
      default: 0
    validations:
      required: true
  - type: dropdown
    id: browsers
    attributes:
      label: What browsers are you seeing the problem on?
      multiple: true
      options:
        - Firefox
        - Chrome
        - Safari
        - Microsoft Edge
  - type: textarea
    id: logs
    attributes:
      label: Relevant log output
      description: Please copy and paste any relevant log output. This will be automatically formatted into code, so no need for backticks.
      render: shell
  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our [Code of Conduct](https://example.com). 
      options:
        - label: I agree to follow this project's Code of Conduct
          required: true
---
<!-- Ces commentaires seront supprimés automatiquement -->
<!-- **Conseil :** Supprimez les parties qui ne sont pas pertinentes -->
<!-- À côté de Cc :, @ mentionnez les utilisateurs qui devraient être au courant -->

<!-- English
These comments automatically delete
**Tip:** Delete parts that are not relevant
Next to Cc:, @ mention users who should be in the loop
-->

Cc:
<!-- add intended user next to **Hi** -->
<!-- English: add intended user next to **Hi** -->

Bonjour {{ USER }}
<!-- English: Hi {{ USER }} -->

### Souci
Expliquez le souci que vous rencontrez. C'est le **POURQUOI** cela doit être fait.

<!-- English: Pain
Explain the pain you are experiencing.  This is **WHY** this must be done.
-->

### Solution suggérée
<!-- Décrivez la solution que vous souhaitez. -->

<!-- English: Suggested Solution
Describe the solution you'd like.
-->

### Critères d'acceptance
Les critères d'acceptation définissent les exigences qui doivent être remplies pour que l'histoire soit terminée. C'est le **QUOI** qui doit être fait.
See https://www.ssw.com.au/rules/acceptance-criteria.

<!-- English: Acceptance Criteria
Tasks help developers to track small bits of work needed to meet the ACs. This is HOW the work will be done.
See https://www.ssw.com.au/rules/acceptance-criteria.
-->

1. {{ AC 1 }}

### Tâches
Les tâches aident les développeurs à suivre les petites tâches nécessaires pour respecter les AC. Voici **COMMENT** le travail sera effectué.
<!-- English: Tasks
Tasks help developers to track small bits of work needed to meet the ACs. This is HOW the work will be done.
-->

```[tasklist]
- [ ] {{ TASK 1 }}
```

### Informations complémentaires
<!-- Ajoutez ici d'autres informations sur le contexte. -->

<!-- English: More Information
Add any other context here.
-->

### Captures d'écran
<!-- Si nécessaire, ajoutez les captures d'écran pour aider à mieux comprendre votre problème. -->

<!-- English: Screenshots
If applicable, add screenshots to help explain your problem.
-->

Merci !
<!-- English: Thanks! -->
