<table>
  <tr>
    <td><img src="teaser.png" width="100%"></td>
    <td>This is the (preliminary) code for the paper <a href="https://arxiv.org/abs/2407.11913">"Quantised Global Autoencoder: A Holistic Approach to Representing Visual Data"</a>.<br/> Everything else will follow soon(tm)<br/><br/>The "demo.ipynb" notebook contains a minimal version, <b>without</b> additional sharpening (QGGAN), and without lightning speedups that make our code viable.<br/><br/>QGGAN.ipynb contains what we used for our experiments, including lightning and the option to add an additional sharpening (QGGAN). Use it after you read & understood the "demo"-file!</td>
  </tr>
</table>
<table>
  <tr>
    <td><img src="examples.png" width="50%"></td>
    <td><img src="benchmarks_generation.png" width="50%"><br/>Performance of our approach for generation on CIFAR, compared to a regular VQ-VAE, trained on the same autoregressive transformer: Our approach converges to better results, as we assume 1D latent spaces to be much more native to be learned by transformer architectures.</td>
  </tr>
</table>

