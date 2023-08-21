### Updates
[2023-08-22 1:38AM]
Can run the following codes:
* `[batch] Speaker_identification_updated_batch.ipynb`
* `[conformer] Speaker_identification_updated_conformer.ipynb`
* `[model] Speaker_identification_updated_model.ipynb`

p.s. the `[model]` code requires importing `torchaudio`.<br>
If there is `ModuleNotFoundError` or `ImportError` for `torchaudio` (not being installed), may need to install by:
* `conda install torchaudio -c pytorch -c nvidia` OR
* `pip3 install torchaudio --index-url https://download.pytorch.org/whl/cu118`

### Estimated time for each device
| Code | NVIDIA GeForce RTX 4090 | Google Colab <br>(Tesla T4) | M1 (MPS) |
| :- | :- | :- | :- |
| `[batch] Speaker_identification_updated_batch.ipynb` | ~1 hour<br>(20 + 20 + 30 mins) | ~5 hours<br>(60 + 90 + 150 mins) | ~3 hours<br>(40 + 60 + 120 mins) |
| `[conformer] Speaker_identification_updated_conformer.ipynb` | ~1 hours | ~2 hours | ~1.5 hours |
| `[model] Speaker_identification_updated_model.ipynb` | ~1 hour | ~3 hours | ~2 hours |

### Dataset
Dataset can be downloaded via my google drive, which is embedded in the code.<br>
To download the dataset, you need the link from `Dataset.py`.  Remember to download it alongside with other codes~

## Instructions
1. Download the whole directory and save it into a folder.
2. Choose kernel (e.g. `handhand`) and simply press `run all`.  The codes should be able to handle most errors, including ImportError
3. Please tell me in case of any error~
<br>
Thanksss!