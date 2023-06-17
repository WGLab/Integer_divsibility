# Integer_divsibility
This page contains two files, [Int_div_mod2](https://github.com/WGLab/Integer_divsibility/blob/main/Int_div_mod2.ipynb) and [Int_div_mod3](https://github.com/WGLab/Integer_divsibility/blob/main/Int_div_mod3.ipynb), which are the code for the [paper](https://arxiv.org/abs/2304.01333) "Classification of integers based on residue classes by deep learning".

In particular, the two scripts outline a comprehensive examination of diverse deep learning architectures following distinct approaches to feature engineering. The outcome of this experimentation yielded results that were not only instinctive but also easily comprehensible. For a more in-depth analysis, we encourage readers to refer to the dedicated "Results" and "Discussion" sections in [paper](https://arxiv.org/abs/2304.01333). Furthermore, for those inclined, our code can be readily modified and employed for personalized testing and exploration. This flexibility allows interested individuals to tailor the code to their specific requirements and objectives.

## Int_div_mod2
This python script contains all the testings of deep neual networks on mod 2 problem, including all the feature engineering listed in Table (1)(a) with the same order.
## Int_div_mod3
This python script contains all the testings of deep neural networks on mod 3 problem, including all the feature engineering listed in Table (1)(b) with the same order.
## Fourier series regression
Furthermore, the paper incorporates a comprehensive exploration of the Fourier series regression method using ordinary least squares. This technique is extensively elucidated in Section 4.4 of the [paper](https://arxiv.org/abs/2304.01333). Reproducing the results of this method is remarkably simple using either the "statsmodels" library in Python or the "lm" function in R. Due to the straightforward nature of the implementation, we have decided not to include the code in this context. Interested readers can readily employ the aforementioned libraries and functions to replicate the analysis and obtain comparable outcomes.
