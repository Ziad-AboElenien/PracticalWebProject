# 🍽️ Meal Done – React Meals Explorer

A complete meals browsing app built with React + Vite, using TheMealDB API to display meals, ingredients, areas, categories, and full meal details.

## 🚀 Demo

**Live Demo:** [https://meal-done.vercel.app/]([https://meal-done.vercel.app/](https://practical-web-project.vercel.app/))

## 🧰 Tech Stack

- **React.js** - Frontend library
- **Vite** - Build tool
- **React Router DOM** - Client-side routing
- **CSS** - Styling
- **TheMealDB API** - Meals data
- **Vercel** - Deployment platform

## 📌 Features

### 🔍 Search
- Search meals by name
- Search meals by first character

### 🍽️ Browse
- Browse meals by category
- Browse meals by area
- Browse meals by ingredients

### 📄 Details Page
- Full meal details
- Cooking instructions
- Ingredients list with measurements
- YouTube video tutorial

### 🧭 Navigation
- Fully responsive navbar
- Fast client-side routing
- Smooth user experience

### 🛠️ Extra
- Custom 404 Not Found page
- Clean folder structure
- Reusable components
- Responsive design for all devices

## 📁 Project Structure

```
src/
├── assets/                 # Images and static files
├── components/            
│   ├── CardArea/          # Area card component
│   ├── Cardcat/           # Category card component
│   ├── Cardingrad/        # Ingredient card component
│   ├── Cardmeal/          # Meal card component
│   ├── Footer/            # Footer component
│   └── Navbar/            # Navigation bar component
├── Pages/                 
│   ├── Area/              # Browse by area page
│   ├── Categories/        # Browse by category page
│   ├── Contact/           # Contact page
│   ├── Home/              # Home page
│   ├── Ingrediants/       # Browse by ingredients page
│   ├── Mealdetails/       # Meal details page
│   ├── NotFound/          # 404 page
│   └── Search/            # Search page
├── App.jsx                # Main app component
├── main.jsx               # Entry point
└── index.css              # Global styles
```

## ⚙️ Installation & Setup

### Prerequisites
- Node.js (version 14 or higher)
- npm or yarn

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/Ziad-AboElenien/meal-done.git
   cd meal-done
   ```

2. **Install dependencies:**
   ```bash
   npm install
   ```

3. **Run the development server:**
   ```bash
   npm run dev
   ```
   The app will be available at `http://localhost:5173`

4. **Build for production:**
   ```bash
   npm run build
   ```

5. **Preview production build:**
   ```bash
   npm run preview
   ```

## 🌍 Deployment on Vercel

The project includes a `vercel.json` file to enable proper SPA routing:

```json
{
  "rewrites": [
    {
      "source": "/(.*)",
      "destination": "/"
    }
  ]
}
```

This configuration ensures that React Router handles all paths correctly, preventing 404 errors on page refresh.

### Deploy to Vercel

1. Push your code to GitHub
2. Import your repository on [Vercel](https://vercel.com)
3. Vercel will automatically detect the settings
4. Click "Deploy"

## 📝 API Documentation

**TheMealDB API:** [https://www.themealdb.com/api.php](https://www.themealdb.com/api.php)

### Endpoints Used:

| Endpoint | Description |
|----------|-------------|
| `/search.php?s={meal_name}` | Search meals by name |
| `/search.php?f={first_letter}` | Search meals by first letter |
| `/categories.php` | Get all meal categories |
| `/list.php?a=list` | Get all areas/countries |
| `/list.php?i=list` | Get all ingredients |
| `/lookup.php?i={meal_id}` | Get meal details by ID |
| `/filter.php?c={category}` | Filter meals by category |
| `/filter.php?a={area}` | Filter meals by area |
| `/filter.php?i={ingredient}` | Filter meals by ingredient |

## 🎨 Screenshots

*(Add screenshots of your app here)*

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1. Fork the project
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📧 Contact

**Ziad AboElenien**

- GitHub: [@Ziad-AboElenien](https://github.com/Ziad-AboElenien)
- Project Link: [https://github.com/Ziad-AboElenien/meal-done](https://github.com/Ziad-AboElenien/meal-done)

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [TheMealDB](https://www.themealdb.com/) for providing the free meals API
- [React](https://react.dev/) team for the amazing library
- [Vite](https://vitejs.dev/) for the blazing fast build tool

---

⭐ **If you like this project, please give it a star!** ⭐

**Happy Cooking! 🍳👨‍🍳**
