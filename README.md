# Frontend for FastAPI RBAC

This project is the frontend for the [FastAPI RBAC](https://github.com/satriyobud/rbac_fastapi) backend. It is a static website built with CoreUI and is designed to work with the aforementioned backend project to provide a complete Role-Based Access Control system.

## Running the project

To run the project, you can use a simple Python web server.

1.  Navigate to the `fe_rbac_fastapi` directory:
    ```bash
    cd fe_rbac_fastapi
    ```
2.  Start the web server:
    ```bash
    python3 -m http.server
    ```
3.  Open your browser and go to `http://localhost:8000`.

## Folder Structure

*   `assets/`: Contains static assets like images and icons.
*   `css/`: Contains the CSS files for the project.
*   `js/`: Contains the JavaScript files for the project.
*   `vendors/`: Contains the third-party libraries used in the project, such as CoreUI.
*   `*.html`: The HTML files for the different pages of the website.