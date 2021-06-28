# Deep Networks for MRI

See [Matt's paper summaries](https://docs.google.com/document/d/1QiSgQenlHWFY51MI9jMA6sHqJs3lAL9AD3rE31BVAZM/edit?usp=sharing) for more information about each paper.

## Deep-Image-Prior Based Methods

*   V. Lempitsky, A. Vedaldi and D. Ulyanov, "Deep Image Prior," 2018 IEEE/CVF Conference on Computer Vision and Pattern Recognition, 2018, pp. 9446-9454, doi: 10.1109/CVPR.2018.00984. [\[arxiv\]](https://arxiv.org/pdf/1711.10925.pdf)

*   Z. Sun, F. Latorre, T. Sanchez and V. Cevher, "A Plug-and-Play Deep Image Prior," ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 2021, pp. 8103-8107, doi: 10.1109/ICASSP39728.2021.9414879. [\[ieee\]](https://ieeexplore-ieee-org.proxy.lib.ohio-state.edu/document/9414879)

## Langevin-Score Based Methods

*   Y. Song and S. Ermon, "Generative modeling by
    estimating gradients of the data distribution," In Advances
    in Neural Information Processing Systems, 2019, pp. 11895–11907. [\[arxiv\]](https://arxiv.org/pdf/1907.05600.pdf)

*   Z. Kadkhoadie and E. P. Simoncelli, "Solving Linear Inverse Problems Using the Prior Implicit in a
    Denoiser," arXiv preprint arXiv:2007.13640, 2020. [\[arxiv\]](https://arxiv.org/pdf/2007.13640.pdf)

*   R. Laumont, V. De Bortoli, A. Almansa, J. Delon, A. Durmus, and M. Pereya, "Bayesian Imaging Using Plug & Play Priors: When Langevin Meets
    Tweedie," arXiv preprint arXiv:2103.04715, 2021. [\[arxiv\]](https://arxiv.org/pdf/2103.04715.pdf)

*   Y. Song, J. Sohl-Dickstein, D. P. Kingma, A. Kumar, S. Ermon, and B.
    Poole, "Score-Based Generative Modeling through Stochastic
    Differential Equations," arXiv preprint arXiv:2011.13456, 2020. [\[openreview\]](https://openreview.net/forum?id=PxTIG12RRHS) [\[jax/flax\]](https://github.com/yang-song/score_sde) [\[pytorch\]](https://github.com/yang-song/score_sde_pytorch)

*   B. Kawar, G. Vaksman, and M. Elad, "Solving Noisy Inverse Problems Stochastically,"
    arXiv preprint arXiv:2105.14951, 2021. [\[paperswithcode\]](https://paperswithcode.com/paper/snips-solving-noisy-inverse-problems)

*   T. Nguyen, G. Jagatap, and C. Hegde, "Provable Compressed Sensing with Generative Priors via Langevin
    Dynamics," arXiv preprint arXiv:2102.12643, 2021. [\[arXiv\]](https://arxiv.org/pdf/2102.12643.pdf)
    
## Optimization with a Generative Prior

*   A. Bora, A. Jalal, E.Price, and A. G. Dimakis, "Compressed sensing using
    generative models," In Proceedings of the 34th International Conference on Machine Learning,  JMLR. org,
    vol. 70, pp. 537–546, 2017. [\[arXiv\]](https://arxiv.org/pdf/1703.03208.pdf)

*   A. Jalal, L. Liu, A. G. Dimakis, and C. Caramanis, "Robust Compressed Sensing of Generative Models," 
    arXiv preprint arXiv:2006.09461, 2020. [\[arXiv\]](https://arxiv.org/pdf/2006.09461.pdf)
    
*   Y. Yang, H. Wang, H. Qiu, J. Wang and Y. Wang, 
    "Non-Convex Sparse Deviation Modeling Via Generative Models," 
    ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 
    2021, pp. 2345-2349, doi: 10.1109/ICASSP39728.2021.9414170. [\[ieee\]](https://ieeexplore-ieee-org.proxy.lib.ohio-state.edu/document/9414170)

*   V. Killedar, P. K. Pokala and C. Sekhar Seelamantula, 
    "Sparsity Driven Latent Space Sampling for Generative Prior Based Compressive Sensing," 
    ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 
    2021, pp. 2895-2899, doi: 10.1109/ICASSP39728.2021.9413451. [\[ieee\]](https://ieeexplore-ieee-org.proxy.lib.ohio-state.edu/document/9413451)
    
*   F. L. Gómez, A. Eftekhari, and V. Cevher, "Fast and Provable ADMM for Learning with Generative Priors,"
    arXiv preprint arXiv:1907.03343, 2019. [\[arXiv\]](https://arxiv.org/pdf/1907.03343.pdf)

## Iterative Invertible Neural Network

*   V. A. Kelkar, S. Bhadra, and M. A. Anastasio, "Compressible
    Latent-Space Invertible Networks for Generative Model-Constrained
    Image Reconstruction," IEEE Trans. Comp. Imaging, vol. 7, pp.
    209-223,
    2021. [\[arxiv\]](https://arxiv.org/pdf/2007.02462.pdf) [\[ieee\]](https://ieeexplore.ieee.org/iel7/6745852/6960042/09318016.pdf?casa_token=H8-rAEQL5TYAAAAA:hEI5vYD3kecKiaHYgXyGpnTvI5tFcJwrJx6h7A3zOHpk9y95gjlkoE6nuL0MVxVRsTse_Rg) 
    
## Supervised MRI GAN

*   G. Yang et al., "DAGAN: Deep De-Aliasing Generative Adversarial Networks for Fast Compressed Sensing MRI Reconstruction," 
    in IEEE Transactions on Medical Imaging, vol. 37, no. 6, pp. 1310-1321, 
    June 2018, doi: 10.1109/TMI.2017.2785879. [\[ieee\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8233175)

*   T. M. Quan, T. Nguyen-Duc and W. -K. Jeong, 
    "Compressed Sensing MRI Reconstruction Using a Generative Adversarial Network With a Cyclic Loss," 
    in IEEE Transactions on Medical Imaging, vol. 37, no. 6, pp. 1488-1497, 
    June 2018, doi: 10.1109/TMI.2018.2820120. [\[ieee\]](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8327637)

*   M. Mardani et al., "Deep Generative Adversarial Neural Networks for Compressive Sensing MRI," 
    in IEEE Transactions on Medical Imaging, vol. 38, no. 1, pp. 167-179,
    January 2019, doi: 10.1109/TMI.2018.2858752. [\[ieee\]](https://ieeexplore-ieee-org.proxy.lib.ohio-state.edu/stamp/stamp.jsp?tp=&arnumber=8417964)

*   R. Shail, I. David, O. Shitrit, and T.R. Raviv, "Subsampled brain MRI reconstruction by generative adversarial neural networks,"
    Medical Image Analysis, 2020, p. 101747. [\[ScienceDirect\]](https://www-sciencedirect-com.proxy.lib.ohio-state.edu/science/article/pii/S1361841520301110)

*   P. Deora, B. Vasudeva, S. Bhattacharya and P. M. Pradhan, "Structure Preserving Compressive Sensing MRI Reconstruction using Generative Adversarial Networks," 
    2020 IEEE/CVF Conference on Computer Vision and Pattern Recognition Workshops (CVPRW), 
    2020, pp. 2211-2219, doi: 10.1109/CVPRW50498.2020.00269. [\[ieee\]](https://ieeexplore.ieee.org/document/9151087)

*   Z. Yuan et al., "SARA-GAN: Self-Attention and Relative Average Discriminator Based Generative Adversarial Networks for Fast Compressed Sensing MRI Reconstruction,"
    Frontiers in Neurinformatics, 2020. [\[frontiersin\]](https://www.frontiersin.org/articles/10.3389/fninf.2020.611666/full)

*   G. Yang, J. Lv, Y. Chen, J. Huang, and J. Zhu, "Generative Adversarial Networks (GAN) Powered Fast Magnetic
    Resonance Imaging --- Mini Review, Comparison and Perspectives," arXiv preprint arXiv:2105.01800, 2021. [\[arXiv\]](https://arxiv.org/pdf/2105.01800.pdf)

## Unsupervised MRI GAN

*   E. K. Cole, J. M. Pauly, S. S. Vasanawala, and F. Ong, "Unsupervised MRI Reconstruction with Generative Adversarial
    Networks," arXiv preprint arXiv:2008.13065, 2020. [\[arXiv\]](https://arxiv.org/abs/2008.13065)


## Contrastive GAN

*   H. Zhang, J. Y. Koh, J. Baldridge, H. Lee, and Y. Yang, "Cross-Model Contrastive Learning for Text-to-Image
    Generation," arXiv preprint arXiv:2101.04702, 2021. [\[google AI
    blog\]](http://ai.googleblog.com/2021/05/cross-modal-contrastive-learning-for.html)
    
## Post-Processed GAN
*   M. Vella and J. F. C. Mota, "Overcoming Measurement Inconsistency In Deep Learning For Linear Inverse Problems: Applications In Medical Imaging," 
    ICASSP 2021 - 2021 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), 
    2021, pp. 8113-8117, doi: 10.1109/ICASSP39728.2021.9414173. [\[ieee\]](https://ieeexplore-ieee-org.proxy.lib.ohio-state.edu/document/9414173)
