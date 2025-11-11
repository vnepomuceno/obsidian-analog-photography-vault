---
tags:
  - kodak
  - kodak-colorplus
  - iso200
  - analog
  - color-film
  - analog-photography
film_type: Kodak ColorPlus ISO 200
film_iso: "200"
film_color: Colour
film_format: 35mm
category: 📸 Film Type
cover_url: https://i.ebayimg.com/thumbs/images/g/0qAAAOSwP-RlJriB/s-l1200.jpg
---

![Kodak ColorPlus ISO 200](https://i.ebayimg.com/thumbs/images/g/0qAAAOSwP-RlJriB/s-l1200.jpg)

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
	AND film_type = [[Kodak ColorPlus ISO 200]]
SORT session_number DESC
LIMIT 15
```