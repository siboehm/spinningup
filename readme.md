Setup:
```bash
mamba create -n spinningUp python=3.7 gym-classic_control gym-atari gym-box2d cloudpickle==1.2.1  matplotlib ipython joblib  mpi4py numpy pandas pytest psutil scipy seaborn==0.8.1  tqdm pytorch pytorch-cuda=12.1 -c pytorch -c nvidia
```

Gym doesn't support py>3.7.
