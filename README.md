Evaluating and Circumventing Safety Measures in Large Language Models through Adversarial LoRA Fine-Tuning

The burgeoning complexity of large language models (LLMs) brings forth pressing challenges in ensuring their safe deployment when model weights are accessible. Our study delves into these model’s susceptibility to adversarial fine-tuning, using
Low-Rank Adaptation (LoRA) as a pivotal tool. This investigation focuses on the robustness of safety training measures and their ability to mitigate misuse risks in LLMs. The potential dangers of releasing model weights, a common scenario, are
also explored. We employed a data set comprising harmful prompts alongside the AdvBench benchmark to fine-tune the Llama-2-7b-chat model using LoRA. This method allowed us to assess the model’s vulnerability to generating unsafe content
and its capability to bypass existing safety protocols. The findings from our study reveal significant vulnerabilities within these models. We observed high Harmful Scores and a notable success rate in circumventing safety measures, underscoring
the limitations of current safety protocols in LLMs. Our research highlights the urgent need for more stringent safety measures and ethical considerations in AI model deployment. As shown by our experiments, the ease with which safety
measures can be subverted raises serious concerns about the potential misuse of such technology. Moreover, our study emphasizes the importance of responsible practices in the release and public accessibility of AI models. In the broader context
of AI safety and ethics, our findings contribute valuable insights into the ongoing dialogue on responsible AI development. They advocate for a proactive approach to developing AI technologies that are not only powerful but also align with societal
values and norms.
