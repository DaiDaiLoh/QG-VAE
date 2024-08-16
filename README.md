<table>
  <tr>
    <td width="50%"><img src="teaser.png" width="100%"></td>
    <td>This is the code for the paper <a href="https://arxiv.org/abs/2407.11913">"Quantised Global Autoencoder: A Holistic Approach to Representing Visual Data"</a>.<br/><br/>The "QG-VAE.ipynb" notebook contains a minimal version, <b>without</b> additional sharpening (QGGAN), and without lightning speedups that make our code viable.<br/><br/>QGGAN.ipynb contains what we used for our experiments, including the fast lightning code and the option to add an additional sharpening (QGGAN). Use it after you read & understood the "demo"-file!</td>
  </tr>
  <tr>
    <td width="50%"><img src="examples.png" width="100%"></td>
    <td><img src="benchmarks_generation.png" width="100%"><br/>Performance of our approach for generation on CIFAR, compared to a regular VQ-VAE, trained on the same autoregressive transformer: Our approach converges to better results, as we assume 1D latent spaces to be much more native to be learned by transformer architectures.</td>
  </tr>
</table>

