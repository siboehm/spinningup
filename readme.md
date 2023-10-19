Setup (M1 mbp):
```bash
mamba create -n spinningUp python=3.8
conda activate spinningUp
pip install -e .
pip install pyglet==1.5.15 # ignore errors
python spinup/examples/pytorch/pg_math/1_simple_pg.py --render
```
