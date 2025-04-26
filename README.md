# runware-models
Repo to host my Seaart.ai models.
Populate README with model list
# Runware Models

This repository hosts custom LoRA models (and others, in future) for use with Runware.ai.

## Models Included

| Model Name                 | Filename                                  | SHA-256 Identifier                                                         | Description                                  |
| -------------------------- | ----------------------------------------- | -------------------------------------------------------------------------- | -------------------------------------------- |
| FLUX Erotic Exotic v1      | `Flux_Erotic_Exotic_v1.safetensors`      | `sha256:5FDDFEEC673BB72E5D079611D6C8865F014B17C3838D8A12D5D385AF9B61BD1D` | Seaart-trained exotic stylization LoRA       |
| FLUX Erotic v1             | `FLUX_Erotic_v1.safetensors`             | `sha256:B6FB74E06ECF2C10ACD93960096A5E7BE311F7A4AEA7D5BE280B652E689A6F86` | Early erotic LoRA                            |
| FLUX Erotic v2             | `FLUX_Erotic_v2.safetensors`             | `sha256:D5340BE42C52F0375853F64F309907C2F88C65CE9F8661881EDC60F33E40F367` | Refined erotic LoRA v2                       |
| FLUX Exotic v1             | `FLUX_Exotic_v1.safetensors`             | `sha256:8543CEAD2053AC9461DEFBCD07F82D66E295228CEB0F72F61EDFC930F1AE149A` | Original “Exotic” concept LoRA               |
| FLUX Exotic v2             | `FLUX_Exotic_v2.safetensors`             | `sha256:E74EF0C083CB73D00E94E60C437209A8D74CE41CEB7B9C5A25AA4DFA005D441F` | Updated Exotic v2 LoRA                       |
| FLUX Exotic Jungle v1      | `FLUX_Exotic_Jungle_v1.safetensors`      | `sha256:3C361446494BC3940F007BE4771C30E82E1F650335D8DC22180961F34905F132` | Jungle-themed Exotic v1 LoRA                 |
| FLUX Exotic Jungle v1.2    | `FLUX_Exotic_Jungle_v1.2.safetensors`    | `sha256:DF92069119732D1AACF1DD2A3651E931274EBCADFC5072129B50AC9FB6287526` | Tweaked Jungle v1.2 LoRA                     |
| FLUX Vibrant v1            | `FLUX_Vibrant_v1.safetensors`            | `sha256:A5E862F53F8AC37A56AE8FC966B48119726BC7990EFF4DD3012638D891204FD0` | Vibrant color-boosting LoRA                  |
| FLUX Vibrant v1.2          | `FLUX_vibrant_v1.2.safetensors`          | `sha256:AB9ACC279DF7A3F5BF858A54BEF1C03C4E376C9D40BABF4ED68603051EDE7AA4` | Minor revision of Vibrant v1.2 LoRA          |

## Setup

1. **Install Git LFS** (for files >100 MB):  
   ```bash
   git lfs install
