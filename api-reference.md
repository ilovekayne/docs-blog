---
title: API Reference
nav_order: 3
---

# API Reference
{: .no_toc }

<details open markdown="block">
  <summary>Table of contents</summary>
  {: .text-delta }
- TOC
{:toc}
</details>

---

## `kayne.help(person)`

Helps a person. Always succeeds.

| Parameter | Type | Description |
|---|---|---|
| `person` | Human | Anyone. Literally anyone. |

**Returns:** A more capable, more confident person.

```python
>>> kayne.help(you)
<Person confident=True learned_something=True>
```

## `kayne.explain(topic, depth="just right")`

Explains a topic at exactly the depth you need.

**Raises:** Nothing. Kayne doesn't raise exceptions, he raises people up.

## `kayne.respond(incident)`

Handles an incident.

```python
>>> kayne.respond(Incident(severity="everything is on fire"))
[+] staying calm
[+] building timeline
[+] containing threat
[+] writing report
[+] thanking team
<Incident status="resolved">
```

{: .warning }
Do not call `kayne.panic()`. It is not implemented and never will be.

## `kayne.lead(meeting)`

Runs a meeting. Agenda is followed. Tangents go to the parking lot, and then actually get revisited.

**Returns:** A meeting that ends on time.

## `kayne.love`

A read only property.

```python
>>> kayne.love
"from everyone, always"
```
