---
tags:
  - harman
  - harman-phoenix
  - iso200
  - analog
  - color-film
  - analog-photography
film_type: Harman Phoenix ISO 200
film_iso: "200"
film_color: Colour
film_format: 35mm
category: 📸 Film Type
home: "[[Analog Photography]]"
---

![Harman Phoenix ISO 200](https://www.colorfoto.pt/userfiles/images/loja/produtos/zoom/0019498182099.jpg)

## Reviews

* Review Link

---

## Film Photoshoots

```dataview
TABLE
	film_type AS "Film Type",
	camera AS "Camera",
	status AS "Status"
FROM "Photography/Analog/Photoshoots"
WHERE
	file.name != this.file.name
	AND film_type = [[Harman Phoenix ISO 200]]
SORT session_number DESC
LIMIT 15
```