# OpenLegal website

A static website for OpenLegal, a commercial law firm. The design takes its cues from Webb Henderson (warm off-white backgrounds, light geometric type, charcoal and gold, dark arrow buttons, gold-ruled lists). The content is drawn from openlegal.com.au.

## Pages

| File | Page |
|---|---|
| `index.html` | Home |
| `firm.html` | The Firm, team and client guarantee |
| `practice.html` | Areas of practice |
| `membership.html` | OpenLegal Membership |
| `contact.html` | Enquiry form and offices |

Shared styles are in `assets/styles.css` and the small script (mobile menu, scroll reveal, form message) is in `assets/main.js`.

## Viewing it

Open `index.html` in a browser, or serve the folder:

```bash
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Still to do before going live

- **Enquiry form:** it is not connected to anything yet. Submitting shows a message asking people to call 1300 337 997. Connect it to a form service or the firm's CRM.
- **Team photos:** portraits are placeholders showing initials. Replace the `.portrait` blocks with real photos.
- **Articles:** the three article links point to the existing articles on openlegal.com.au.
- **Review the copy:** content is adapted from the current OpenLegal site and should be checked by the firm before publishing.
