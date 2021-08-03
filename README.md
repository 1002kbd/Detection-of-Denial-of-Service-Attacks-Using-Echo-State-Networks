# Detection-of-Denial-of-Service-Attacks-Using-Echo-State-Networks

Denial of Service and Distributed Denial of Service attacks are major threats to communication security. These cyber attacks are evolving and becoming more difficult to identify and, hence, a number of detection approaches have been proposed. Various machine learning techniques have proved useful in detecting network intrusions. We apply echo state networks to detect known DoS and DDoS attacks. Echo state networks are a reservoir computing approach to train recurrent neural networks. The reservoir in the echo state networks serves as a memory and as a nonlinear high dimensional expansion of the input. The performance of echo state network models depends on settings of reservoir hyperparameters: input scaling, spectral radius, leaking rate, size and sparsity of the reservoir, and distribution of nonzero elements. The most important features are selected using an extra-trees classifier. We use network intrusion and Internet routing datasets. We compare echo state network models to bidirectional long short-term memory, one of the widely used recurrent neural networks, and evaluate their performance based on accuracy, F-Score, false alarm rate, and training time. 

Each folder contains code and datasets (except of CIC-IDS: datasets are too large to upload).
-- Code: feature selection (extra trees) and ESN code. The code relies on several external libraries: numpy, pandas, scipy, sklearn, and math.

-- BGP Datasets: Slammer, Nimda, Code Red I Internet worms, and BGP records from large DDoS attacks that targeted AWS in 2019 and 2020.

