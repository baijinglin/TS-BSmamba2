# TS-BSMAMBA2: A Two-Stage Band-Split Mamba-2 Network For Music Separation <br>
The paper is available at https://arxiv.org/abs/2409.06245
# Abstract
Music source separation (MSS) aims to separate mixed music into its distinct tracks, such as vocals, bass, drums, and more. MSS is considered to be a challenging audio separation task due to the complexity of music signals. Although the RNN and Transformer architecture are not perfect, they are commonly used to model the music sequence for MSS. Recently, Mamba-2 has already demonstrated high efficiency in various sequential modeling tasks, but its superiority has not been investigated in MSS. This paper applies Mamba-2 with a twostage strategy, which introduces residual mapping based on the mask method, effectively compensating for the details absent in the mask and further improving separation performance. Experiments confirm the superiority of bidirectional Mamba2 and the effectiveness of the two-stage network in MSS.

# Performance

<img width="938" alt="image" src="https://github.com/user-attachments/assets/6d10038f-86bb-40e3-9622-820b6f2a77f4">

# License

TS-BSMAMBA2 is licensed under the Apache License 2.0.

# Citication

@misc{bai2024twostagebandsplitmamba2network,
      title={A Two-Stage Band-Split Mamba-2 Network for Music Separation}, 
      author={Jinglin Bai and Yuan Fang and Jiajie Wang and Xueliang Zhang},
      year={2024},
      eprint={2409.06245},
      archivePrefix={arXiv},
      primaryClass={cs.SD},
      url={https://arxiv.org/abs/2409.06245}, 
}






