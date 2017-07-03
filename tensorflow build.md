#build & test log
-------------------------------------
- broadwell
    - 272/batch=2048

    ```
    [27.33][17.39]Iter 2048 , Minibatch Loss= 63396.062500, Training Accuracy= 0.09961
    [48.97][21.64]Iter 22528 , Minibatch Loss= 25943.226562, Training Accuracy= 0.30957
    [68.61][19.63]Iter 43008 , Minibatch Loss= 13662.499023, Training Accuracy= 0.51611
    [88.21][19.6]Iter 63488 , Minibatch Loss= 7877.036621, Training Accuracy= 0.67090
    [107.72][19.5]Iter 83968 , Minibatch Loss= 6205.614258, Training Accuracy= 0.73242
    [127.12][19.41]Iter 104448 , Minibatch Loss= 5100.070801, Training Accuracy= 0.76904
    [146.63][19.51]Iter 124928 , Minibatch Loss= 4085.560791, Training Accuracy= 0.80518
    [165.93][19.3]Iter 145408 , Minibatch Loss= 3544.935547, Training Accuracy= 0.82812
    [185.52][19.6]Iter 165888 , Minibatch Loss= 3206.145996, Training Accuracy= 0.83643
    [204.88][19.36]Iter 186368 , Minibatch Loss= 2691.526855, Training Accuracy= 0.85156
    ```
- mkl
    - 272/batch=2048

    ```
    [27.17][27.17]Iter 8763392 , Minibatch Loss= 48.481636, Training Accuracy= 0.98389
    [28.97][1.79]Iter 8767488 , Minibatch Loss= 48.719269, Training Accuracy= 0.98340
    [33.29][4.32]Iter 8787968 , Minibatch Loss= 47.009068, Training Accuracy= 0.98340
    [37.64][4.35]Iter 8808448 , Minibatch Loss= 46.249680, Training Accuracy= 0.98242
    [41.69][4.05]Iter 8828928 , Minibatch Loss= 28.811796, Training Accuracy= 0.98828
    [45.94][4.25]Iter 8849408 , Minibatch Loss= 26.846550, Training Accuracy= 0.98779
    [49.66][3.7]Iter 8869888 , Minibatch Loss= 42.506992, Training Accuracy= 0.98291
    [53.99][4.32]Iter 8890368 , Minibatch Loss= 29.698177, Training Accuracy= 0.98535
    [57.88][3.89]Iter 8910848 , Minibatch Loss= 32.587132, Training Accuracy= 0.98779
    [61.54][3.66]Iter 8931328 , Minibatch Loss= 34.705845, Training Accuracy= 0.98975
    [65.33][3.79]Iter 8951808 , Minibatch Loss= 18.150543, Training Accuracy= 0.99072
    ```

- s