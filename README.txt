KULDEEP MOBILE ADMIN SETUP

1. Upload all files/folders to the root of your GitHub Pages repo.
2. Keep config.js in the root and admin/index.html inside the admin folder.
3. Open https://kuldeepmobile.shop/admin/ and login with the Supabase admin user.
4. Add product photo, name, brand/model, price and offer.
5. Offer posters are stored as rows with title __POSTER__ and the latest poster is shown on the homepage.

IMPORTANT: The homepage keeps the existing products and also shows new admin products under Latest Products. Existing hard-coded products are not yet migrated into Supabase.

Never put a Supabase secret/service key in config.js. The key here is the publishable browser key.
