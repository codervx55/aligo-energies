# Aligo Energies website rebuild

Responsive multi-page static website for Netlify.

## Run locally
Open this folder in VS Code and use the Live Server extension, or run `python -m http.server 8000` from this folder and open http://localhost:8000.

## Pages
Home, About, Project, Products, Sustainability, Investors, News, Gallery, Downloads, Contact.

## Replace reference images before public launch
The current hero and cassava-drying images are reference assets from the prior work, not verified photographs of the exact Aligo facility. Replace them with approved, high-resolution photographs from the actual project site. Keep the filenames or update references in HTML. Do not present illustrative photos as the actual refinery.

- `assets/images/hero-harvest-reference.jpg` — homepage and project agricultural context
- `assets/images/cassava-drying-reference.jpg` — homepage story and gallery
- `assets/images/aligo-logo.jpg` — company logo asset

## Forms and downloads
The contact form opens the visitor's email app using `mailto:`; it is not a server-backed form. Connect a form provider before relying on web submissions. The Downloads page intentionally has no fake download links; add approved PDFs before launch.

## Deployment
Upload the folder contents to a Netlify site or connect the repository. Keep all relative paths intact.

## Before CEO review / launch
1. Replace reference imagery with genuine site photos and approved captions.
2. Verify current construction status and all project figures.
3. Confirm investment language and obtain approval for published funding statements.
4. Add approved company profile, project overview and product documents.
5. Test every page on physical mobile devices and desktop browsers.
6. Connect a proper form service if direct form submission is required.

## Accuracy note
Project capacity, annual target output, expected employment, phase timing, and funding details are shown as planning targets or project-stated ambitions, not independently verified operational results or guaranteed financing.
