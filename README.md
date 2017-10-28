# This is a copy of "Meta-Learning Shared Hierarchies" to run in ubuntu env 

Code for [Meta-Learning Shared Hierarchies](https://s3-us-west-2.amazonaws.com/openai-assets/MLSH/mlsh_paper.pdf).

##### Install

You will need a tensorflow env. with python2.7, gym, mpi4py and cloudpickle

```
pip install mpi4py gym cloudpickle
```


##### Running Experiments
```
python main.py --task MovementBandits-v0 --num_subs 2 --macro_duration 1000 --num_rollouts 2000 --warmup_time 20 --train_time 30 --replay true AntAgent
```

```
python main.py --task KeyDoor-v0 --num_subs 2 --macro_duration 1000 --num_rollouts 2000 --warmup_time 20 --train_time 30 --replay true AntAgent
```

```
python main.py --task Allwalk-v0 --num_subs 2 --macro_duration 1000 --num_rollouts 2000 --warmup_time 20 --train_time 30 --replay true AntAgent
```

```
python main.py --task Fourrooms-v0 --num_subs 2 --macro_duration 1000 --num_rollouts 2000 --warmup_time 20 --train_time 30 --replay true AntAgent
```
