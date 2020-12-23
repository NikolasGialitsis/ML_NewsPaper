<header><h1>Your Daily Machine Learning Newspaper</h1></header>| title                                                                | link                                                                                                            | img                                                                    |
|----------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------|
| Deploying a Simple UI for Python                                     | https://towardsdatascience.com/deploying-a-simple-ui-for-python-88e8e7cbbf61                                    | https://cdn-images-1.medium.com/max/1200/0*qq1KYo_jJmLn2hjl            |
| Hacking Super Intelligence                                           | https://towardsdatascience.com/hacking-super-intelligence-af5fe1fe6e26                                          | https://cdn-images-1.medium.com/max/1200/1*kfl0cA4OenIaBo8m4zUHzQ.jpeg |
| Low Effort Machine Learning Tools                                    | https://towardsdatascience.com/low-effort-machine-learning-tools-9622d7d57135                                   | https://cdn-images-1.medium.com/max/800/1*l-_uMYUimj73v-1JlAsXKg.jpeg  |
| Emerging problems in machine learning: making AI                     | https://towardsdatascience.com/emerging-problems-in-machine-learning-making-ai-good-3980bb9fdd39                | https://cdn-images-1.medium.com/max/800/1*_o6kgLxZmE8pTg-2cwfkdQ.jpeg  |
| OCR and the WordSearch solver AI                                     | https://towardsdatascience.com/ocr-and-the-wordsearch-solver-ai-515aeb816bdf                                    | https://cdn-images-1.medium.com/max/800/1*5UR8Yol9sE5x0j-T2oA_UQ.gif   |
| Deep Learning: GoogLeNet Explained                                   | https://towardsdatascience.com/deep-learning-googlenet-explained-de8861c82765                                   | https://cdn-images-1.medium.com/max/800/1*k3_mlHv44pQtJ_u7D7464g.png   |
| Classifying Images with Feature Transformations                      | https://towardsdatascience.com/classifying-images-with-feature-transformations-1fcb69b44fce                     | https://cdn-images-1.medium.com/max/800/0*7f9_pPTauYHwJYO1             |
| BFGS in a Nutshell: An Introduction to Quasi-Newton Methods          | https://towardsdatascience.com/bfgs-in-a-nutshell-an-introduction-to-quasi-newton-methods-21b0e13ee504          | https://cdn-images-1.medium.com/max/800/1*QdcaMRVvRVkjDMGAhZW4Ug.jpeg  |
| PyCaret and Streamlit: How to Create and Deploy Data Science Web App | https://towardsdatascience.com/pycaret-and-streamlit-how-to-create-and-deploy-data-science-web-app-273d205271a3 | https://cdn-images-1.medium.com/max/800/1*m5Rq5JMxdDy-Ml7y5qeKeg.jpeg  |
| What is TinyML, and why does it matter?                              | https://towardsdatascience.com/what-is-tinyml-and-why-does-it-matter-f5b164766876                               | https://cdn-images-1.medium.com/max/800/0*YCOmGd-CMq7x7sqG             |
| 6 Examples to Improve Your SQL Skills                                | https://towardsdatascience.com/6-examples-to-improve-your-sql-skills-76b40138f3cf                               | https://cdn-images-1.medium.com/max/800/1*v5HHnLCJIYvtZzK2wCcOjg.jpeg  || title                                                                                                                                                | abstract                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                 |
|------------------------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| compressive sensing using iterative hard thresholding with low precision   data representation: theory and applications	DOI:10.1109/tsp.2020.3010355 | modern scientific instruments produce vast amounts of data, which can overwhelm the processing ability of computer systems. lossy compression of data is an intriguing solution, but comes with its own drawbacks, such as potential signal loss, and the need for careful optimization of the compression ratio. in this work, we focus on a setting where this problem is especially acute: compressive sensing frameworks for interferometry and medical imaging. we ask the following question: can the precision of the data representation be lowered for all inputs, with recovery guarantees and practical performance? our first contribution is a theoretical analysis of the normalized iterative hard thresholding (iht) algorithm when all input data, meaning both the measurement matrix and the observation vector are quantized aggressively. we present a variant of low precision normalized {iht} that, under mild conditions, can still provide recovery guarantees. the second contribution is the application of our quantization framework to radio astronomy and magnetic resonance imaging. we show that lowering the precision of the data can significantly accelerate image recovery. we evaluate our approach on telescope data and samples of brain images using cpu and fpga implementations achieving up to a 9x speed-up with negligible loss of recovery quality.                                                                                                                                                                                                     |
| why do deep residual networks generalize better than deep feedforward   networks? -- a neural tangent kernel perspective                             | deep residual networks (resnets) have demonstrated better generalization performance than deep feedforward networks (ffnets). however, the theory behind such a phenomenon is still largely unknown. this paper studies this fundamental problem in deep learning from a so-called "neural tangent kernel" perspective. specifically, we first show that under proper conditions, as the width goes to infinity, training deep resnets can be viewed as learning reproducing kernel functions with some kernel function. we then compare the kernel of deep resnets with that of deep ffnets and discover that the class of functions induced by the kernel of ffnets is asymptotically not learnable, as the depth goes to infinity. in contrast, the class of functions induced by the kernel of resnets does not exhibit such degeneracy. our discovery partially justifies the advantages of deep resnets over deep ffnets in generalization abilities. numerical results are provided to support our claim.                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                                         |
| long-term effect estimation with surrogate representation                                                                                            | there are many scenarios where short- and long-term causal effects of an intervention are different. for example, low-quality ads may increase short-term ad clicks but decrease the long-term revenue via reduced clicks. this work, therefore, studies the problem of long-term effect where the outcome of primary interest, or primary outcome, takes months or even years to accumulate. the observational study of long-term effect presents unique challenges. first, the confounding bias causes large estimation error and variance, which can further accumulate towards the prediction of primary outcomes. second, short-term outcomes are often directly used as the proxy of the primary outcome, i.e., the surrogate. nevertheless, this method entails the strong surrogacy assumption that is often impractical. to tackle these challenges, we propose to build connections between long-term causal inference and sequential models in machine learning. this enables us to learn surrogate representations that account for the temporal unconfoundedness and circumvent the stringent surrogacy assumption by conditioning on the inferred time-varying confounders. experimental results show that the proposed framework outperforms the state-of-the-art.                                                                                                                                                                                                                                                                                                                        |
| tight bounds on the smallest eigenvalue of the neural tangent kernel for   deep relu networks                                                        | a recent line of work has analyzed the theoretical properties of deep neural networks via the neural tangent kernel (ntk). in particular, the smallest eigenvalue of the ntk has been related to memorization capacity, convergence of gradient descent algorithms and generalization of deep nets. however, existing results either provide bounds in the two-layer setting or assume that the spectrum of the ntk is bounded away from 0 for multi-layer networks. in this paper, we provide tight bounds on the smallest eigenvalue of ntk matrices for deep relu networks, both in the limiting case of infinite widths and for finite widths. in the finite-width setting, the network architectures we consider are quite general: we require the existence of a wide layer with roughly order of $n$ neurons, $n$ being the number of data samples; and the scaling of the remaining widths is arbitrary (up to logarithmic factors). to obtain our results, we analyze various quantities of independent interest: we give lower bounds on the smallest singular value of feature matrices, and upper bounds on the lipschitz constant of input-output feature maps.                                                                                                                                                                                                                                                                                                                                                                                                                             |
| finding global minima via kernel approximations                                                                                                      | we consider the global minimization of smooth functions based solely on function evaluations. algorithms that achieve the optimal number of function evaluations for a given precision level typically rely on explicitly constructing an approximation of the function which is then minimized with algorithms that have exponential running-time complexity. in this paper, we consider an approach that jointly models the function to approximate and finds a global minimum. this is done by using infinite sums of square smooth functions and has strong links with polynomial sum-of-squares hierarchies. leveraging recent representation properties of reproducing kernel hilbert spaces, the infinite-dimensional optimization problem can be solved by subsampling in time polynomial in the number of function evaluations, and with theoretical guarantees on the obtained minimum.   given $n$ samples, the computational cost is $o(n^{3.5})$ in time, $o(n^2)$ in space, and we achieve a convergence rate to the global optimum that is $o(n^{-m/d + 1/2 + 3/d})$ where $m$ is the degree of differentiability of the function and $d$ the number of dimensions. the rate is nearly optimal in the case of sobolev functions and more generally makes the proposed method particularly suitable for functions that have a large number of derivatives. indeed, when $m$ is in the order of $d$, the convergence rate to the global optimum does not suffer from the curse of dimensionality, which affects only the worst-case constants (that we track explicitly through the paper). |