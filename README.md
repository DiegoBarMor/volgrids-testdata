# VolGrids Test Data
This repository contains raw inputs to generate test data for the [volgrids](https://github.com/DiegoBarMor/volgrids) package.

# Usage
1) Go into the `volgrids` repo.
```bash
# git clone https://github.com/DiegoBarMor/volgrids
cd volgrids
```

2) Clone this repo.
```bash
git clone --depth 1 https://github.com/DiegoBarMor/volgrids-testdata testdata
rm -rf testdata/.git* # (optional)
```

3) The tests can now be run. The first time `tests/run.sh` is executed, several test data files will be automatically generated.
```bash
# pip install -r environment/requirements.txt
tests/run.sh
tests/cleanup.sh # (optional)
```
