# BaliStayora website files

## Files
- `index.html` — homepage, villa search/filter and Monthly/Yearly submenu.
- `villa.html` — villa detail page, opened with `villa.html?id=v1`.
- `admin.html` — local admin form for creating/editing villa listings and setting optional promotions.

## Deploy to GitHub Pages
1. Upload these files to the root of your GitHub repository.
2. If publishing with GitHub Pages, choose the correct branch and `/ (root)` folder in repository Settings → Pages.
3. The homepage must be named `index.html`.
4. Open `admin.html` to create listings. Download the ZIP publish package and upload `villas.json` plus its `images/` folder to the same root as `index.html`.
5. Villa detail URLs look like `villa.html?id=YOUR_VILLA_ID`.

## Important notes
- The admin page saves drafts in the current browser's local storage. It does not synchronize data between browsers or devices and does not provide login protection. Protect the admin URL before using it publicly.
- The detail-page inquiry uses the visitor's email app (`mailto:`). This requires an email app to be configured. For server-side inquiry storage or automated email delivery, connect a backend/form service.
- Replace sample villa records and placeholder photos with real, verified listing data before launch.
- Optional promotions are stored on each villa. Dates control whether the promotion appears on the detail page.
