<div align="center">


# Features Low Vram for GPU Poor


# DON'T CLONE THIS REPO, IT WON'T WORK AS IT ALL DEPENDS ON THE PYTHON_EMBEDED 3.12.10 TO WORK! 


## I made this YuE 2 Portable 1 click install for Windows that uses Nvidia GTX 10XX, 16XX, RTX Quadro, 20XX, 30XX, 40XX, 50XX GPU. Installs Torch with Cuda, Flash Attention, Triton & all other requirements also creates Launch YuE 2 & Music Desktop Shortcuts. Automatically saves generations into "outputs" folder. Automatically saves last used settings in .json file & loads them automatically on startup.


## Click here to jump to Install 👉 [Installation](#-Installation) 👈


![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/redtash1/YuE2_Windows/total?style=for-the-badge&labelColor=orange&color=0000ff)



</div> 


---


<img width="1907" height="1038" alt="Screenshot 2026-10-20 074050" src="https://github.com/user-attachments/assets/775b58a0-5c0a-4806-9f01-dfc3c117631e" />


----


# 📦 Installation

## Nvidia GTX 10XX, 16XX, RTX Quadro, 20XX, 30XX, 40XX, 50XX 

### Requirements: Minimum Ram 24GB & VRAM 6GB should work but not guaranteed. Recommend Ram 32GB & VRAM 8GB.


