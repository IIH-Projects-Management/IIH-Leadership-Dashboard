# IIH Leadership Dashboard

Leadership portfolio tracker for IIH (Ideal Innovation House): workstreams, epics, tasks, risks, team, client view, weekly report email and PowerPoint export.

**This is a separate product.** It is not the MoC Dashboard (`MOC-Dashboard`, Firebase `iih-trackers-db`) and not the MoMAH Dashboard (`MoMah-Dashboard`, Excel masterlist). It has its own Firebase project, its own GitHub repository and its own browser settings.

| | IIH Leadership Dashboard | MoC Dashboard | MoMAH Dashboard |
|---|---|---|---|
| GitHub repo | `IIH-Leadership-Dashboard` | `MOC-Dashboard` | `MoMah-Dashboard` |
| Data | its own Firebase project | Firebase `iih-trackers-db` | `masterlist.xlsx` |
| Logo | IIH only | IIH + Ministry of Culture | MoMAH |

## Files
- `index.html` – the dashboard. Paste the Firebase configuration into `firebaseConfig` near the top before publishing.
- `firestore.rules` – security rules for the new Firebase project.

## First admin
`mabukhamseh@iih.ai` is always admin. Sign in with that email, then add people under **Users & Access**.
