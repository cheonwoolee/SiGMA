# UNIFYING MULTI-SCALE DESIGN IN TIME-SERIES FORECASTING

## Official implementation of SiGMA.

## TL;DR

- We propose **SiGMA**, a simple yet principled multi-scale time series forecasting framework that overcomes the limitations of existing multi-scale forecasting approaches.
- This project is developed based on experiments using [TSLib](https://github.com/thuml/Time-Series-Library), which is distributed under the MIT License.

## Environment Setup

```bash
conda create -n SiGMA python=3.8.0
conda activate SiGMA
pip install -r requirements.txt
```

## How to Run?

```
bash script/SiGMA_[dataset_name].sh
```

**Supported `dataset_name` values:**
`ECL`, `ETTh1`, `ETTh2`, `ETTm1`, `ETTm2`, `Exchange`, `M4`, `Traffic`, `Weather`

You can download these datasets from [TSLib](https://github.com/thuml/Time-Series-Library).

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
