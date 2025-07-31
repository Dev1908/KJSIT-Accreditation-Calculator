# KJSIT-Accreditation-Calculator
🎯 Overview
The KJSIT Accreditation Calculator is a web-based automation tool developed to streamline and digitize the computation of accreditation metrics—particularly NBA Criteria 4 and 5—for the K. J. Somaiya Institute of Technology. It helps faculty and administrators reduce manual effort and improve accuracy in reporting academic and administrative data.

This tool was built using PHP, HTML/CSS, and connects to a MySQL backend (through config.php) to handle form data and dynamically compute evaluation scores.

⚙️ Features
🧾 Automated calculation of NBA Criteria 4 & 5 values.

🖥️ User-friendly web interface with forms for various NBA sub-criteria (4.1, 4.2, 5.1, etc.).

🔒 Login/Logout functionality for secure access.

🎨 Clean and responsive UI with custom CSS.

🧮 Reduction in manual effort by approximately 60%, increasing institutional efficiency and accuracy.

🛠️ Tech Stack
Frontend: HTML, CSS

Backend: PHP

Database: MySQL (via config.php connection)

Other Assets: SVG/PNG graphics for branding and UI

KJSIT_Accreditation_Calculator/
│
├── homepage.html                # Landing page
├── login.php                   # Login functionality
├── logout.php                  # Logout script
├── config.php                  # DB configuration
├── 4.1FORM.php                 # Criteria 4.1 input
├── 5.1_form.php                # Criteria 5.1 input
├── criteria4.php, criteria5.2.php, ...  # Logic for other sub-criteria
├── *.css                       # Custom stylesheets
├── *.svg / *.png / *.jpg       # Visual assets

