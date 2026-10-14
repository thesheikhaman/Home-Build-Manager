HOME BUILD MANAGER PRO

FILES
1. index.html - application page
2. styles.css - responsive colourful styling
3. app.js - purchases, materials, shop ledgers, reports and local backup
4. supabase.js - supplied Supabase project connection
5. schema.sql - database tables and policies

SETUP
1. Keep index.html, styles.css, app.js and supabase.js in the same folder.
2. In Supabase Dashboard, open SQL Editor and run schema.sql once.
3. Open index.html through a local web server. Example: python -m http.server 8080
4. Visit http://localhost:8080

IMPORTANT
The app is fully usable with browser local storage. The current build tests the Supabase connection. Database CRUD helpers are included in supabase.js. The publishable key is visible to browsers by design. Do not insert a Supabase service-role key into these files.
