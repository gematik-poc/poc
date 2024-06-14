---
name: Industriekommentare
about: Kommentare für Änderungsvoschläge der Industrie
title: "[Änderungsvorschlag]: "
labels: ["Fehler", "Verbesserung", "Ergänzung"]
assignees: ''
body:
  - type: input
    id: Dokument
    attributes:
      label: Dokument
      description: Name des Dokuments (erorderlich)
      placeholder:
    validations:
      required: true
  - type: input
    id: Kapitel
    attributes:
      label: Kapitel
      description: Name des Kapitels im Dokument
    validations:
      required: false
  - type: input
    id: AFO
    attributes:
      label: AFO
      description: AFO im Dokument
    validations:
      required: false
  - type: input
    id: Zeilennr.
    attributes:
      label: Zeilennr.
      description: Zeilennr. im Dokument
    validations:
      required: false
  - type: textarea
    id: Vorschlag
    attributes:
      label: Vorschlag
      description: Ihr Änderungsvorschlag
    validations:
      required: true
---
