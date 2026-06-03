# Thesis_Backdoor_Federated_Learning_Cuckoo

Experiment -2: python federated.py --data=fmnist --local_ep=2 --bs=256 --num_agents=10 --rounds=200

Experiment -1: python federated.py --data=fmnist --local_ep=2 --bs=256 --num_agents=10 --rounds=200 --num_corrupt=1  --poison_frac=0.5

Experiment 0: python federated.py --data=fmnist --local_ep=2 --bs=256 --num_agents=10 --rounds=200 --num_corrupt=1  --poison_frac=0.5 --robustLR_threshold=4
