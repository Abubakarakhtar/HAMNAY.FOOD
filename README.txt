HAM-NAY FOODS — Ready-to-deploy static website

FILES
- index.html: responsive menu with 16 dishes, cart, price calculations, and WhatsApp order flow
- vercel.json: Vercel configuration
- assets/: locally bundled dish photos supplied for this update

DEPLOY TO VERCEL
1. Extract this ZIP.
2. Upload index.html, vercel.json, README.txt, and the complete assets folder to the root of your GitHub repository.
3. Import the repository at https://vercel.com and deploy as a static site (no build command required).
4. Keep the assets folder beside index.html so dish pictures display correctly.

MENU / CONTACT
The existing menu names, prices, and three phone numbers were preserved.
WhatsApp checkout opens a prefilled message to 0300 4583050 (+92 300 4583050).
Most menu photos are bundled locally in assets/. Raita keeps its existing external photo URL because no separate raita photo was among the uploaded pictures.
This is a static frontend; it does not store orders in a database or provide a private admin panel.
