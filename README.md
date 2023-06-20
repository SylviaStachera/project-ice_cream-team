# project-ice_cream-team

## Dependencies

You need to have the LTS version of Node.js installed on your computer.

## Getting Started

Install all the dependencies for the project by running the following command once:

```shell
npm ci
```

### Development

Start the development server by running the following command:

```shell
npm run dev
```

Open [http://localhost:1234](http://localhost:1234) in your browser.

### Deployment
The code will automatically be built and deployed to GitHub Pages in the gh-pages branch whenever changes are made to the main branch. For example, after a direct push or when a pull request is merged. To enable this functionality, you need to modify the homepage field and the build script in the package.json file, replacing username and repository-name with your own.

```json
"homepage": "https://username.github.io/repository-name",
"scripts": {
  "build": "parcel build src/*.html --public-url /repository-name/"
},
```

After some time, you will be able to see your website live at the address specified in the updated homepage property, for example,
[https://goitacademy.github.io/parcel-project-template](https://goitacademy.github.io/parcel-project-template).

## Files and Folders

All style partials should be placed in the src/sass folder and imported into src/sass/main.scss.
Add images to the src/images folder. Make sure to optimize the images before adding them. The build process simply copies the used images to avoid the system optimization step, as it can be time-consuming on slower computers.

Feel free to modify this translation according to your needs.
