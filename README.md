<div align="center">

<h1>WorldExam</h1>

<h3>Benchmarking World Models from Apparent Appearance to Inherent Reactivity</h3>

<p>
  <a href="https://worldexam.github.io/"><img src="https://img.shields.io/badge/Project_Page-WorldExam-2f80ed?style=for-the-badge&amp;logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1MTIgNTEyIj48cGF0aCBmaWxsPSIjZmZmIiBkPSJNMzUxLjkgMjgwbC0xOTAuOSAwYzIuOSA2NC41IDE3LjIgMTIzLjkgMzcuNSAxNjcuNCAxMS40IDI0LjUgMjMuNyA0MS44IDM1LjEgNTIuNCAxMS4yIDEwLjUgMTguOSAxMi4yIDIyLjkgMTIuMnMxMS43LTEuNyAyMi45LTEyLjJjMTEuNC0xMC42IDIzLjctMjggMzUuMS01Mi40IDIwLjMtNDMuNSAzNC42LTEwMi45IDM3LjUtMTY3LjR6TTE2MC45IDIzMmwxOTAuOSAwQzM0OSAxNjcuNSAzMzQuNyAxMDguMSAzMTQuNCA2NC42IDMwMyA0MC4yIDI5MC43IDIyLjggMjc5LjMgMTIuMiAyNjguMSAxLjcgMjYwLjQgMCAyNTYuNCAwcy0xMS43IDEuNy0yMi45IDEyLjJjLTExLjQgMTAuNi0yMy43IDI4LTM1LjEgNTIuNC0yMC4zIDQzLjUtMzQuNiAxMDIuOS0zNy41IDE2Ny40em0tNDggMEMxMTYuNCAxNDYuNCAxMzguNSA2Ni45IDE3MC44IDE0LjcgNzguNyA0Ny4zIDEwLjkgMTMxLjIgMS41IDIzMmwxMTEuNCAwek0xLjUgMjgwYzkuNCAxMDAuOCA3Ny4yIDE4NC43IDE2OS4zIDIxNy4zLTMyLjMtNTIuMi01NC40LTEzMS43LTU3LjktMjE3LjNMMS41IDI4MHptMzk4LjQgMGMtMy41IDg1LjYtMjUuNiAxNjUuMS01Ny45IDIxNy4zIDkyLjEtMzIuNyAxNTkuOS0xMTYuNSAxNjkuMy0yMTcuM2wtMTExLjQgMHptMTExLjQtNDhDNTAxLjkgMTMxLjIgNDM0LjEgNDcuMyAzNDIgMTQuNyAzNzQuMyA2Ni45IDM5Ni40IDE0Ni40IDM5OS45IDIzMmwxMTEuNCAweiIvPjwvc3ZnPg%3D%3D" alt="Project Page"></a>
  <img src="https://img.shields.io/badge/arXiv-Coming_Soon-b31b1b?style=for-the-badge&amp;logo=arxiv&amp;logoColor=white" alt="arXiv Coming Soon">
  <a href="https://worldexam.github.io/WorldExam.pdf"><img src="https://img.shields.io/badge/Paper-PDF-e5322d?style=for-the-badge&amp;logo=data:image/svg%2Bxml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCA1NzYgNTEyIj48cGF0aCBmaWxsPSIjZmZmIiBkPSJNMjA4IDQ4TDk2IDQ4Yy04LjggMC0xNiA3LjItMTYgMTZsMCAzODRjMCA4LjggNy4yIDE2IDE2IDE2bDgwIDAgMCA0OC04MCAwYy0zNS4zIDAtNjQtMjguNy02NC02NEwzMiA2NEMzMiAyOC43IDYwLjcgMCA5NiAwTDIyOS41IDBjMTcgMCAzMy4zIDYuNyA0NS4zIDE4LjdMMzk3LjMgMTQxLjNjMTIgMTIgMTguNyAyOC4zIDE4LjcgNDUuM2wwIDE0OS41LTQ4IDAgMC0xMjgtODggMGMtMzkuOCAwLTcyLTMyLjItNzItNzJsMC04OHpNMzQ4LjEgMTYwTDI1NiA2Ny45IDI1NiAxMzZjMCAxMy4zIDEwLjcgMjQgMjQgMjRsNjguMSAwek0yNDAgMzgwbDMyIDBjMzMuMSAwIDYwIDI2LjkgNjAgNjBzLTI2LjkgNjAtNjAgNjBsLTEyIDAgMCAyOGMwIDExLTkgMjAtMjAgMjBzLTIwLTktMjAtMjBsMC0xMjhjMC0xMSA5LTIwIDIwLTIwem0zMiA4MGMxMSAwIDIwLTkgMjAtMjBzLTktMjAtMjAtMjBsLTEyIDAgMCA0MCAxMiAwem05Ni04MGwzMiAwYzI4LjcgMCA1MiAyMy4zIDUyIDUybDAgNjRjMCAyOC43LTIzLjMgNTItNTIgNTJsLTMyIDBjLTExIDAtMjAtOS0yMC0yMGwwLTEyOGMwLTExIDktMjAgMjAtMjB6bTMyIDEyOGM2LjYgMCAxMi01LjQgMTItMTJsMC02NGMwLTYuNi01LjQtMTItMTItMTJsLTEyIDAgMCA4OCAxMiAwem03Ni0xMDhjMC0xMSA5LTIwIDIwLTIwbDQ4IDBjMTEgMCAyMCA5IDIwIDIwcy05IDIwLTIwIDIwbC0yOCAwIDAgMjQgMjggMGMxMSAwIDIwIDkgMjAgMjBzLTkgMjAtMjAgMjBsLTI4IDAgMCA0NGMwIDExLTkgMjAtMjAgMjBzLTIwLTktMjAtMjBsMC0xMjh6Ii8%2BPC9zdmc%2B" alt="Download PDF"></a>
  <img src="https://img.shields.io/badge/Test_Case-Coming_Soon-f3b344?style=for-the-badge&amp;logo=huggingface&amp;logoColor=white" alt="Dataset Coming Soon">
