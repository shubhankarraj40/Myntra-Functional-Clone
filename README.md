# Myntra Clone Website

Welcome to the **Myntra Clone** project! This web application replicates basic functionalities of an e-commerce website like adding products to a bag and calculating the total price. The project is built using HTML, CSS, and JavaScript.

---

## Features

- Add products to the shopping bag.
- Dynamically calculate the total price of selected items.
- User-friendly interface with product images and details.
- Separate pages for the product listing and shopping bag.
- Modular and reusable JavaScript for data handling.

---

## Project Structure

```plaintext
├── css
│   ├── bag.css       # Styles specific to the shopping bag page.
│   ├── index.css     # Styles for the main product listing page.
│
├── data
│   └── items.js      # JavaScript file containing product data (name, price, image, etc.).
│
├── images
│   ├── 1.jpg         # Product image 1.
│   ├── 2.jpg         # Product image 2.
│   ├── ...           # Other product images.
│   └── 8.jpg         # Product image 8.
│
├── pages
│   ├── bag.html      # Shopping bag page displaying selected products.
│   └── index.html    # Main page for browsing products.
│
├── scripts
│   ├── bag.js        # JavaScript for managing shopping bag functionality.
│   └── index.js      # JavaScript for handling product listing interactions.
```

---

## How to Use

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/your-username/myntra-clone.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd myntra-clone
   ```

3. **Open the Application:**
   Open `index.html` in your browser to view the main product page.

4. **View Shopping Bag:**
   Add products to the bag on the main page and navigate to `bag.html` to see the selected items and their total price.

---

## Files Overview

### HTML Files
- **index.html**: Displays the product listing with options to add items to the shopping bag.
- **bag.html**: Shows items added to the shopping bag and calculates the total price dynamically.

### CSS Files
- **index.css**: Contains styles for the main product listing page.
- **bag.css**: Contains styles for the shopping bag page.

### JavaScript Files
- **index.js**:
  - Handles product listing interactions.
  - Manages the functionality to add products to the shopping bag.
- **bag.js**:
  - Retrieves and displays selected items from the bag.
  - Calculates the total price of products dynamically.

### Data File
- **items.js**: Provides structured data for products (e.g., name, price, image).

### Images
- **1.jpg - 8.jpg**: Sample product images for the application.

---

## Screenshots

### Main Product Page
- Displays a list of products with their details.
  ![Screenshot (10)](https://github.com/user-attachments/assets/e1567fc2-a6e5-4524-a17d-8fce3ac2ee94)


### Shopping Bag Page
- Lists items added to the bag with their individual and total prices.
  ![Screenshot (9)](https://github.com/user-attachments/assets/75cbb16b-5917-4785-8fbd-1116dc21e67e)


---

## Technologies Used

- **HTML**: For the structure of the web pages.
- **CSS**: For styling the pages and making them visually appealing.
- **JavaScript**: For interactive functionalities like adding items to the bag and calculating prices.

---

## Future Enhancements

- Add user authentication for a personalized experience.
- Implement a responsive design for better mobile compatibility.
- Integrate a backend for persistent data storage.
- Add search and filtering options for easier product discovery.

---

## Contributing

Feel free to fork this repository and contribute to enhance its features! Submit a pull request for any changes you make.

---

## License

This project is licensed under the [MIT License](LICENSE).

---

Happy Coding! 😊
