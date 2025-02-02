We observed performance with respect to normalization, varying hidden layer sizes as well as number of epochs.

## Sizes

Started with hidden sizes **512, 256** with poorest results. Optimal combination reached at sizes **4096, 2048**.

## Epochs

Epochs - from **10 to 100**, 10 giving the worst accuracy (**<15%**) and 100 giving a decent or above accuracy. (Did run till **500** as well after which there was no improvement at all.)

## Normalization

Normalization played a big role. **Without it, the model was very slow to converge**, and **with it, it became faster**. It also gave **much better results** (with highest accuracy reaching somewhere around **57%**).

## Results

Some of the results include:

- **Accuracy on test set with epochs = 10 and hidden size 1, 2 = 512, 256** → **11.29%**
- **Accuracy on test set with epochs = 100 and hidden size 1, 2 = 4096, 2048** → **57.07%**
- **Accuracy on test set with epochs = 25 and hidden size 1, 2 = 4096, 2048, WITHOUT NORMALIZATION** → **11.50%**
