# tasks-vizzy-pages

Public homepage + privacy policy for the **tasks-vizzy** OAuth consent screen.

Not the app. The app repo stays private: `lewismarshall/tasks-vizzy`.

Two static pages:

- `/` — what it is
- `/privacy` — privacy policy (same origin)

## Host

- Vercel project: **tasks-vizzy-pages** (Hobby, Framework Other, no build)
- Custom domain (DNS bot): **tasks-vizzy.technoplusit.co.uk**
- Branding URLs once live: `https://tasks-vizzy.technoplusit.co.uk/` and `/privacy`
- Authorised domain in Google Cloud: `technoplusit.co.uk`

After Vercel deploy, add the custom domain and send the CNAME target to the DNS operator. Do not make `lewismarshall/tasks-vizzy` public.
