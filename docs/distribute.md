# Distribution
```bash
# Package
pip3 install setuptools twine

# Distribute
# Instal to local system: $ pip install dist/cicv-0.0.1.tar.gz
python3 setup.py sdist bdist_wheel

# Update load to PyPI
twine upload dist/*
```