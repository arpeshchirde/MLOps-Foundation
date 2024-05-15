# MLOps-Foundation
[build-system]
requires = ['setuptools>=42.0', "wheel"]
build-backend = "setuptools.build_meta"

[tool.pytest.ini_options]
testpaths = [
    "tests"
    ]

[tool.mypy]
mypy_path = "src"
ignore_missing_imports = true