# Furry Baby 🐾

**The Pet Boutique Where Chic Meets Chew Toys**

Furry Baby is a multi-page website for a fictional upscale pet boutique in Hyde Park Village, Tampa, FL. It's built with plain HTML5 and CSS3, with no frameworks or build tools.

🔗 **Live site:** [jennamick.github.io/furry-baby]

                (https://jennamick.github.io/furry-baby)

---

## Pages

| Page | File | What's on it |
|------|------|--------------|
| Home | `index.html` | Hero banner, tagline, and a Featured Items section |
| Petwear | `petwear.html` | Cold-weather and everyday clothing, plus a dog sizing chart |
| Playtime | `toys.html` | Rope, squeaky, and snuggle toys |
| Essentials | `essentials.html` | Beds, collars, and bowls |
| About | `about.html` | The boutique's story and mission |
| Contact | `contact.html` | Contact form with a newsletter sign-up option |

## Features

- **Consistent layout:** every page shares the same header, navigation bar, and footer
- **Active nav state:** the current page is highlighted in the menu (`class="active"`)
- **Product galleries:** items are grouped by category with images and product names
- **Responsive sizing table:** the Petwear sizing chart sits in a `.table-responsive` wrapper so it scrolls on small screens
- **Accessible form:** each input has a matching `<label>`, the name and email fields are required, and the email field checks the format
- **Descriptive alt text** on all product images
- **Mobile-ready:** viewport meta tag on every page

## Built With

- HTML5 (semantic elements: `header`, `nav`, `main`, `section`, `footer`)
- CSS3 (one shared stylesheet, `style.css`)

## Project Structure

```
furry-baby/
├── index.html
├── petwear.html
├── toys.html
├── essentials.html
├── about.html
├── contact.html
├── style.css
├── README.md
└── *.png            # product and banner images
```

## Running Locally

No installation is needed.

1. Clone the repository:
   ```bash
   git clone https://github.com/jennamick/furry-baby.git
   ```
2. Open `index.html` in any web browser.

## Notes

- The contact form uses a `mailto:` action, so submitting it opens the visitor's email app. It doesn't send data to a server.
- Furry Baby is a portfolio project. The store, products, and email address are fictional.

## Author

**Jennifer Amick**
Web Development student, St. Petersburg College
GitHub: [@jennamick](https://github.com/jennamick)