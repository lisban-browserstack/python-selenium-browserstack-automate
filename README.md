## To run the file 
# create virtual environment
python3 -m venv env
source env/bin/activate
# install the required packages
pip3 install -r requirements.txt

# Set userName and accessKey properties in browserstack.yml to authenticate your tests on BrowserStack.

## Execute build on BrowserStack
browserstack-sdk python ./tests/test.py

## Session Id : c7737365af1e091ef3e894e6547c4f39c5e0fee7
## Public Id : https://automate.browserstack.com/builds/3c4686231335d651049e81c5d7123d3fbb37e6ea/sessions/c7737365af1e091ef3e894e6547c4f39c5e0fee7?auth_token=9640aae80a76e243bcd3ad00cd00092c0e71fb346cb61e85dbf4b49c9e6ecf3f