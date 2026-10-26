# Component notices and reuse

This release contains author-generated research records and software alongside identified third-party source snapshots. Existing licenses apply to their respective components. No new umbrella license is assigned to the mixed package, and public visibility is not an unrestricted reuse grant.

The third-party implementation snapshot resides in `Supplementary_Checkpoint_Precision_Normalization.zip` under `source_dependencies/site-packages/`. Preserve these accompanying notices when redistributing that archive:

| Component | Included source | Applicable notice |
| --- | --- | --- |
| timm | `timm/` | Apache 2.0 license already supplied under `source_dependencies/licenses/timm-1.0.14.dist-info/licenses/LICENSE`, together with file-specific notices. |
| PyTorch | Five retained `torch/` implementation files | Existing PyTorch LICENSE and NOTICE under `source_dependencies/licenses/torch-2.7.1+cu126.dist-info/`. |
| Pillow | `PIL/Image.py` and `PIL/PngImagePlugin.py` | Existing Pillow license under `source_dependencies/licenses/pillow-12.3.0.dist-info/licenses/LICENSE`. |
| Apple FastViT | `timm/models/fastvit.py` | Companion `licenses/Apple-ML-FastViT-LICENSE.txt` and `licenses/Apple-ML-FastViT-ACKNOWLEDGEMENTS.txt`. |
| OpenAI CLIP | Adaptation in `timm/layers/attention_pool2d.py` | Companion `licenses/OpenAI-CLIP-LICENSE.txt`, from the exact upstream commit cited in that source. |
| ECA-Net | `timm/layers/eca.py` | Original MIT notice already retained in the file's docstring. |

The companion `THIRD_PARTY_NOTICES.zip` release asset contains this notice and the additional license files. Download it with the checkpoint diagnostic archive and distribute them together. `licenses/sources.json` records the notice sources and checksums. The original scientific archive remains byte-identical.

See DATA_ACCESS.md for dataset attribution and reuse boundaries. The repository does not redistribute trained weights. Historical model URLs identify provenance and are not included assets. Additional permissions for author-owned material can be requested from the repository authors without assuming that they control third-party rights.
