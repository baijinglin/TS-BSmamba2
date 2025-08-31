# A Two-Stage Band-Split Mamba-2 Network For Music Source Separation <br>
# Abstract
Music source separation (MSS) aims to separate mixed music into its distinct tracks, such as vocals, bass, drums, and more. MSS is considered to be a challenging audio separation task due to the complexity of music signals. Although the RNN and Transformer architecture are not perfect, they are commonly used to model the music sequence for MSS. Recently, Mamba-2 has already demonstrated high efficiency in various sequential modeling tasks, but its superiority has not been investigated in MSS. This paper applies Mamba-2 with a twostage strategy, which introduces residual mapping based on the mask method, effectively compensating for the details absent in the mask and further improving separation performance. Experiments confirm the superiority of bidirectional Mamba2 and the effectiveness of the two-stage network in MSS.

# Performance

<p align="center">
  <img width="938" alt="image" src="https://github.com/user-attachments/assets/6d10038f-86bb-40e3-9622-820b6f2a77f4">
</p>

<p align="center">
  <img width="515" alt="image" src="https://github.com/user-attachments/assets/44fd91a7-676f-487b-80b7-230e3b60f82b">
</p>


# Usage
### TS-BSMAMBA2:
```bash
python TS-BSmamba2.py
```

### L-TS-BSMAMBA2 (Lightweight model):   
```bash
python L-TS-BSmamba2.py
```
# Audio Samples-- Arise - Run Run Run
You can download them using the following link.</br>
https://mega.nz/folder/qYBzXL7S#c0qBxQss-PxPue27YqCdfA</br></br>
Note:
{track} = 'vocals, bass, drums, other'
- id3_mixture.wav: Mixture
- id3_{track}.wav: Target
- id3_mixture_{track}.wav: SIMO BSRNN results
- id3_mixture_{track}_mask.wav: TS-BSmamba2 one-stage results
- id3_mixture_{track}_map.wav: TS-BSmamba2 two-stage results

# License
TS-BSMAMBA2 is licensed under the Apache License 2.0.

# Contact
For any questions or feedback regarding TS-BSMAMBA2, feel free to reach out to us via email:  
[bjlin@mail.imu.edu.cn](mailto:bjlin@mail.imu.edu.cn)

