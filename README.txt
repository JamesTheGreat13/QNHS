QNHS PORTAL STARTER FILES

FILES
- index.html: portal home and role selection
- login-admin.html / login-student.html / login-teacher.html
- register-admin.html / register-student.html / register-teacher.html
- dashboard-admin.html / dashboard-student.html / dashboard-teacher.html
- styles.css: shared purple-pink glassmorphism styling

ADD YOUR IMAGES
1. Open styles.css and replace:
   PASTE_YOUR_BACKGROUND_IMAGE_LINK_HERE
   with a direct image URL, for example https://example.com/school.jpg

2. In every HTML file, replace:
   PASTE_YOUR_TRANSPARENT_LOGO_LINK_HERE
   with the direct PNG URL for your transparent logo.

HOW TO USE
Keep all files in the same folder. Open index.html in a browser.
All links are local relative href links, so keep the filenames unchanged.

IMPORTANT SECURITY / FUNCTIONALITY NOTE
This is a front-end starter template only. The login forms currently navigate
to role-specific dashboard pages using GET. They do NOT authenticate users,
store accounts, or securely register users. Do not use this as a real login
system until connected to a backend (such as PHP + database, Node.js, or a
managed authentication service). Never send real passwords in URL query strings.
