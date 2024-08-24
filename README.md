# Astro and SASS Template Project

This is a basic template project that uses [Astro](https://astro.build/) (version 4.14.2) and [SASS](https://sass-lang.com/) to help you quickly set up new web projects. The template also includes styles and management for dark and light themes, making it easy to switch between different visual styles.

![image](https://github.com/user-attachments/assets/21a81e40-acc8-4920-b59b-ea4f54457459)

## Requirements

- [Node.js](https://nodejs.org/) (version 18 or higher)
- [Astro](https://astro.build/) (version 4.0 or higher)

## How to use the template

### Installation

1. Use this template in your project or just clone the repository:
    ```bash
    git clone https://github.com/albertogmdev/astro-template.git
    ```

2. Navigate to the project directory:
    ```bash
    cd astro-template
    ```

3. Install the dependencies:
    ```bash
    npm install
    ```

4. Prepare SCSS or CSS styles

    The template is configured to work with SASS. In case you dont have installed in your machine:

    **Install SASS globally:**
    ```bash
    npm install -g sass
    ```

    **Verify the installation:**
    ```bash
    sass --version
    ```
    
    For more information check [SASS Installation Guide](https://sass-lang.com/install/)

    Once SASS is installed, you can start customizing the styles by editing the `.scss` files located in the `/scss` directory. To compile SCSS styles you have to run  

    ```bash
    sass --watch ./public/scss/styles.scss:./public/css/styles.css
    ```

    If you prefer not to use SASS, you can remove the `/scss` directory.

    If you delete the `/scss` directory, you'll need to manage all styles and variables manually within the `styles.css` file.

### Development

**Development server**

```bash
npm run dev
```

**Build application**

If you want to generate static HTML content

```bash
npm run build
```

This command will create `/dist` folder with your static application. For running a preview of the static content simply run 

```bash
npm run preview
```

## Themes

This template supports themes. The application has a dark theme by default, but you can change the theme of a page, section or component by simply adding `theme--dark` or `theme--light` to the class of a tag. 

You can also customize colors (inside `/scss/_variables.scsss`) and change or add new themes to the template (inside `/scss/_themes_.scsss`).

## Contributing

Contributions are welcome! If you have suggestions for improvements, feel free to open an issue or submit a pull request.

## License

Feel free to customize this template to better suit your specific project needs.