1. Make sure you have Git installed, if not download the Git Standalone Installer and click on Git for Windows/x64 Setup. 👉 [Git Standalone Installer Download](https://git-scm.com/downloads/win) 👈 To install Git, double click Git.exe and just keep clicking next until it's installed, you don't need to change anything.


2. Make sure your Nvidia graphics drivers are up-to-date. If they are not or if your not sure, please click on the following link to download Nvidia graphics drivers. 👉 [Nvidia Drivers](https://www.nvidia.com/en-us/software/nvidia-app/) 👈

3. Make sure that you have NVIDIA's [CUDA Toolkit](https://developer.nvidia.com/cuda-toolkit) version **13.0** (or newer) installed on your system.

4. Make sure you have FFMPEG Shared downloaded & on PATH. Download 👉 [ffmpeg-release-full-shared.7z](https://www.gyan.dev/ffmpeg/builds/) 👈

5.  Now after you have made sure Nvidia GPU drivers are up to date and Git is installed, download YuE 2 Windows 1 Click Install
 from here 👉 [YuE 2 Windows 1 Click Install](https://github.com/Redtash1/krea_2_Windows_1_Click_Install/releases) 👈 or from the Releases section at the top right of this page.

6. After downloading, extract YuE 2 Windows 1 Click Install ZIP file and pick where you would like to extract the zip files too.

7. Then open YuE 2 Windows 1 Click Install main folder, you will see this in the root
----

<img width="973" height="213" alt="Screenshot 2026-10-20 074254" src="https://github.com/user-attachments/assets/85275a6d-c0a2-48d9-ba67-ad9a5a033b18" />

----
8. Then double click on Install_YuE2.bat to start the installation. It will install everything.  After installation is finished, slowly scroll back up to the top to make sure everything installed correctly.

9. To launch double click the Launch_YuE2.bat & it will automatically open in your default Internet Browser.

---


### If this worked for you, Please give it a Star ⭐. Thank you.

---

## Thanks to:
DeepBeepMeep for models, some YuE 2 code & MMGP for the GPU Poor. [Hugging Face](https://huggingface.co/DeepBeepMeep) [Github](https://github.com/deepbeepmeep)

---

## License

| Use | Terms |
| --- | --- |
| **Personal users, content creators, and musicians** | Free to use YuE2 and monetize generated outputs, with **no fees or royalties payable to us**. |
| **Academic research and education** | Free for **non-commercial use**. |
| **Commercial use by companies** | [Contact us](#contact) to discuss a commercial license for the model weights. |

We strongly encourage crediting **YuE2** or using **#YuE2** when sharing generated work; attribution is optional.

**Responsible use.** The additional creator permission prohibits illegal, harmful, deceptive, or unethical use. YuE2 is provided **as is, without warranties**. Users are responsible for their inputs, outputs, and use; liability limits are set out in the [full terms](MODEL_LICENSE).

**Code, agent skill, and documentation:** [Apache 2.0](LICENSE). **Model weights:** [CC BY-NC 4.0 with additional creator permission](MODEL_LICENSE).

*Copyright (c) 2026 the YuE2 authors. [Third-party components](THIRD_PARTY_NOTICES.md) and earlier releases retain their respective licenses.*

## Citation

Please cite the [YuE2 paper](https://arxiv.org/abs/2609.33757) when using YuE2, MERT2, or WildSongBench:

```bibtex
@article{yuan2026yue2,
  title = {{YuE2}: Unifying Symbolic and Audio Music Generation at Frontier Quality},
  author = {Yuan, Ruibin and Pan, Jiahao and Jiang, Junyan and Wu, Zhiyue and Zhou, Ziya and Sun, Jiankai and Li, Yizhi and Zhang, Ge and Gu, Yicheng and Tian, Zeyue and Dai, Junyu and Lin, Hanfeng and Li, Kai and Wu, Shangda and Liu, Xuanjie and Wang, Jiaming and Liu, Zihan and Wang, Yue and Ma, Yinghao and Yin, Hanzhi and Chen, Kangrui and Zhang, Xinyue and Ma, Ziyang and Liao, Mengqi and Zhao, Hejia and Huang, Guowei and Yan, Chao and Ke, Lei and Yu, Jianwei and Liu, Bei and Guo, Joe and Xue, Liumeng and Xia, Gus and Xue, Wei and Guo, Yike},
  journal = {arXiv preprint arXiv:2609.33757},
  year = {2026},
  eprint = {2609.33757},
  archivePrefix = {arXiv},
  primaryClass = {eess.AS},
  url = {https://arxiv.org/abs/2609.33757}
}
```

When using SheetSage2, please cite the [SheetSage2 paper](https://arxiv.org/abs/2610.05336):

```bibtex
@misc{jiang2026sheetsage2,
  title = {{SheetSage2}: Coherent Lead-Sheet Transcription with Synthetic Supervision},
  author = {Jiang, Junyan and Yuan, Ruibin and Pan, Jiahao and Xue, Wei and Guo, Yike and Xia, Gus and LeCun, Yann},
  year = {2026},
  eprint = {2610.05336},
  archivePrefix = {arXiv},
  primaryClass = {cs.SD},
  url = {https://arxiv.org/abs/2610.05336}
}
```

For the original **[MERT](https://arxiv.org/abs/2306.00107)** and **[YuE](https://arxiv.org/abs/2503.08638)** models, please cite:

```bibtex
@article{li2023mert,
  title = {{MERT}: Acoustic Music Understanding Model with Large-Scale Self-supervised Training},
  author = {Li, Yizhi and Yuan, Ruibin and Zhang, Ge and Ma, Yinghao and Chen, Xingran and Yin, Hanzhi and Xiao, Chenghao and Lin, Chenghua and Ragni, Anton and Benetos, Emmanouil and Gyenge, Norbert and Dannenberg, Roger and Liu, Ruibo and Chen, Wenhu and Xia, Gus and Shi, Yemin and Huang, Wenhao and Wang, Zili and Guo, Yike and Fu, Jie},
  journal = {arXiv preprint arXiv:2306.00107},
  year = {2023},
  eprint = {2306.00107},
  archivePrefix = {arXiv},
  url = {https://arxiv.org/abs/2306.00107}
}

@article{yuan2025yue,
  title = {{YuE}: Scaling Open Foundation Models for Long-Form Music Generation},
  author = {Yuan, Ruibin and Lin, Hanfeng and Guo, Shuyue and Zhang, Ge and Pan, Jiahao and Zang, Yongyi and Liu, Haohe and Liang, Yiming and Ma, Wenye and Du, Xingjian and Du, Xinrun and Ye, Zhen and Zheng, Tianyu and Jiang, Zhengxuan and Ma, Yinghao and Liu, Minghao and Tian, Zeyue and Zhou, Ziya and Xue, Liumeng and Qu, Xingwei and Li, Yizhi and Wu, Shangda and Shen, Tianhao and Ma, Ziyang and Zhan, Jun and Wang, Chunhui and Wang, Yatian and Chi, Xiaowei and Zhang, Xinyue and Yang, Zhenzhu and Wang, Xiangzhou and Liu, Shansong and Mei, Lingrui and Li, Peng and Wang, Junjie and Yu, Jianwei and Pang, Guojian and Li, Xu and Wang, Zihao and Zhou, Xiaohuan and Yu, Lijun and Benetos, Emmanouil and Chen, Yong and Lin, Chenghua and Chen, Xie and Xia, Gus and Zhang, Zhaoxiang and Zhang, Chao and Chen, Wenhu and Zhou, Xinyu and Qiu, Xipeng and Dannenberg, Roger and Liu, Jiaheng and Yang, Jian and Huang, Wenhao and Xue, Wei and Tan, Xu and Guo, Yike},
  journal = {arXiv preprint arXiv:2503.08638},
  year = {2025},
  eprint = {2503.08638},
  archivePrefix = {arXiv},
  url = {https://arxiv.org/abs/2503.08638}
}
```

## Contact

<table>
  <tr>
    <td align="center" width="50%">
      <strong><img src="assets/wechat.svg" width="20" height="20" alt="" />&nbsp;WeChat</strong><br>
      <sub>Chinese-speaking users</sub>
    </td>
    <td align="center" width="50%">
      <a href="https://discord.gg/ssAyWMnMzu"><strong><img src="assets/discord.svg" width="20" height="20" alt="" />&nbsp;Join&nbsp;Discord</strong></a><br>
      <sub>Global users</sub>
    </td>
  </tr>
  <tr>
    <td align="center" colspan="2">
      <details>
        <summary><strong>Show WeChat QR code</strong></summary>
        <br>
        <a href="assets/wechat-yue2-group.png">
          <img src="assets/wechat-yue2-group.png" alt="YuE2 WeChat group QR code" width="240" />
        </a><br>
        <sub>Click to enlarge<br>Valid until Oct 11, 2026</sub>
      </details>
    </td>
  </tr>
</table>

- **Licensing inquiries:** [lauryliuyang@hkgai.org](mailto:lauryliuyang@hkgai.org)
- **Data partnerships:** [gezhang@umich.edu](mailto:gezhang@umich.edu)
- **Academic collaboration:** [ryuanab@connect.ust.hk](mailto:ryuanab@connect.ust.hk)
