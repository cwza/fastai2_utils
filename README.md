# fastai2_utils

> My personal utils for fastai2 and pytorch.

## Install
`pip3 install git+https://github.com/cwza/fastai2_utils.git`

## How to develop
### Editable install
``` sh
git clone https://github.com/cwza/fastai2_utils.git
cd fastai2_utils
make install
```
### Develop pipeline
1. Modify notebooks in nbs folder (Write unit tests in the same notebook and create new notebook to write integration test)
2. make build-lib to update python files
3. make test to run unit test
4. make test-slow to run integration test
5. make build-all to run build-lib, build-docs, clean-nbs
6. git add commit and push
