# nice

| File | loss_labels | loss_masks |
| --- | ----------- | ----------- |
| modeling_maskformer.py | fixed (0,1,2) labels | angular loss radians |
| modeling_maskformer_with_labels_loss.py | labels via hungarian matrching | angular loss radians |
| modeling_maskformer_mse_loss.py | fixed (0,1,2) labels | mse loss |
| modeling_maskformer_mse_with_labels_loss.py | labels via hungarian matrching | mse loss |
| modeling_maskformer_with_hungarian.py | hungarian matching for fixed (0,1,2) labels | mse loss |
