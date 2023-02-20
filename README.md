# nice

| File | loss_labels | loss_masks | null class |
| --- | ----------- | ----------- | ----------- |
| modeling_maskformer.py | fixed (0,1,2) labels | angular loss radians | yes |
| modeling_maskformer_with_labels_loss.py | labels via hungarian matrching | angular loss radians | yes |
| modeling_maskformer_mse_loss.py | fixed (0,1,2) labels | mse loss | yes |
| modeling_maskformer_mse_with_labels_loss.py | labels via hungarian matrching | mse loss | yes |
| modeling_maskformer_with_hungarian.py | hungarian matching for fixed (0,1,2) labels | mse loss | yes |
| modeling_maskformer_with_hungarian_angular_loss.py | hungarian matching for fixed (0,1,2) labels | angular loss | yes |
| modeling_maskformer_mse_loss_nobg.py | fixed (0,1,2) | mse loss | no |
| modeling_maskformer_with_hungarian_nobg.py | hungarian matching for fixed (0,1,2) labels | mse loss | no |
