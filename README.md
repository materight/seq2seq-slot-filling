# [CT1] An Attention-based Sequence-to-Sequence Model for Concept Tagging
**Matteo Destro (221222)** \
**Natural Language Understanding [CT1]** \
**Year 2020/21** \
\
A sequence-to-sequence model with attention and beam search for concept tagging. Trained and evaluated on the ATIS dataset.

## Get started
- Clone the repository
- Install the required dependencies by running `pip install torch numpy pandas matplotlib`
- Open and run the Jupyter notebook `Seq2Seq.ipynb`

## Project structure
All the code to define the model and run the experiments is available in `Seq2Seq.ipynb`.

The folder data contains the ATIS dataset, the `conlleval.pl` script and the pre-trained embedding weights, obtained using the `gensim` APIs and filtered to contain only the relevant tokens. 

The project report is available in `report.pdf`.