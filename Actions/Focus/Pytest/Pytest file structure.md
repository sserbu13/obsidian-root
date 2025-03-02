#programming #python #pytest

## Project Directory Structure

```
Pytest-allure-demo/

    ├── tests/                  # Test case files

    │   ├── test_login.py       # Example test case file

    │   ├── test_order.py       # Example test case file

    │   └── ...

    ├── data/                   # Test data files (e.g., JSON, CSV, etc.)

    │   ├── dev_test_data.json      # Development environment test data file

    │   ├── prod_test_data.json      # Production environment test data file

    │   ├── ...

    ├── config/

    │   ├── dev_config.json  # Development environment configuration file

    │   ├── prod_config.json  # Production environment configuration file

    │   ├── ...

    ├── conftest.py             # Pytest global configuration file

    ├── pytest.ini              # Pytest configuration file

    ├── requirements.txt        # Project dependencies file

    └── allure-report/          # Allure report storage
    