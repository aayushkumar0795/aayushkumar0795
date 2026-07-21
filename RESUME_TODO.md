# TODO before the site is fully live

1. **`resume.pdf`** — drop your resume as `resume.pdf` in the repo root.
   Both "Download Resume" buttons (hero + contact footer) link to `./resume.pdf` and will 404 until it exists.

2. **`aayush.jpg`** — drop your profile photo as `aayush.jpg` in the repo root.
   The hero portrait frame and the Open Graph / Twitter card image both point to it.
   Until then the frame shows a "file not found" placeholder.

3. **Formspree ID** — create a free account at [formspree.io](https://formspree.io), create a form,
   and replace `FORMSPREE_ID` in `index.html` (search for it — one spot in the contact form's
   `action` attribute) with your real form ID. Until then the form's error state kicks in and
   points visitors to your email instead.

4. **Project links** — each project card has an `href="#"` link with a `data-todo` attribute and
   an HTML comment listing what to supply (public repo URL, TestFlight link, or screenshots page).
   The MCP servers card must point to a clean-room public rebuild — not IBM code.

Delete this file once done.
