# An Attention-based Sequence-to-Sequence Model for Slot Filling

A sequence-to-sequence model with attention and beam search for slot filling. Implemented in PyTorch and trained and evaluated on the ATIS dataset. Check the [report](./report.pdf) for more implementation details.

## Get started
- Clone the repository
- Install the required dependencies by running `pip install -r requirements.txt`
- From the repository root, open and run the Jupyter notebook `Seq2Seq.ipynb`

**Note:** the model was developed and tested using Python 3.7.10.

## Project structure
All the code to define the model and run the experiments is available in `Seq2Seq.ipynb`.

The folder data contains the ATIS dataset, the `conlleval.pl` script and the pre-trained embedding weights, obtained using the `gensim` APIs and filtered to contain only the relevant tokens. 

The project report is available in `report.pdf`.
