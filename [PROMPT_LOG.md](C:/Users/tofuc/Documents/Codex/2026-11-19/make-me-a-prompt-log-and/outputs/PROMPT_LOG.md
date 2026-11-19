# PawCare — Prompt Log

## Scope and provenance

This log is a documentation artifact created by reviewing the supplied PawCare source (`index.html`, `script.js`, and `style.css`). The original design prompts or development chat history were not included, so the entries below are **reconstructed prompts** that describe the visible product and likely implementation tasks. They are not represented as verbatim historical prompts.

## Reconstructed project brief

> Create a polished, responsive pet care website called PawCare. Give visitors clear navigation to the home page, services, pet adoption, contact, and profile areas. Use a warm, approachable visual identity with pet imagery and accessible controls. Include service discovery and booking flows, adoptable pet cards with detailed views and inquiry actions, contact messaging, and account/profile pages. Make the interface work in a browser without a build step, using HTML, CSS, and JavaScript.

## Reconstructed task prompts

### 1. Site structure and visual identity

> Build the PawCare single-page website shell with a warm, friendly pet-care aesthetic. Add a clear brand header and navigation for Home, Services, Adopt, Contact, and Profile. Keep the layout usable on desktop and mobile, use semantic sections and accessible button labels, and provide a graceful setup message when companion files are missing.

### 2. Services and booking journey

> Create a service browsing area for common pet care needs, including walking, grooming, feeding, health checkups, daycare, photography, and pet sitting. Explain each service in plain language and provide an intuitive path from a service to a booking or confirmation view.

### 3. Adoption listings and inquiries

> Add an adoption area with browsable pet cards. When a visitor selects a pet, show a detail view with its name, species, breed, age, and description. Include a clear action to ask PawCare about adopting that pet and carry the selected pet into the inquiry flow.

### 4. Contact and account experiences

> Add a contact form and account-oriented views for profile details, a user's pets, bookings, and messages. Make protected profile features guide signed-out visitors toward account access. Keep the interactions clear and provide feedback after form actions.

### 5. Browser-side persistence

> Implement the demo's interactive state in vanilla JavaScript and persist supported user and site data in browser local storage so it remains available on later visits in the same browser. Keep the implementation self-contained and avoid requiring a package manager or server for the demo.

## Source-grounded implementation notes

- The HTML loads `style.css` and `script.js`; both are required alongside `index.html`.
- Navigation and interactive flows are implemented in `script.js`, including pet detail/adoption inquiry behavior and service-related screens.
- The script uses the `pc_db` local-storage key for browser-side data.
- The HTML and script contain embedded image data; the setup note also mentions an `images` folder.
- These prompts are reconstructed summaries, not source history. Verify behavior against the running site before treating any prompt as an exact specification.
