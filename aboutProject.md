---
layout: page
title: About the Project
permalink: /AboutTheProject/
---

### What is AI?
Artificial intelligence (AI) is a branch of computer science which aims to replicate human intelligence using computers and learning from new data. Unlike traditional computing AI is not told specifically what to do or what to look for but is given examples to find patterns in, it can then use these examples to perform tasks on new data. AI is already in use in many everyday applications such as email spam filters, Alexa, video suggestions on streaming apps etc. 

### What is laryngeal cancer?
The larynx (also known as the voice box) is a part of the throat which is involved in the production of speech as well as helping with breathing. 
<figure>
  <img  width="500"  src="/images/ThroatDiagram.jpg" style="margin:10px 10px">
  <figcaption>A diagram of the structures in the throat including the larynx. (https://www.macmillan.org.uk/cancer-information-and-support/head-and-neck-cancer/the-mouth-throat-nose-and-ears)</figcaption>
</figure>


For more information please visit the NHS website [here](https://www.nhs.uk/conditions/laryngeal-cancer/)

### How can AI detect laryngeal cancer?
One of the initial symptoms of laryngeal cancer can be a hoarse voice or a change in voice quality. However, this can also be a symptom of many other, non-cancerous, diseases. We want to investigate if AI is capable of finding the feature or features within speech which differentiates cancer and non-cancer patients. This will be investiagted in multiple different ways. Two common sets of features that will be investiagted are acoustic features and spectrograms. Acoustic features are generally focused on the amplitude and frequency of the sound. Spectrograms are visualisations of a sound's frequency and amplitude. Spectrograms for both a healthy patient and a throat cancer patient can be seen below.

<table cellpadding="10">
  <tr>
    <th><img  src="/images/HealthySpec.png" style="max-width: 95%;"></th>
    <th><img  src="/images/CancerSpec.png" style="max-width: 95%;"></th>
  </tr>
  <tr>
    <td>A spectrogram of a healthy person saying "ah"</td>
    <td>A spectrogram of a throat cancer patient saying "ah"</td>
  </tr>
</table>
