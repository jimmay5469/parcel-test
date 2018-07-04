# Parcel Test

## Setup

- `mkdir my-new-project`
- `cd my-new-project`
- `git init`
- `echo node_modules/ >> .gitignore`
- `echo dist/ >> .gitignore`
- `echo .cache/ >> .gitignore`
- `npm init -y`
- Add `"start": "parcel index.html"` to `"scripts"` in `package.json`
- `npm i --save-dev parcel`
- `npm i --save-dev node-sass`
- `touch index.html`
- `git commit -m "Initial commit"`


## Running

- `npm start`
- Visit [localhost:1234](http://localhost:1234)


## Options

### Adding Fontawesome

- `npm i @fortawesome/fontawesome-free`
- Include Fontawesome:
    ```
    $fa-font-path: "./../node_modules/@fortawesome/fontawesome-free/webfonts";
    @import "./../node_modules/@fortawesome/fontawesome-free/scss/fontawesome";
    @import "./../node_modules/@fortawesome/fontawesome-free/scss/fa-brands";
    @import "./../node_modules/@fortawesome/fontawesome-free/scss/fa-regular";
    @import "./../node_modules/@fortawesome/fontawesome-free/scss/fa-solid";
    ```
