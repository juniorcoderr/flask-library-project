# 📚 Flask Library Manager

A simple and intuitive web-based library management system built with Flask and SQLAlchemy. Keep track of your personal book collection with an easy-to-use interface.

## ✨ Features

- **📖 View Library**: Browse your entire book collection in a clean, organized list
- **➕ Add Books**: Easily add new books with title, author, and rating information
- **✏️ Edit Ratings**: Update book ratings as your opinions change
- **🗑️ Remove Books**: Delete books from your collection
- **🎯 Smart Rating Input**: Supports both decimal (8.5) and fraction (9/10) rating formats
- **💾 Persistent Storage**: Uses SQLite database to save your data

## 🛠️ Technologies Used

- **Backend**: Flask (Python web framework)
- **Database**: SQLAlchemy ORM with SQLite
- **Frontend**: HTML templates with Jinja2
- **Styling**: Clean, minimal HTML interface

## 📋 Prerequisites

- Python 3.11+ (recommended for best compatibility)
- pip (Python package manager)

## 🚀 Quick Start

1. **Clone the repository**
   ```bash
   git clone https://github.com/juniorcoderr/flask-library-project.git
   cd flask-library-project
   ```

2. **Create a virtual environment**
   ```bash
   python -m venv .venv
   source .venv/bin/activate  # On Windows: .venv\Scripts\activate
   ```

3. **Install dependencies**
   ```bash
   pip install flask flask-sqlalchemy
   ```

4. **Run the application**
   ```bash
   python main.py
   ```

5. **Open your browser**
   Navigate to `http://127.0.0.1:5000` to start managing your library!

## 📁 Project Structure

```
flask-library-manager/
├── main.py              # Main application file
├── templates/
│   ├── index.html       # Home page template  
│   ├── add.html         # Add book form
│   └── edit_rating.html # Edit rating form
├── books.db            # SQLite database (created automatically)
└── README.md           # This file
```

## 🎯 Usage

### Adding a Book
1. Click "Add New Book" on the home page
2. Fill in the book title, author, and rating
3. Rating can be entered as:
   - Decimal: `8.5`, `9.2`
   - Fraction: `9/10`, `8/10`

### Editing a Rating
1. Click "Edit Rating" next to any book
2. Enter the new rating and submit

### Deleting a Book
1. Click "Delete" next to any book to remove it from your library

## 🔧 Customization

- **Database**: The app uses SQLite by default. You can change the database URL in `main.py`
- **Styling**: Add CSS to the HTML templates to customize the appearance
- **Features**: Extend the Book model to include additional fields like genre, publication date, etc.

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🐛 Known Issues

- Requires Python 3.11+ for best compatibility with SQLAlchemy
- Basic styling - UI could be enhanced with CSS frameworks

## 💡 Future Enhancements

- [ ] Search and filter functionality
- [ ] Book cover image support
- [ ] Export library to CSV/PDF
- [ ] Reading status tracking (to-read, reading, completed)
- [ ] Book recommendations
- [ ] Responsive mobile design

---

⭐ If you found this project helpful, please give it a star!
