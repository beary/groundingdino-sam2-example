# GroundingDINO SAM2

### Install

Clone repository

```bash
git clone --recurse-submodules https://github.com/beary/groundingdino-sam2-example.git
cd groundingdino-sam2-example
```

Create virtual environment

```bash
python -m venv .venv
# *nix
source .venv/bin/activate
# windows
.\.venv\Scripts\activate.ps1
```

Install pytorch

```bash
pip install -U torch torchvision
```

Install other dependencies

```bash
pip install -r requirements.txt
```

Install SAM2

```bash
pip install -e 3rdparty/sam2
```

### Download SAM2 checkpoint

| URL                     | Location                            |
| ----------------------- | ----------------------------------- |
| [sam2.1_hiera_large.pt] | `checkpoints/sam2.1_hiera_large.pt` |

### Start

```bash
python -m jupyter lab
```

Visit: http://localhost:8888/lab/workspaces/auto-l/tree/notebook/groundingdino-sam2.ipynb in browser.

[sam2.1_hiera_large.pt]: https://dl.fbaipublicfiles.com/segment_anything_2/092824/sam2.1_hiera_large.pt