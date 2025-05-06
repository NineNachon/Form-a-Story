# 📝 Form a Story

**Form a Story** is a fun and interactive HTML-based web application that allows users to complete a short form and generate a personalized story using their inputs.

## 🌐 Live Demo

[Click here to try it out!](#)  
*(Add link if hosted online)*

---

## 📁 Project Structure

project/
├── index.html # Main form page
├── story.html # Page to display the generated story (to be created)
├── style.css # Styling for the site
└── README.md # Project documentation

yaml
Copy
Edit

---

## 🚀 How It Works

1. The user fills in a form with:
   - 3 animals
   - 1 adjective (ending in -ed)
   - 1 verb (ending in -ing)
   - A number
   - A yes/no choice
   - A comparative speed (e.g., faster, slower)
   - A motivational quote
   - A meaningful message

2. On submission, the form sends the data via URL parameters (`GET` method) to `story.html`.

3. `story.html` reads the inputs and creates a custom, dynamic story based on them. *(You will need to implement `story.html` to parse and use the data.)*

---

## 📦 Requirements

This project uses only vanilla HTML and CSS. No additional libraries or frameworks are needed.

---

## ✅ To Do

- [x] Create the HTML form
- [ ] Build `story.html` to render a story using the query parameters
- [ ] Style the pages using `style.css`
- [ ] Add JavaScript for better UX (optional)

---

## 🛠️ Author Notes

This project is great for beginners learning:
- HTML form structure and validation
- GET method and URL parameter usage
- Interlinking static web pages

---

## 📜 License

MIT License – free to use, modify, and distribute.
