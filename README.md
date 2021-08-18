# thesis B00123635 

Corresponding notebooks located at https://github.com/ncorejava/thesB00123635

## Getting Started

### 1. Install Anaconda

Visit the [Anaconda website](https://www.anaconda.com/distribution/) and download the Anaconda installer for your OS (Python 3.7 version).

### 2. Create Environment

Clone this repository using terminal.

```bash
git clone https://github.com/ncorejava/thesB00123635
```

Run the following from within the root of the repository

```bash
conda env create --file environment.yml
```

### 3. Install required Jupyer Lab extensions

In terminal, make sure you have the `thesB00123635` environment activated.

```bash
conda activate thesB00123635
```

Once activated, install the plotly Jupyter Lab extension.

```bash
jupyter labextension install @jupyterlab/plotly-extension
```

### 4. Launch Jupyter Lab

Run the following from within the root of the repository.

```bash
jupyter lab
```

If it asks you to build/rebuild make sure to accept all the prompts. You can keep an eye on the terminal window that launched Jupyter Lab to see when it's ready. You should refresh your browser once it's done.

