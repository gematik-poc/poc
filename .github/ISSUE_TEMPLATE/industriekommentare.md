---
name: Industriekommentare
about: "Kommentare für Änderungsvoschläge der Industrie"
title: "[Änderungsvorschlag]: "
labels: "bug"
assignees: "gematik"
body:
  - type: markdown
    attributes:
    value: "## Welcome!"
  - type: input
    id: document
    attributes:
      label: "Dokument"
      description: "Name des Dokuments (erforderlich)"
    validations:
      required: true
  - type: input
    id: chapter
    attributes:
      label: "Kapitel"
      description: "Name des Kapitels im Dokument"
    validations:
      required: false
  - type: input
    id: afo
    attributes:
      label: "AFO"
      description: "AFO im Dokument"
    validations:
      required: false
  - type: input
    id: line
    attributes:
      label: "Zeilennr."
      description: "Zeilennr. im Dokument"
    validations:
      required: false
  - type: textarea
    id: suggestion
    attributes:
      label: "Vorschlag"
      description: "Ihr Änderungsvorschlag (erforderlich)"
    validations:
      required: true
---
