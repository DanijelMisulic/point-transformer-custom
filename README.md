# Point transformer for classification

Most of the code was taken from this repo: https://github.com/qq456cvb/Point-Transformers

Initial changes:
- removed other models and all other unnecesarry stuff from the repo
- device decision not hardcoded to gpu (code can now run on cpu as well)

Additional changes:
- added tensorboard for training monitoring

To run everything firstly create conda environment: <br/>
conda create --name point_transformer python=3.6 <br/>
conda activate point_transformer  <br/>
pip install -r requirements.txt <br/>
Then cd to the root directory and run: <br/>
python train_cls.py 

If you want to run tensorboard, position yourself to dir: log/cls/Hengshuang/output/point_transformer_Hengshuang and run: <br/>
tensorboard --logdir . <br/>
and open tensorboard on this address: <br/>
http://localhost:6006/

