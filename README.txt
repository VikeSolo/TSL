Race Timer with simple password login (Admin: admin123, Viewer: user123)
Files:
- login.html  : Login page (choose Admin or Viewer)
- index.html  : Viewer (requires login)
- admin.html  : Admin (requires admin login)
- script.js   : Shared JS for timer & drivers (uses Firebase Realtime DB compat)
- style.css   : Racing theme
- vercel.json : Vercel routing (deploy root)
Notes:
- This login is client-side only; session stored in sessionStorage.
- For production, use Firebase Auth or a server-side auth method.
- To deploy to Vercel: upload the unzipped folder (do not upload the ZIP file).
