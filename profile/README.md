KanTV-AI <b>cares</b> Kan(aka English "Watch") TV on Android phone(can be seen as a standard embedded development board equipped with a special Linux distribution) or Android-based device(Smart TV, Smart STB,......).

KanTV-AI focus on learning/studying/practising device-AI solution in <b>real application</b> & <b>real scenario</b> on <b>ANY</b> mainstream <b>Android phone</b> equipped with <b>high-end</b> mobile SoC(such as Snapdragon 8Gen3, Snapdragon 8Elite or customized 8Gen3/8Elite......).

The Project KanTV is <b>mainly powered</b> by [llama.cpp](https://github.com/ggml-org/llama.cpp) + [whisper.cpp](https://github.com/ggml-org/whisper.cpp) +  [stable-diffusion.cpp](https://github.com/leejet/stable-diffusion.cpp) + [FFmpeg](https://www.ffmpeg.org/) + [opencv-mobile](https://github.com/nihui/opencv-mobile). the core AI engine is driven by [ggml](https://github.com/ggml-org/ggml), we'd like to [make contributions to upstream](https://github.com/ggml-org/llama.cpp/pull/12326) project llama.cpp.

### Software arch

![Image](https://github.com/user-attachments/assets/a01efc55-b9be-4e4b-b5b9-7a4c8723278b)

### News
- `[2025 May 02]` [release v1.6.8](https://github.com/kantv-ai/kantv/releases/tag/kantv-1.6.8)
- `[2025 Mar 11]` [submit ggml-hexagon PR to upstream llama.cpp](https://github.com/ggml-org/llama.cpp/pull/12326)
- `[2025 Feb 12]` create kantv-ai in github and re-launch dev activity of project kantv and [ggml-qnn](https://github.com/zhouwg/ggml-hexagon/discussions/18)(rename to ggml-hexagon since 2025 March 19)
<!--
- `[2025 Jan 29]` back to Github and llama.cpp community due to DeepSeek-R1
- `[2024 Jul 18]` completely left Github and llama.cpp community
- `[2024 Mar 29]` [PoC:Add Qualcomm mobile SoC native backend for GGML](https://github.com/kantv-ai/kantv/issues/121)
- `[2024 Mar 05]` [first touch with whisper.cpp](https://github.com/kantv-ai/kantv/issues/64)
- `[2024 Feb 22]` first touch with ggml/device-AI tech
-->

### the KanTV way

- Simple is the beautiful

   we believe the philosophy of "<b>simple is the beautiful</b>" which <b>comes from the great Unix</b>.

- Make it run, then make it right, then make it fast
  - this is a practical approach in R&D activity
  - a [candicated PR(a specified llama.cpp backend for Qualcomm Hexagon NPU)](https://github.com/ggml-org/llama.cpp/pull/12326) could run and right at the moment on Qualcomm high-end mobile SoC based Android phone.
  - this approach also used in Project KanTV(all efforts in Project KanTV will be used in <b>real scenario</b> in real Android APK on Android phone equipped with Qualcomm's <b>state-of-the-art</b> 8Elite/<b>8Elite2/8Elite3</b>/8Elite4/... mobile SoC.
    
- Explore and have fun!

  we believe the philosophy of <b>try crazy ideas, build wild demos, and push the edge of what’s possible</b>(which is one of the core spirits of ggml-way).

### Roadmap

https://github.com/kantv-ai/kantv/discussions/262

### Contribution
- report issues and contribute PR to KanTV-AI are both greatly welcomed.

### Collaboration

- domain tech experts and AI experts are greatly welcomed to join kantv-ai.

