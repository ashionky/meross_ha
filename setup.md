# refoss_ha
- Meross to support for  Home Assistant
- 安装setuptools和wheel
  - python3 -m pip install  --upgrade setuptools wheel
- 打包
  - python3 setup.py bdist_wheel
  - python3 -m twine upload  dist/meross_ha-1.0.1-py3-none-any.whl

