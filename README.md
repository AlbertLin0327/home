<!-- PROJECT LOGO -->

# Personal Website

[![Followers](https://img.shields.io/github/followers/AlbertLin0327?style=social)](https://github.com/AlbertLin0327)
[![Stars](https://img.shields.io/github/stars/AlbertLin0327?style=social)](https://github.com/AlbertLin0327)
![Issue](https://img.shields.io/github/issues/AlbertLin0327/Personal-Website)
![Commit](https://img.shields.io/github/last-commit/AlbertLin0327/Personal-Website)

#### This repository is forked from [hashirshoaeb](https://github.com/hashirshoaeb/home) and modification are made to fit personal need.

## Technology Stack 🛠

Dependencies defined in package.json:

[Reactjs](https://reactjs.org/)
| [Bootstrap](https://getbootstrap.com/)
| [Typist](https://github.com/jstejada/react-typist)
| [GitHub API](https://developer.github.com/v3/repos/)
| [Instagram API](https://www.instagram.com/developer/embedding/)

## Structure

-   Navigation bar (optional)
-   Body
    -   Name | Profession
    -   Contact / Follow / Find me / Facebook / LinkedIn / GitHub / Instagram / Email / CodePen
    -   Resume | About me
-   About Me
    -   Display picture (optional)
    -   About myself, my Interests, Goals and Hobbies
    -   Things I'm good at (Skills)
    -   Resume button
-   Recent Projects (using GitHub API) (optional)
-   Leadership (optional)
    -   Paragraph
    -   Carousel images
-   Skills (optional)
    -   Technical Skills
    -   Soft Skills
-   Footer
    -   Footer Note (optional)
    -   Copyrights - open source
    -   Acknowledgements(

## Prerequisites

You should have [Node.js](https://nodejs.org/en/) and [Git](https://git-scm.com/) installed on your PC. You should also own a GitHub account.

## Setup And Deployment

1. To Get Started, Fork this repository to your GitHub account:
2. Clone the forked repo from your account using:

    ```bash
      git clone https://github.com/<your-username>/home.git
    ```

3. Open in editor and edit [src/editable-stuff/config.js](./src/editable-stuff/config.js) file.

4. Add your resume as <resume.pdf> in place of [src/editable-stuff/resume.pdf](./src/editable-stuff/)

5. Edit [title](./public/index.html#L34) and meta [description](./public/index.html#L13) in [public/index.html](./public/index.html).
6. Change URL in [package.json](./package.json) file:

    ```json
     "homepage": "https://<your-username>.github.io/home"
    ```

    Or for deployment at custom domain, refer [create-react-app.dev](https://create-react-app.dev/docs/deployment/#step-1-add-homepage-to-packagejson)

7. After editing run the following bash commands:

    ```bash
    npm install
    npm start
    ```

8. To deploy website, run:

    ```bash
     npm run build
     cd build
     npm run deploy
    ```

    Or for deployment at \<username>.github.io, refer [custom-deployment.md](./custom-deployment.md) and [pages.js](./pages.js)

9. Congrats your site is up and running. To see it live, visit:

    ```https
      https://<your-username>.github.io/home
    ```

10. To change the thumbnail image:

    - Navigate to the "public" folder.
    - There you will see "social-image.png".
    - Delete it.
    - Take a screenshot of your version and rename it "social-image.png" and place it there.

Next time if you make changes, repeat from step 8.

Facing issues? Feel free to contact at hashirshoaeb@gmail.com.

## Contributing 🙌

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
