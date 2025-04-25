# CSE326 Internet Programming Laboratory

# FreelanceHub

![FreelanceHub Logo](images.png)  
**FreelanceHub** is a web-based platform designed to connect freelancers and job posters globally. Whether you're a job seeker looking for opportunities or an employer posting jobs, FreelanceHub offers a seamless experience with features like job posting, time tracking, and secure payment processing.

**[Visit Live Site]([https://freelancehub-cse326.netlify.app/])**

## Features

- **Modern UI**: Responsive design with Tailwind CSS and smooth animations using Animate.css.
- **Dynamic Hero Section**: A slideshow with three transitioning background images on the homepage for an engaging user experience.
- **Job Management**:
  - **Job Seekers**: Browse and take available jobs, log hours, and generate invoices.
  - **Job Posters**: Post jobs with details like title, duration, budget, and complexity.
- **Time Tracking**: Log work hours and generate invoices based on hourly rates and job budgets.
- **Contact Us**: A dedicated page with a form, contact information, and social media links.
- **Local Storage**: Jobs and time logs are stored locally using `localStorage` for persistence.
- **Accessibility**: Semantic HTML and ARIA attributes for better usability.

## Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Styling**: Tailwind CSS (via CDN)
- **Animations**: Animate.css (via CDN)
- **Excel Parsing**: SheetJS (XLSX) for time tracking (via CDN)
- **Icons**: Font Awesome (via CDN, used in Contact Us page)
- **Hosting**: Netlify

## Project Structure

```
FreelanceHub/
├── index.html              # Homepage with slideshow
├── contact.html            # Contact Us page
├── seeker.html             # Job Seeker login
├── job_poster.html         # Job Poster login
├── job_posting.html        # Job posting and management
├── seeker2.html            # Time tracking and invoice generation
├── available_jobs.html     # List of available jobs
└── README.md               # Project documentation
```

## Setup Instructions

To run FreelanceHub locally:

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/your-username/freelancehub.git
   cd freelancehub
   ```

2. **Serve the Project**:
   Since this is a static website, you can use any local server. For example, with Python:
   ```bash
   python -m http.server 8000
   ```
   Or with Node.js (using `live-server`):
   ```bash
   npm install -g live-server
   live-server
   ```

3. **Access the Site**:
   Open your browser and navigate to `http://localhost:8000` (or the port provided by your server).

**Note**: No additional dependencies are required, as all libraries (Tailwind CSS, Animate.css, SheetJS, Font Awesome) are included via CDN.

## Usage

- **Homepage**: Explore the platform and navigate to Job Seeker or Job Poster sections.
- **Job Seeker**:
  - Log in (dummy credentials work for demo).
  - View available jobs in `available_jobs.html`.
  - Take a job and track hours in `seeker2.html`.
  - Generate invoices based on logged hours.
- **Job Poster**:
  - Log in and post jobs in `job_posting.html`.
  - View posted jobs with their status (Available/Taken).
- **Contact Us**: Submit inquiries via the contact form (demo alert on submission).

## Hosting

The project is hosted on Netlify at:  
**[https://freelancehub-cse326.netlify.app/](https://freelancehub-cse326.netlify.app/)**

## Contributing

Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature/your-feature`).
3. Make your changes and commit (`git commit -m "Add your feature"`).
4. Push to the branch (`git push origin feature/your-feature`).
5. Open a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

For questions or feedback, reach out via the [Contact Us](https://freelancehub-cse326.netlify.app/contact.html) page or open an issue on GitHub.

---
Built with ❤️ by Chukka Chaitanya
