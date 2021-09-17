# Point transformer for classification

Most of the code was taken from this repo: https://github.com/qq456cvb/Point-Transformers

Initial changes:
- removed other models and all other unnecesarry stuff from the repo
- device decision not hardcoded to gpu (code can now run on cpu as well)

Additional changes:
- added tensorboard for training monitoring

To run everything firstly create conda environment:
conda create --name point_transformer python=3.6 <br/>
pip install requirements.txt

