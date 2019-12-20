# KB-smishing

## pickle data load
sample_datas = []
sample_label_datas = []

with open('train_data.pickle', 'rb') as f:
  sample_datas = pickle.load(f)
with open('train_label_data.pickle', 'rb') as f:
  sample_label_datas = pickle.load(f)
