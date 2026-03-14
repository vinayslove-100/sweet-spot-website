
Sweet Spot Desserts 🍰🍩

Welcome to Sweet Spot Desserts, a visually appealing, interactive website designed for dessert shops to showcase their offerings and attract customers. This project combines modern UI design, responsive layouts, and dynamic menu management using HTML, CSS, JavaScript, and Supabase for backend data storage.


---

Table of Contents

1. Project Overview


2. Features


3. Technologies Used


4. Project Structure


5. Installation & Deployment


6. How to Use


7. Owner Section


8. Contributing


9. License




---

Project Overview

Sweet Spot Desserts is a fully designed website for dessert shops to:

Showcase a welcoming, attractive home page with visually engaging UI/UX.

Highlight featured desserts with full-screen hero sections, interactive buttons, and attractive transitions.

Display a dynamic menu of desserts, including images, names, and prices.

Allow shop owners to manage menu items using a secure Owner section powered by Supabase.

Offer customers an easy-to-navigate interface to explore desserts and locations.


The project emphasizes branding, aesthetics, and user experience, making it appealing for both the shop owner and the customer.


---

Features

1. Attractive Home Page

Hero section with smooth top-to-middle transitions.

Engaging background with doodle patterns, cakes, donuts, and desserts illustrations.

Highlighted call-to-action buttons such as “Get In” to guide customers deeper into the website.

Dynamic card sections to showcase:

Shop introduction

Featured desserts

Special events like IPL offers

Location information



2. Dessert Menu

Menu page displaying dessert items in a clean, visually appealing layout.

Images of desserts with names and prices.

Responsive grid layout for better customer experience.

Integrates with Supabase backend for real-time updates.


3. Owner Section

Secure owner login page (can be enhanced with Supabase Auth).

Allows shop owner to add, update, and remove desserts.

Supports image upload to Supabase Storage or external links.

Changes reflect instantly on the menu page for customers.


4. Full-Screen Layout

Website optimized to fit screen without scrolling for a seamless look.

Attractive typography, golden accents, and dessert patterns throughout the design.


5. Deployment

Fully deployable on Netlify, Vercel, or any static hosting.

GitHub repository allows version control and collaborative development.



---

Technologies Used

Technology	Purpose

HTML5	Structure and layout of the website
CSS3	Styling, animations, transitions, and responsive design
JavaScript	Dynamic behaviors, button transitions, and interactivity
Supabase	Backend database for dessert items, storage, and auth
Git/GitHub	Version control and repository hosting
Netlify	Web hosting and deployment



---

Project Structure

sweet-spot-website/
│
├── index.html       → Home page with hero, cards, and transitions
├── menu.html        → Customer menu page
├── owner.html       → Owner dashboard for managing menu items
├── havehome.html    → Alternate or previous home page (optional)
├── style.css        → Global styles and design elements
├── script.js        → Optional JavaScript for animations, transitions, and menu updates
└── README.md        → Project documentation


---

Installation & Deployment

1. Clone the Repository

git clone git@github.com:vinayslove-100/sweet-spot-website.git
cd sweet-spot-website

2. Open Locally

Open any of the HTML files in a browser:

termux-open index.html

Or just double-click in your OS file explorer.

3. Deploy Online

Upload the project to Netlify or Vercel for live access:

1. Drag and drop the repository folder to Netlify dashboard


2. Or link your GitHub repo to automatically deploy





---

How to Use

For Customers

1. Open index.html in a browser.


2. Explore the hero section with dessert animations and call-to-action.


3. Click “Get In” to enter the main website.


4. Navigate to Menu to see all desserts with images, names, and prices.



For Owners

1. Open owner.html in a browser.


2. Add new desserts by filling name, price, and image link.


3. Save the changes — menu page updates in real-time using Supabase.


4. Optionally, remove or edit existing items from the Owner dashboard.




---

Owner Section (Supabase)

Uses Supabase as the backend database:

Table: desserts → columns: id, name, price, image_url

Table policies ensure secure read/write access.


Supports image uploads via Supabase Storage or external image URLs.

Real-time database updates make menu dynamic and maintainable.



---

Contributing

1. Fork the repository on GitHub.


2. Clone your fork locally.


3. Create a new branch for changes:



git checkout -b feature/awesome-dessert

4. Make changes, add, commit, and push:



git add .
git commit -m "Add chocolate lava cake"
git push origin feature/awesome-dessert

5. Open a Pull Request on the main repository.




---

License

This project is open for personal and educational use.

You can modify and deploy it for your dessert shop.

If used commercially, please credit the author.



---

Screenshots

Home Page



Menu Page



Owner Dashboard




---

Future Enhancements

Add owner authentication with Supabase Auth

Enable real-time editing of menu for multiple owners

Add filtering by dessert type

Integrate cart and checkout for online ordering

Make fully responsive for mobile and tablet



---

Author

Vinay raj

Email: d20298349@gmail.com

GitHub: https://github.com/vinayslove-100
