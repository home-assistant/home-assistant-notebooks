[![License:](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)

# Jupyter notebooks for Home Assistant

A Jupyter notebook to explore the data in the database of your Home Assistant instance: `GETTING_STARTED.ipynb`. It works with SQLite, the default database, and with MariaDB, MySQL, and PostgreSQL.

- To set up JupyterLab, connect it to your database, and run this notebook, see [Explore your own data](https://contributors.home-assistant.io/data/guides/explore-your-data/).
- The structure of the database is explained in the [data documentation](https://contributors.home-assistant.io/data/).
- The notebook uses [HASS Data Detective](https://github.com/robmarkcole/HASS-data-detective) to find your database, and to sort events by the time of day.
