# Rajpoot Hospital — Interactive HMS Demo

This repository contains a **static, fictional-data prototype** for the Rajpoot Hospital Management System.

## Publish using GitHub Pages

1. Create a **public GitHub repository**, e.g. `rajpoot-hospital-demo`.
2. Upload `index.html`, `.nojekyll`, and `README.md` to the repository root on the `main` branch.
3. In the repository, go to **Settings → Pages**.
4. Under **Build and deployment**, select **Deploy from a branch**, `main`, `/ (root)`, then **Save**.
5. After GitHub Pages finishes publishing, visit `https://YOUR-USERNAME.github.io/rajpoot-hospital-demo/`.

For a private repository, GitHub Pages availability depends on your account and repository settings. The published web page can be public even if its source repository is private.

## Prototype functionality

- Role views for Administrator/IT, Doctor, Pharmacist, and Lab Operator.
- Patient registry, patient history, consultation/diagnosis/prescriptions, lab reports and appointments.
- Browser localStorage saves **demo changes on the viewer's own device**. Visitors do not share a database.
- Use **Reset demo data** to restore fictional sample records.

## Security notice

This is **not production software**: it has no real login, backend, verified role enforcement or compliant clinical records storage. A GitHub Pages website is publicly viewable. **Never enter real patient information** into this prototype.