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
git clone https://github.com/DiegoBarMor/volgrids-testdata testdata
rm -rf testdata/.git*
```

3) Generate the testdata for volgrids.
```bash
# pip install -r environment/requirements.txt
tests/_gen_input.sh
```

4) The tests can now be executed.
```bash
tests/run.sh
```
