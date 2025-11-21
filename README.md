# Portfolio — Static site

Simple static personal site for "Mahtab Uddin Ahmed" matching the structure of the referenced Canva page (animations intentionally omitted).

Files:
- index.html — main page
- styles.css — styling
- assets/ — put your profile.jpg, Resume PDF, and favicon here

How to use
1. Replace placeholders:
   - assets/profile.jpg — your headshot
   - assets/Resume-Mahtab-Uddin-Ahmed.pdf — your resume PDF
   - Update email links, phone number, and social links in index.html
2. Optional: enable the contact form:
   - Replace the Formspree action URL in the <form> tag with your Formspree endpoint, or remove the form and keep mailto links.
3. Serve locally:
   - Open index.html in a browser, or run a simple server:
     - Python 3: `python -m http.server 8000`
4. Deploy:
   - Host via GitHub Pages, Netlify, Vercel, or any static hosting.

Customization ideas
- Fonts: add Google Fonts in the head
- Colors: change CSS variables in styles.css
- Add or remove sections as needed

If you want, I can:
- Replace placeholder text with your real bio, roles, and project descriptions
- Configure a contact form (Formspree) or make a small Netlify Function to process messages
- Add minor entrance animations (fade/slide) if you change your mind
