# sangava.com

Personal site of Pratik Kesapure, plus the public legal pages for ChatZone.

| Path | Page |
|---|---|
| `/` | Portfolio (`index.html`) |
| `/ChatZone-Privacy` | ChatZone Privacy Policy |
| `/ChatZone-Terms` | ChatZone Terms of Service |
| `/ChatZone-Child-Safety` | ChatZone Child Safety Standards |
| `/ChatZone-Delete-Account` | ChatZone account deletion |

Plain static HTML, hosted on Vercel (project `portfolio`, team `sangava`). `vercel.json`
enables clean URLs, so `/ChatZone-Terms` serves `ChatZone-Terms.html`.

Deploy:

```bash
npx vercel deploy --prod --scope sangava
```
