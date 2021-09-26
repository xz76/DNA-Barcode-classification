README
================

## Methods

In this competition, I used seven methods to approach the prediction.

1.  1D CNN

    -   File location: “/Methods/1D\_CNN.ipynb”

    -   The final accuracy at Kaggle is 94.004%.

2.  2D CNN trained on the one-hot encoder

    -   File location: “/Methods/2D\_CNN.ipynb”

    -   The final accuracy at Kaggle is 95.208%.

3.  LSTM/Recurrent neural networks

    -   File location:
        “/Methods/LSTM\_Recurrent\_neural\_networksipynb.ipynb”

    -   The final accuracy at Kaggle is 94.943%.

4.  Variational auto encoder (VAE) fed into a supervised learning
    algorithm

    -   File location:
        “/Methods/Variational\_auto\_encoder\_(VAE).ipynb”

    -   The final accuracy at Kaggle is 94.317%.

5.  Feedforward neural network

    -   File location: “/Methods/FNN.ipynb”

    -   The final accuracy at Kaggle is 94.341%.

6.  Natural language processing(NLP) embeddings of k-mers + multinomial

    -   File location:
        “/Methods/NLP\_with\_Multinomial\_Classifier.ipynb”

    -   The final accuracy at Kaggle is 96.990%. (Due to the kaggle
        entry issue, I did not submit this result successfully.)

7.  Natural language processing(NLP) + CNN

    -   File location: “/Methods/NLP\_with\_CNN.ipynb”

    -   The final accuracy at Kaggle is 96.291%.

8.  Consider new species.(Submission failed)

    -   File location: “/Data/mv\_predict\_3.csv”

    -   The final accuracy at Kaggle is 97.592% on public leaderboard,
        and 97.432% on private leaderboard.

    -   The unperfect thing is that there should be five entries each
        day, but after four entries, the system did not allow me to
        submit the prediction. I am new to kaggle so I have no idea
        regarding this issue. This is the best prediction among all my
        results after I taking new species into account. The main idea
        is combining all seven results together and training to figure
        out the new species.

## Data

-   All methods can be run directly by using the original data sets at
    “/Data” folder. No external data is needed.

-   Since different methods may use a different types of data forms,
    such as character to integer, one-hot encoder, or k-mers, thus,
    different methods were organized separately and can be run
    independently.
