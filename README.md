# Netlify Static Site

This project is a static website hosted on Netlify. It includes HTML, CSS, and JavaScript files to create a simple web application.

## Project Structure

```
netlify-static-site
├── public
│   └── index.html        # Main HTML document
├── src
│   ├── js
│   │   └── main.js       # JavaScript code for interactivity
│   └── css
│       └── styles.css    # CSS styles for the website
├── .gitignore             # Specifies files to ignore in Git
├── netlify.toml          # Netlify configuration file
├── package.json          # npm configuration file
└── README.md             # Project documentation
```

## Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone <repository-url>
   cd netlify-static-site
   ```

2. **Install Dependencies**
   If you have npm installed, run:
   ```bash
   npm install
   ```

3. **Run the Project Locally**
   You can use a local server to view the project. For example, you can use `live-server` or any other local server tool.

4. **Deploy to Netlify**
   - Push your code to GitHub.
   - Go to Netlify and link your GitHub repository.
   - Set the publish directory to `public`.

## Usage

Open `public/index.html` in your browser to view the website. The JavaScript file `src/js/main.js` contains the functionality, while `src/css/styles.css` styles the page.

## Contributing

Feel free to submit issues or pull requests for improvements or bug fixes.