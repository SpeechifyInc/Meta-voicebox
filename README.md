![image](diagram.png)

<!-- ![image](diagram1.png) -->

![image](diagram2.png)

# **Voicebox - PyTorch**

Implementation of [**Voicebox**:](https://ai.facebook.com/blog/voicebox-generative-ai-model-speech/) Text-Guided Multilingual Universal Speech Generation at Scale. The first generative AI model for speech to generalize across tasks with state-of-the-art performance.

Large-scale generative models such as GPT and DALL-E have revolutionized
natural language processing and computer vision research. These models not only
generate high fidelity text or image outputs, but are also generalists which can solve
tasks not explicitly taught. In contrast, speech generative models are still primitive
in terms of scale and task generalization.

**Voicebox**, the most versatile text-guided generative model for speech at scale is
a non-autoregressive flow-matching model trained to infill speech, given audio
context and text, trained on over 50K hours of speech that are neither filtered nor
enhanced. Similar to GPT, Voicebox can perform many different tasks through
in-context learning, but is more flexible as it can also condition on future context.
Voicebox can be used for mono or cross-lingual zero-shot text-to-speech synthesis,
noise removal, content editing, style conversion, and diverse sample generation. In
particular, Voicebox outperforms the state-of-the-art zero-shot TTS model VALL-E
on both intelligibility (5.9% vs 1.9% word error rates) and audio similarity (0.580
vs 0.681) while being up to 20 times faster.

### **Todo:**

- [ ] add training script for Voicebox.
- [ ] add cross-lingual style transfer.
- [ ] add zero-shot text-to-speech synthesis.
- [ ] add transient noise removal and content editing.
- [ ] add diverse speech sampling and alignment-preserved style shuffling.

### **Citiation:**

```bibtex
@misc{voicebox2023,
      title={Voicebox: Text-Guided Multilingual Universal Speech Generation at Scale},
      author={Matthew Le, Apoorv Vyas, Bowen Shi, Brian Karrer, Leda Sari, Rashel Moritz, Mary Williamson, Vimal Manohar, Yossi Adi, Jay Mahadeokar, Wei-Ning Hsu},
      year={2023},
      link={https://research.facebook.com/file/2441102929387057/VoiceBox_arXiv_6_6.pdf}
}
```
