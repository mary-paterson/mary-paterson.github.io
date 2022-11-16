---
layout: page
title: Comparing Denoised Audio
permalink: /DenoisedAudio/
---

In this work we created a support vector machine classifier using clean speech samples. We then added background noise at three different levels (signal to noise ratio 5, 10, and 20). Before extracting acoustic features the recordings were normalized. Using a Wiener filter [1] we then denoised the recordings and evaluated the classifier on the clean, noisy, and denoised recordings. The full pipeline can be seen below:

<figure>
  <img  width="500"  src="/images/ExperimentPipeline.png" style="margin:10px 10px">
</figure>

You can listen to examples of the clean, noisy, and denoised audio below. 

<table>
  <tr>
    <th>Clean</th>
    <th>Noisy</th>
    <th>Denoised</th>
  </tr>
  <tr>
    <td><audio controls style="width: 200px;">
  <source src="/Audio/clean_1027-i_n.wav" type="audio/wav">
Your browser does not support the audio element.
</audio></td>
    <td><audio controls style="width: 200px;">
  <source src="/Audio/noisy_1027-i_n.wav" type="audio/wav">
Your browser does not support the audio element.
</audio></td>
    <td><audio controls style="width: 200px;">
  <source src="/Audio/denoised_1027-i_n.wav" type="audio/wav">
Your browser does not support the audio element.
</audio></td>
  </tr>
  <tr>
    <td><audio controls style="width: 200px;">
  <source src="/Audio/clean_1336-i_n.wav" type="audio/wav">
Your browser does not support the audio element.
</audio></td>
    <td><audio controls style="width: 200px;">
  <source src="/Audio/noisy_1336-i_n.wav" type="audio/wav">
Your browser does not support the audio element.
</audio></td>
    <td><audio controls style="width: 200px;">
  <source src="/Audio/denoised_1336-i_n.wav" type="audio/wav">
Your browser does not support the audio element.
</audio></td>
  </tr>
    <tr>
    <td><audio controls style="width: 200px;">
  <source src="/Audio/clean_1974-u_n.wav" type="audio/wav">
Your browser does not support the audio element.
</audio></td>
    <td><audio controls style="width: 200px;">
  <source src="/Audio/noisy_1974-u_n.wav" type="audio/wav">
Your browser does not support the audio element.
</audio></td>
    <td><audio controls style="width: 200px;">
  <source src="/Audio/denoised_1974-u_n.wav" type="audio/wav">
Your browser does not support the audio element.
</audio></td>
  </tr>
</table>

[1] Pascal Scalart (2022). Wiener filter for Noise Reduction and speech enhancement (https://www.mathworks.com/matlabcentral/fileexchange/24462-wiener-filter-for-noise-reduction-and-speech-enhancement), MATLAB Central File Exchange. Retrieved November 11, 2022.



