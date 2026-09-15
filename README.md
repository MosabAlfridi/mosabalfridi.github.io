# mosabalfridi.github.io

Personal site for Musab Alfridi — Product Owner at Bonat, founder, and
Vice Chairman of the Hail AI Adoption Initiative.

Live at <https://mosabalfridi.github.io>

Single self-contained `index.html`. Fonts load from Google Fonts; every
image is embedded as a data URI, so there are no other external requests.

## Features

- Full English / Arabic toggle with RTL layout
- Light / dark theme toggle, remembered per browser
- Filterable work list
- Scroll-spy navigation and scroll progress
- Respects `prefers-reduced-motion`

## Editing

The source lives in the private second-brain repo at
`projects/personal-brand/`. Edit `profile.src.html`, then run:

    python build.py         # local build, includes the private LinkedIn copy kit
    python build_public.py  # public build, copy kit stripped

Copy the resulting `site/index.html` here and push.
