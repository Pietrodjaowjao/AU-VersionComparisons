# Among Us Version Comparisons

This repository contains HTML files that compare the *Among Us* game code across different versions, generated using [diffoscope](https://diffoscope.org/). The aim is to document the differences between versions for research, analysis, or modding purposes.

## Contents

- **HTML Comparison Files**: Each file is a comparison between two specific versions of *Among Us*. The naming convention is:  
  `diff_vX.X.X_to_vY.Y.Y.html`  
  Example: `diff_v2021.6.30_to_v2022.7.12.html`

## How Comparisons are Generated

The comparisons are created using [diffoscope](https://diffoscope.org/), a tool that provides detailed diffs down to the byte level across multiple file types, including game binaries and assets.

### Steps to Generate a Comparison:

1. Extract or collect the necessary assets or binaries from two *Among Us* versions.
2. Run `diffoscope` to compare them and generate an HTML report:
   ```bash
   diffoscope --html=diff_v2021.6.30_to_v2022.7.12.html path_to_v2021 path_to_v2022
   ```

## Contribution

Contributions are currently not accepted for this repository. It serves mostly as a personal archive of version comparisons.