# Hack-Attack Website

## Overview

The Hack-Attack website is a promotional platform for the "Hack-Attack" hackathon event held at Anurag University, Hyderabad, Telangana, on December 3-7, 2024. The website showcases event details, sectors, domains, schedules, sponsors, gallery, FAQs, and more, providing participants with all necessary information.

## Features

- **Responsive Navigation**: Bootstrap-based navbar with links to key sections (Home, Problem Statement, Sponsors, About, Schedules, Gallery, FAQ, Contact).
- **Carousel Slider**: Displays event highlights with background images and call-to-action buttons.
- **Countdown Timer**: Shows time remaining until the event start.
- **Sectors and Domains**: Lists hackathon focus areas (e.g., AI/ML, Fintech, IoT) with downloadable problem statements.
- **Event Schedule**: Timeline of bootcamps, hackathon, Firecamp, and DJ Night.
- **Chief Guests and Sponsors**: Highlights notable guests and sponsoring partners.
- **Gallery and FAQs**: Photo gallery with lightbox and accordion-style FAQs.
- **Newsletter Signup**: Form for users to subscribe to updates.
- **Google Map**: Embedded map showing Anurag University’s location.

## Project Structure

```
hack-attack/
├── assets/
│   ├── css/
│   │   ├── bootstrap.min.css
│   │   ├── chits.css
│   │   ├── time.css
│   │   ├── sector.css
│   │   ├── nivo-lightbox.css
│   │   ├── animate.css
│   │   ├── main.css
│   │   ├── download.css
│   │   ├── card.css
│   │   ├── responsive.css
│   ├── fonts/
│   │   ├── LineIcons.css
│   ├── js/
│   │   ├── jquery-min.js
│   │   ├── popper.min.js
│   │   ├── bootstrap.min.js
│   │   ├── jquery.easing.min.js
│   │   ├── scrolling-nav.js
│   │   ├── jquery.countdown.min.js
│   │   ├── wow.js
│   │   ├── nivo-lightbox.js
│   │   ├── main.js
│   │   ├── form-validator.min.js
│   │   ├── contact-form-script.min.js
│   ├── img/
│   │   ├── logo.png
│   │   ├── SponsersParteren.png
│   │   ├── bg.png
│   │   ├── img1.jpg
│   │   ├── img2.jpg
│   │   ├── img.jpg
│   │   ├── about.png
│   │   ├── IMG_0518[1].PNG
│   │   ├── comingsoon.png
│   ├── gallery/
│   │   ├── IMG_0360.JPG
│   │   ├── IMG_0306.JPG
│   │   ├── IMG_0283.JPG
│   │   ├── IMG_0927.JPG
│   │   ├── IMG_0201.jpg
│   │   ├── IMG_0199.jpg
│   ├── sponcers/
│   │   ├── sponcer1.png
│   │   ├── sponcer2.png
│   │   ├── sponcer3.png
│   │   ├── sponcer4.png
│   ├── pdfs/
│   │   ├── AIML HackAttack.pdf
│   │   ├── App_Development HackAttack.pdf
│   │   ├── Cyber_Security HackAttack.pdf
│   │   ├── IOT HackAttack.pdf
│   │   ├── Block_Chain HackAttack.pdf
├── index.html
├── LICENSE
├── README.md
```

## Technologies Used

- **HTML5**: Structure of the website.
- **CSS3**: Styling with custom CSS and Bootstrap 4.
- **JavaScript**: Interactivity with jQuery, WOW.js, Nivo Lightbox, and other libraries.
- **Bootstrap 4**: Responsive grid system and components.
- **Boxicons & LineIcons**: Icons for visual elements.
- **External CDNs**: Boxicons, LineIcons, Cloudflare Insights.

## Setup Instructions

1. **Clone or Download**:
   - Clone the repository or download the project files.

2. **Local Server**:
   - Use a local server (e.g., XAMPP, WAMP, or Node.js `http-server`) to serve the files, as some features (e.g., PDF downloads) require a server environment.
   - Example with Node.js:
     ```bash
     npm install -g http-server
     http-server .
     ```
   - Access the website at `http://localhost:8080`.

3. **Dependencies**:
   - No additional installations are needed, as all dependencies are linked via CDNs or included in the `assets` folder.

4. **File Placement**:
   - Ensure the `assets` folder is in the same directory as `index.html`.
   - Verify that all image, CSS, JS, and PDF paths in `index.html` match the folder structure.

5. **Browser Compatibility**:
   - Tested on modern browsers (Chrome, Firefox, Edge). Ensure JavaScript is enabled for animations and interactivity.

## Usage

- Navigate through sections using the top navbar.
- Download problem statements from the "Problem Statement" section.
- View the event gallery with lightbox functionality.
- Subscribe to the newsletter via the signup form.
- Check the embedded Google Map for the event location.

## Contributing

Contributions are welcome! Please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make changes and commit (`git commit -m "Add feature"`).
4. Push to the branch (`git push origin feature-branch`).
5. Create a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For inquiries, reach out via the event’s Instagram: [hackattack1.0](https://www.instagram.com/hackattack1.0/).