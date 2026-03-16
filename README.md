# DeepLearning_Lab_Homework

> BJTU DeepLearning homework.
> By SOMEONE in BJTU, 2023.

---

## Run project

### Install pip packages
```bash
pip install -r requirements.txt
```

### Test cuda usability
> In Pytorch_test.ipynb
```python
import torch
torch.__version__
torch.cuda.is_available()
```

> **Note**: If `torch.__version__` is including `cuda`, but `torch.cuda.is_available()` is `false`.
> You can try again later. It usually works.

---
All codes were collected into .ipynb files.