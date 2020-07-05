| S.No | Activation | Initializer  | Optimiser | Batch_norm | Dropout          | Learning Schedule | Train Error (%) | Validation Error (%) | Test Error (%) |
|------|------------|--------------|-----------|------------|------------------|-------------------|-----------------|----------------------|----------------|
| 1    | ELU        | He-Normal    | Nadam     | Yes        | MacDropout p=0.3 | 1cycle            | 0.653           | 0.511                | 0.545          |
| 2    | ELU        | He-Normal    | Nadam     | Yes        | MacDropout p=0.3 | Constant          | 0.687           | 0.514                | 0.539          |
| 3    | ELU        | He-Normal    | Nadam     | No         | MacDropout p=0.3 | Constant          | 0.704           | 0.502                | 0.537          |
| 4    | ELU        | He-Normal    | Nadam     | Yes        | p=0              | Constant          | 0.709           | 0.520                | 0.525          |
| 5    | SELU       | Lecun_Normal | Nadam     | No         | MacDropout p=0.3 | Constant          | 0.741           | 0.507                | 0.522          |
| 6    | ELU        | He-Normal    | Nadam     | Yes        | p=0.3            | Constant          | 0.687           | 0.514                | 0.515          |
| 7    | ELU        | He-Normal    | Nadam     | Yes        | p=0.3            | 1cycle            | 0.653           | 0.511                | 0.513          |
| 8    | ELU        | He-Normal    | Nadam     | Yes        | MacDropout p=0.3 | 1cycle            | 0.557           | 0.474                | 0.511          |
| 9    | SELU       | Lecun_Normal | Nadam     | No         | p=0.3            | Constant          | 0.741           | 0.507                | 0.502          |
| 10   | ELU        | He-Normal    | Nadam     | No         | p=0.3            | Constant          | 0.704           | 0.502                | 0.500          |
| 11   | SELU       | Lecun_Normal | Nadam     | No         | p=0              | Constant          | 0.613           | 0.500                | 0.498          |
| 12   | SELU       | Lecun_Normal | Nadam     | No         | MacDropout p=0.3 | 1cycle            | 0.529           | 0.466                | 0.497          |
| 13   | ELU        | He-Normal    | Nadam     | No         | p=0              | Constant          | 0.603           | 0.484                | 0.493          |
| 14   | ELU        | He-Normal    | Nadam     | Yes        | p=0.3            | 1cycle            | 0.557           | 0.474                | 0.480          |
| 15   | SELU       | Lecun_Normal | Nadam     | No         | p=0.3            | 1cycle            | 0.529           | 0.466                | 0.478          |
| 16   | ELU        | He-Normal    | Nadam     | Yes        | MacDropout p=0.3 | 1cycle            | 0.469           | 0.419                | 0.461          |
| 17   | ELU        | He-Normal    | Nadam     | Yes        | p=0.3            | 1cycle            | 0.653           | 0.511                | 0.545          |