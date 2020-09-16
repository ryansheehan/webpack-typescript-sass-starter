# webpack-typescript-sass-starter

## Features

* Webpack production and development
* Webpack hot module reloading
* Sass w/ autoprefixer
* typescript
* github actions for autobuild

## Usage

1. Clone the repo

    ```bash
    git clone --depth=1 --branch=master https://github.com/ryansheehan/webpack-typescript-sass-starter.git
    ```

2. Delete and recreate the .git directory

    ```bash
    rm -rf .git
    git init
    git add .
    git commit -m "initial commit"
    ```

3. Update package.json and README.md

    * change name, version, description in `package.json`
    * Update the `README.md`

4. [optional] Update build.yml

    * `.github/workflows/build.yml` just builds on push to master
    * production builds put assets in `/dist`, may want to publish assets 
      to github pages or some other location.