</p>

<p>
  <strong>Yuxue Yang<sup>1,*,&dagger;</sup>, Shuyao Shang<sup>1,*</sup>, Jiahe Wang<sup>1</sup>, Zitong Zhou<sup>1</sup>, Liang Tan<sup>1</sup></strong><br>
  <strong>Junhan Zeng<sup>1</sup>, Ruizhi Li<sup>1</sup>, Junyan Li<sup>1</sup>, Yu Liu<sup>4</sup>, Xiao Yang<sup>5</sup>, Yong Li<sup>5</sup></strong><br>
  <strong>Jun Zhu<sup>5</sup>, Hongsheng Li<sup>2,3</sup>, Tieniu Tan<sup>1</sup>, Lue Fan<sup>1,&dagger;,&ensp;✉️</sup>, Zhaoxiang Zhang<sup>1,&ensp;✉️</sup></strong>
</p>

<p>
  <sup>1</sup>CASIA &nbsp;&nbsp; <sup>2</sup>SLAI &nbsp;&nbsp; <sup>3</sup>CUHK &nbsp;&nbsp; <sup>4</sup>AMAP &nbsp;&nbsp; <sup>5</sup>THU<br>
  <sup>*</sup>Equal Contribution &nbsp;&nbsp; <sup>&dagger;</sup>Project Leaders &nbsp;&nbsp; <sup>✉️</sup>Corresponding Authors
</p>

<br>

<img src="teaser.png" alt="WorldExam overview" width="100%">

<br>

</div>

> [!NOTE]
> **Inherent World Reactivity** is the ability to infer from the scene state how the world should react and to generate plausible consequences not explicitly described in the input.

⭐ If you find **WorldExam** useful or interesting, please consider giving this repository a star and stay tuned for future updates!

## Citation

```bibtex
@article{yang2026worldexam,
  title   = {WorldExam: Benchmarking World Models from Apparent Appearance to Inherent Reactivity},
  author  = {Yang, Yuxue and Shang, Shuyao and Wang, Jiahe and Zhou, Zitong and Tan, Liang and Zeng, Junhan and Li, Ruizhi and Li, Junyan and Liu, Yu and Yang, Xiao and Li, Yong and Zhu, Jun and Li, Hongsheng and Tan, Tieniu and Fan, Lue and Zhang, Zhaoxiang},
  journal = {arXiv preprint},
  year    = {2026}
}
```

The citation entry will be updated with the arXiv identifier after the paper is announced.
