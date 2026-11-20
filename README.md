# Kea Blog: Portfolio & Blog

A personal portfolio and reflective blog for **Keatametse Dolly Bosigo**, a first-year BSc Business Intelligence and Data Analytics student in Gaborone, Botswana. The site supports an application for an industrial attachment as a data analyst.

**Live site:** `https://keatametse-dolly.github.io/kea-blog/` *(replace after enabling GitHub Pages)*

## What's on the site

| Section | Contents |
|---|---|
| About | Education, Semester 1 modules and earlier schooling |
| CV | Full CV with a link to the PDF |
| Experience | Hair stylist and class monitress |
| Skills | Excel, Microsoft Dynamics NAV, cashflow planning, communication and more |
| Projects | Sales and inventory database (Microsoft Access) and the Semester 1 group project |
| Excel Visualization | Golema-Mmidi weekly and monthly rainfall charts, with the workbook to download |
| Group project | Embedded "Student Success Plan" presentation (PDF) with the original `.odp` |
| Blog | Two reflective posts: academic journey and group work (Tuckman's stages) |
| Application | Industrial attachment application letter and a copyable email template |
| Gallery | Group study photos |
| Contact | Email link |

The site also has a light/dark theme toggle (the ◐ button in the menu).

## Project structure

```
kea-blog/
├── index.html
├── style.css
├── README.md
├── Keatametse_Bosigo_CV.pdf
├── CT_ASSIGNMENT_KEA.accdb
├── EXCEL_ct_assignment.xlsx
├── assets/
│   ├── portrait.jpg
│   ├── group-1.jpg
│   └── group-2.jpg
└── presentation/
    ├── CSS_Group_Presentation.pdf
    └── CSS_Group_Presentation.odp
```

- `index.html` holds the page content and the JavaScript (blog posts, theme toggle, email copy button, scroll animations).
- `style.css` holds all styling, including dark mode.
- `assets/` holds the images used on the page.
- `presentation/` holds the group presentation (PDF for viewing, ODP as the original).

## Run it locally

No build step or installation is needed.

1. Download or clone this repository.
2. Open `index.html` in any modern web browser.

## Publish with GitHub Pages

1. Go to the repository's **Settings**, then **Pages**.
2. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
3. Choose branch **main** and folder **/ (root)**, then click **Save**.
4. After a minute or two, the site is live at the link shown at the top of the Pages screen.

## Editing the content

- **Blog posts:** edit the `posts` list near the bottom of `index.html`. Each post has an `id`, `title`, `date`, a short `ex` summary and an HTML `body`.
- **Colours:** change the variables at the top of `style.css` (`--bg`, `--fg`, `--acc` and so on).
- **Contact details:** search `index.html` for the email addresses and the P O Box address and replace the placeholders before sharing the site publicly.

## Built with

HTML, CSS and plain JavaScript. There are no frameworks or external dependencies.

## Author

**Keatametse Dolly Bosigo**
BSc Business Intelligence and Data Analytics, Botswana School of Business Sciences
Gaborone, Botswana

## Notes

- The CV, database, Excel workbook and presentation are included for download, so anyone who can see the repository can open them. Keep the repository private if you don't want that.
