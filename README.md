# tasks-vizzy-pages

Public static pages for OAuth consent branding and the **tasks-write** HTTPS
callback bounce. Hosted on Vercel at **tasks-vizzy.technoplusit.co.uk**.

Not the app binaries. App repos stay private:
`lewismarshall/tasks-vizzy`, `lewismarshall/tasks-write`.

## Paths

| Path | Purpose |
| --- | --- |
| `/` | tasks-vizzy homepage (readonly poller branding) |
| `/privacy` | tasks-vizzy privacy policy |
| `/tasks-write/` | **tasks-write** homepage (write CLI branding — distinct from vizzy) |
| `/tasks-write/privacy` | **tasks-write** privacy policy |
| `/oauth/tasks-write` | HTTPS OAuth bounce for tasks-write (`fetch` to localhost CLI; never redirects browser to http; never stores tokens) |

Google Auth Platform for project **tasks-write** must use the `/tasks-write/`
home and privacy URLs — not the vizzy marketing pages. The authorised redirect
URI remains `/oauth/tasks-write`.

## Host

- Vercel project: **tasks-vizzy-pages** (Hobby, Framework Other, no build)
- Custom domain: **tasks-vizzy.technoplusit.co.uk**
- Authorised domain in Google Cloud: `technoplusit.co.uk`
