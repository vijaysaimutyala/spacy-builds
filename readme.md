## Spacy 2.0.11 build for Windows

The wheel files were generated to be used on Azure App Service where the usual pip install fails due to Visual Studio compiler error. The wheels are generated using 

1. pip==18.0
2. wheel == 0.31.1

### pip wheel --wheel-dir=/tmp/wheelhouse spacy==2.0.11

with the above command on Windows 10 64 bit system. I've deployed these wheels on Azure app service and these are running fine without any issues. 

