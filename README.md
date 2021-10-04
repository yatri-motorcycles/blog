# Yatri Blog

## Server Setup (docker)

- In the root project folder, copy the `example.env` and save as `.env.dev` for development and `.env.prod` for production. Update the variables.
  In the project directory, you can run:

- Run `docker-compose up` from the root folder to the application. To run the application in background, use `docker-compose up -d`. The logs can be seen through `docker-compose logs`.

- For production mode. Run `docker-compose -f docker-compose.prod.yml up`

Runs the app in the development mode.\
Open [http://localhost:3004](http://localhost:3004) to view it in the browser.

## Site setup

- Navigate to `http://localhost:3004/ghost` to access the admin panel. After you've finished the setup process. You'll be able to see the ghost dashboard.

## Custom theme

- Navigate to `http://localhost:3004/ghost`. On the bottom left you'll see a ⚙️ icon. It'll navigate you to the settings page. Choose theme then under installed theme, select `yatri-casper`. It'll activate your custom theme.

- Navigate to `ghost/themes/yatri-casper` from your root project directory and make changes to theme files. Reload your blog site and you'll be able to see your changes.

- To create a `.zip` theme file.
  ```bash
  cd ghost/themes/yatri-casper
  # install dependencies
  yarn
  # create .zip file
  yarn zip
  ```

🏍 Happy Coding :)
