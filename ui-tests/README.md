# Visual regression tests using Galata

This directory contains visual regression tests for ipympl, using Galata.

In order to run them, you need to install dependencies:

```bash
const install -c conda-forge yarn jupyterlab=3.0.7

yarn install
```

Then start JupyterLab in one terminal (you need to check that it properly starts on port 8888):
```bash
yarn run start-jlab
```

Finally, run the galata tests:
```bash
yarn run test
```

If bqplot visuals change, you can re-generate reference images by running:
```bash
yarn run update-references
```
