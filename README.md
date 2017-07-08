Structure of project
====================

|-- CONTRIBUTORS.md
|-- LICENSE
|-- config
|   `-- db.config.json
|-- database
|-- docs
|-- includes
|   |-- config.php
|   |-- helpers.php
|   `-- library
|       `-- WC.php
|-- public
|   |-- css
|   |   `-- styles.css
|   |-- fonts
|   |-- img
|   |-- index.php
|   |-- js
|   |   `-- scripts.js
|   |-- login.php
|   `-- logout.php
`-- views
    |-- apology.php
    |-- dump.php
    |-- footer.php
    |-- header.php
    |-- login_form.php
    `-- main.php


The following describes the use cases for each directory as listed.
-------------------------------------------------------------------
* configs/: The application-wide configuration directory.
* database/: Database schema.
* docs/: This directory contains documentation, either generated or directly authored.
* includes/: This directory should hold all 3rd party libraries, custom libraries, configs and any other code that acts as a resource in the project.
    * library/: Central location for all custom and third party libraries.
* public/: This directory contains all public files for the application.
    * css/: All css files.
    * fonts/: All fonts files.
    * img/: All images files.
    * js/: All javascript files.
* views/: Reusable components that make up your layout.(templates)
