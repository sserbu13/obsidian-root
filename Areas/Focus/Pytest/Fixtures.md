
```cardlink
url: https://docs.pytest.org/en/stable/explanation/fixtures.html
title: "About fixtures - pytest documentation"
host: docs.pytest.org
```

#fixtures

Fixtures are useful for building pre-requisites before tests and doing clean-up after tests are ran.

These are saved in conftest.py

We call the fixture by calling the fixture function inside the test function argument 
```js
def test_function(fixture_name):
```

OR 
 
We can set the fixture argument as follows for tests to always use the fixture : 
```js
@pytest.fixture(autouse=True)
```