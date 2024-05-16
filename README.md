# BarrenPlateaus_DLA_Data Repository

This repository contains pre-generated data for the figure related to barren plateaus in variational quantum circuits (VQC), specifically focusing on the exponential and polynomial decay of gradients with respect to system size.

## Background

The original code used for the figure is available [here](https://github.com/therooler/lie_classification). Generating the data using their provided Python scripts can be time-consuming, taking up to 2 days of continuous computation. To alleviate this burden, I have generated the data and uploaded it to this repository, along with minor fixes to ensure smooth execution.

## Repository Contents

    data/: Contains the pre-generated data files.
    scripts/: Contains the original Python scripts with a minor fix.
    examples/: Example usage of the data and scripts.
    README.md: This document.
## Usage
# Accessing the Data

The pre-generated data is located in the data/ directory. You can load and use this data directly in your analysis without the need to run the time-consuming scripts.

## Running the Scripts

If you need to run the scripts for any reason, they are available in the scripts/ directory. Note the minor fix added:

# Fixed missing import
```import scienceplots```

To run the scripts:

    1. Ensure you have all dependencies installed:
    ```pip install -r requirements.txt```

    2. Execute the main script:
    '``python barren_plateaus.py```


## Acknowledgments

Thanks to the original authors for their significant work on the classification of dynamical Lie algebras. This repository aims to build upon their foundation and provide easier access to their results.

## Citing the Original Work

Please cite the original authors if you use this data or any part of their code in your work:

```bibtex
@misc{wiersema2023classification,
      title={Classification of dynamical Lie algebras for translation-invariant 2-local spin systems in one dimension}, 
      author={Roeland Wiersema and Efekan Kökcü and Alexander F. Kemper and Bojko N. Bakalov},
      year={2023},
      eprint={2309.05690},
      archivePrefix={arXiv},
      primaryClass={quant-ph}
}
