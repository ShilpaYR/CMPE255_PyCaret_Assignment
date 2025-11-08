# PyCaret Assignment

## How to run the Colabs:

The data associated with each of the colab is present in the respective folders.

### For all the colabs other than Association Rules, use the following:
1. Change the Google Colab runtime to 2025.07, to meet Python 3.11 requirement, because PyCaret and it's dependencies work with 3.11 and below. It's difficult to pin the python version in the colab to 3.11.

2. Choose GPU runtime to make the colabs run faster.

3. Run each of the cells individually, as there is manual intervention needed (like accepting to Restart the kernel after downgrading and installing the package versions, loading the data files through file picker).

### For Association Rules colab:
1. Since association rules package is only available in Pycaret 2.3.5, it needs Python 3.8 or lower, which was very difficult to achieve in colab. So, use local runtime to run this colab.
2. Setup the local runtime by using `conda`, pinning the Python version to 3.8 and other package versions and mentioned in the colab.
3. Run jupyter notebook, and use the link in the Colab local runtime to connect to local runtime.
4. Run each of the cells individually.
