# Sharing Pytests

https://2023.pycascades.com/program/talks/sharing-is-caring-sharing-pytest-fixtures/

https://pythontest.com/pycascades-2023/

Fixture crash course

A fixture is a function

```
import pytest
@pytest.fixture()
def db()
  pass
```

https://github.com/tartley/colorama

can share pytest fixtures with a conftest.py
Then test files can just be a test file and can import the fixtures

to share pytest fixtures with different projects will need to package the pytest into packages.

goddam gotta build a project.toml file (Similar to yaml)

https://pypi.org/classifiers/

Package testing/building:
- https://pypi.org/project/tox/
- tox is neat that it will build and test your code in all python versions (up to the one that you define)
- similar one is knox: https://github.com/8x8cloud/knox


How to publish packages and test: https://test.pypi.org/
https://www.amazon.com/Python-Testing-pytest-Effective-Scalable/dp/1680508601/ref=pd_lpo_1?pd_rd_w=xoQnH&content-id=amzn1.sym.116f529c-aa4d-4763-b2b6-4d614ec7dc00&pf_rd_p=116f529c-aa4d-4763-b2b6-4d614ec7dc00&pf_rd_r=M2JQB829QCGDX6SH5W6V&pd_rd_wg=aCZr8&pd_rd_r=e73151f8-871f-4590-b0a1-419c1d88dbf9&pd_rd_i=1680508601&psc=1
