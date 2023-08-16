# discrete Walk-Jump Sampling (dWJS)

This is the official open source repository for discrete Walk-Jump sampling.

## Setup
Assuming you have [miniconda](https://docs.conda.io/en/latest/miniconda.html) installed, clone the repository, navigate inside, and run:
```bash
./scripts/install.sh
```

### Training
The entrypoint `train` is the main driver for training and accepts parameters using Hydra syntax.
The available parameters for configuration can be found by running `train` --help or by looking in the `src/walkjump/hydra_config` directory

### Sampling
The entrypoint `sample` is the main driver for training and accepts parameters using Hydra syntax.
The available parameters for configuration can be found by running `sample` --help or by looking in the `src/walkjump/hydra_config` directory

## Contributing

We welcome contributions. If you would like to submit pull requests, please make sure you base your pull requests off the latest version of the `main` branch.

## License
Licensed under the Apache License, Version 2.0 (the "License"); you may not use this file except in compliance with the License. You may obtain a copy of the License at https://www.apache.org/licenses/LICENSE-2.0.

Unless required by applicable law or agreed to in writing, software distributed under the License is distributed on an "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied. See the License for the specific language governing permissions and limitations under the License.

