# AgroGrowth Technologies

A static front-end prototype for **AgroGrowth Technologies**, a platform dedicated to revolutionizing agricultural trade by connecting farmers directly with industrial buyers. This GitHub Pages–hosted site serves as the marketing and lead-capture portal, laying the foundation for a full-featured agri-marketplace.

---

## Demo

[Live Website](https://ameenkhan12345.github.io/Agrotech-Website/)


---


## Table of Contents

* [Problem Statement](#problem-statement)
* [Core Idea](#core-idea)
* [Features](#features)
* [Tech Stack](#tech-stack)
* [Project Structure](#project-structure)
* [Installation & Deployment](#installation--deployment)
* [Usage](#usage)
* [Future Enhancements](#future-enhancements)
* [Contributing](#contributing)
* [License](#license)



## Problem Statement

Traditional agricultural supply chains are fragmented:

* Farmers rely on multiple middlemen, reducing their profit margins and introducing payment delays.
* Industrial buyers face limited visibility into produce quality, origin, and fair pricing.

AgroGrowth aims to digitize this first mile by providing a two-sided platform for both farmers and industrial buyers.

---

## Core Idea

1. **Farmers** can register, list their produce, and eventually manage offers directly.
2. **Industrial Buyers** can register, browse listings, and place or negotiate orders.
3. This static site functions as the marketing brochure and lead-capture portal, with future plans to integrate dynamic back-end workflows.

---

## Features

* **Full-Width Carousel**: Showcase core messages and highlights.
* **User Segmentation Banner**: Quick access for farmers vs. industrial buyers.
* **Static Registration & Login Pages**: `register.html`, `farmerlogin1.html`, `induslogin1.html`.
* **Responsive Design**: Built with Bootstrap 5 for mobile-first layouts.
* **Custom Styling**: `css/style.css` for branding and visual polish.
* **Footer with Contact & Newsletter**: Lead capture form and social links.

---

## Tech Stack

* **HTML5**
* **CSS3 & Bootstrap 5**
* **JavaScript (jQuery, Owl Carousel)**
* **Font Awesome & Bootstrap Icons**

---

## Project Structure

```
├── index.html            # Landing page
├── register.html         # User registration
├── farmerlogin1.html     # Farmer login
├── induslogin1.html      # Industrial buyer login
├── css/
│   ├── bootstrap.min.css
│   └── style.css         # Custom styles
├── js/
│   └── main.js           # Custom scripts
├── lib/
│   ├── owlcarousel/
│   └── ...               # Additional dependencies
├── img/                  # Images and favicon
└── README.md             # Project overview
```

---

## Installation & Deployment

1. **Clone the repo**

   ```bash
   git clone https://github.com/AmeenKhan12345/Agrotech-Website.git
   cd Agrotech-Website
   ```

2. **(Optional) Preview locally**

   * You can use any static server. For example, with [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer) in VS Code or:

     ```bash
     npx http-server .
     ```

3. **Deploy via GitHub Pages**

   * In your repository, go to **Settings > Pages**.
   * Under **Source**, select branch `main` and folder `/ (root)`.
   * Click **Save**; your site will publish at `https://<your-username>.github.io/<repository-name>/`.

---

## Usage

* Navigate to the live URL.
* Use the top navigation bar to explore sections.
* Click **Register** or **Login** for farmers or industrial buyers to simulate onboarding.

---

## Future Enhancements

* Integrate a back-end (Node.js/Express, Firebase) for form submission and user data storage.
* Replace static forms with real authentication (e.g., Auth0, Firebase Auth).
* Build interactive dashboards for produce listings and order management.
* Optimize assets (minification, image compression) for faster load times.

---

## Contributing

Contributions are welcome! Please:

1. Fork the repository.
2. Create a feature branch: `git checkout -b feature/YourFeature`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/YourFeature`.
5. Open a Pull Request outlining your changes.

---

## License

This project is licensed under the [MIT License](LICENSE).
