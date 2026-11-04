# Campus — Student Profiling

A responsive frontend project using HTML5, CSS3, vanilla JavaScript, and Bootstrap 5.3.3. No backend, database, build process, or package installation is required.

## Run
Extract the ZIP and open `index.html` in a modern browser. For consistent localStorage behavior, you can also open the folder using VS Code Live Server. Bootstrap is bundled locally, so the project runs offline.

## Files
- `index.html`: semantic page structure, directory, Bootstrap modal, and profile drawer.
- `styles.css`: colors, layout, responsive styles, component appearance.
- `app.js`: sample data, browser storage, validation, search, filters, pagination, sorting, CRUD, program insights, and CSV export.
- `vendor/bootstrap.min.css`: Bootstrap framework styles, separate from custom CSS.
- `vendor/bootstrap.bundle.min.js`: Bootstrap components with Popper, separate from application logic.
- `vendor/BOOTSTRAP-LICENSE.txt`: Bootstrap MIT license.

## Use
Use Add student to create a record. Click View to open a profile, edit its details, or delete it after confirmation. Search by name, ID or email; combine program, year, and status filters. Export CSV downloads all matching students, across pages. Program insights summarizes all records. Press `/` to focus search.

IDs and emails must be unique (case-insensitive). Required fields and email syntax are validated. Changes are saved to `localStorage` under `campus-student-profiles-v1`. If storage is unavailable, the app shows a message and continues in memory.

## Customize
Change sample students and program names in `app.js`. Change colors in the `:root` variables in `styles.css`. Edit headings and labels in `index.html`.

## Demo limitations
All included students are fictional and use example.com addresses. Initial sample profiles receive today's creation date. This project has no authentication, access control, server validation, shared storage, or real enrollment integration. Browser storage is readable by scripts on the same origin and can be cleared by the user. Use fictional data for demonstrations; do not deploy this as a production repository of personal student information.

Bootstrap 5.3.3: https://getbootstrap.com/ — MIT licensed.
