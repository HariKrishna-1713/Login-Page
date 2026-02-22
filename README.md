📩 Contact Us – Simple HTML Form
📌 Project Overview

This is a simple Contact Us webpage built using HTML5 and CSS (Flexbox).
The page contains a centered layout with an image and a contact form.

The design focuses on:

Clean layout

Proper spacing (without <br> misuse)

Basic form validation

Responsive centering using Flexbox

🛠 Technologies Used

HTML5

CSS3 (Flexbox)

📂 Project Structure
project-folder/
│
├── index.html
├── image.png
└── README.md
🎯 Features
1️⃣ Layout

Full screen height using height: 100vh

Horizontal and vertical centering using:

display: flex;
justify-content: center;
align-items: center;
2️⃣ Form Fields

The form includes:

First Name (required, 1–20 characters)

Last Name (required, 1–30 characters)

Email (required, valid email format)

Message textarea (1–100 characters)

Submit button

3️⃣ Validation

Uses built-in HTML validation:

required

minlength

maxlength

type="email"

No JavaScript validation is used.

🚀 How to Run the Project

Download or clone the project.

Make sure image.png exists in the same directory.

Open index.html in your browser.

🔄 Form Submission

The form action is:

<form action="/random.py">

This means:

The form sends data to random.py.

You must create a backend Python script to process the form.

Without a backend, submission will not work.

🎨 Styling Highlights

gap property used instead of multiple <br> tags.

Flexbox for layout alignment.

Minimal and clean design.

Inline styling only used for the submit button (can be improved).

⚠ Improvements You Can Make

If you want to level this up:

Add responsive design using media queries.

Replace inline button styling with a CSS class.

Add hover effects on button.

Add backend using Flask or Django.

Add proper labels instead of <br> text.

Example improvement:

<label for="email">Email</label>
<input id="email" type="email" required>
📸 Preview

The page displays:

Left side → Image (400x400)

Right side → Contact Form

Fully centered on the screen

👨‍💻 Author
Koteswar Rao Golagani
