# PawCare

PawCare is a browser-based pet care and adoption website. It brings pet services, adoptable pet listings, contact, and account tools together in one interface.

## Features

- Browse the home, services, adoption, contact, and profile areas using the site navigation.
- View pet listings and open a detail view with species, breed, age, and an adoption inquiry action.
- Explore pet care services such as walking, grooming, feeding, health checkups, daycare, photography, and sitting; the interface includes service booking flows.
- Use account-oriented pages for profile, pets, bookings, and messages.
- Store supported demo account and site data in browser `localStorage` under `pc_db`.
- Responsive viewport setup and custom visual design with embedded image assets.

## Run locally

Keep `index.html`, `style.css`, and `script.js` together in the same directory. Open `index.html` in a current browser. No package installation or build step is required. The page loads Google Fonts from the network; the browser will use fallback fonts if those are unavailable.

The site displays a setup note if its companion files are missing. The `images` folder is referenced by that note, but the supplied page also embeds substantial image data directly in the HTML and JavaScript.

## Data and deployment notes

This is a front-end demonstration. Its local data is stored in the current browser profile, so it is not shared between visitors or devices and may be cleared by the browser. The inspected source does not include a server API or database integration. Do not treat the client-side account and booking flows as production authentication or a real booking system. A production launch would need a secure backend, validation, privacy and security review, and operational contact/booking handling.

## Project files

- `index.html` — page structure, embedded graphics, and links to the stylesheet and script.
- `style.css` — layout, colors, responsive behavior, and presentation.
- `script.js` — navigation, interactive views, forms, and browser-side data behavior.

## Contact shown in the site

The page displays `PawCare09@gmail.com` as its contact address.
