name: Hot fix
description: corrección de pura calentura
title: "[Hot fix]: "
labels: ["hotfix"]
assignees:
  - nallegrotti
body:
  - type: markdown
    attributes:
      value: |
        Así cambian las cosas los apurados
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: ¿Cómo te contactamos para saber cómo llegaste a semejante revelación?
      placeholder: ej. email@example.com
    validations:
      required: false
  - type: textarea
    id: resumen
    attributes:
      label: ¿qué lo qué?
      description: Hacela corta lo jugoso está en el código
      placeholder: De qué va el cambio...
      value: "ah!"
    validations:
      required: true
