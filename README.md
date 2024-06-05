# TB-GenomeExplorer

TB-GenomeExplorer is a repository containing scripts and documentation for performing whole genome sequencing (WGS) analysis of Mycobacterium tuberculosis using Azure pipelines. The example analysis focuses on identifying and analyzing genomic features specific to the TB-causing bacterium.

## Contents
- `data/`: Directory for storing raw and processed data.
- `scripts/`: Python and shell scripts for data processing and analysis.
- `notebooks/`: Jupyter notebooks for interactive data exploration and analysis.
- `results/`: Directory for storing results.
- `azure-pipelines/`: Azure pipeline configuration files.

## Getting Started

### Prerequisites
- Python 3.8+
- Azure CLI
- Docker

### Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/alushaks/TB-GenomeExplorer.git
    cd TB-GenomeExplorer
    ```

2. Install the required Python packages:
    ```sh
    pip install -r requirements.txt
    ```

## Running the Analysis

To run the analysis, follow the instructions in the `scripts/` directory and use the Jupyter notebooks in `notebooks/` for detailed analysis steps.

## Azure Pipelines

The repository includes configuration files for running the analysis on Azure Pipelines. See the `azure-pipelines/` directory for details.
