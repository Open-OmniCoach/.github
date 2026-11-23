<div align="center">

<img src="https://raw.githubusercontent.com/Open-OmniCoach/omnicoach/main/assets/logo.png" alt="Open-OmniCoach Logo" width="128"/>

# Open-OmniCoach

**Evidence-Enhanced Trajectory Learning for Omni Video Agents**

<p>
  <a href="https://github.com/Open-OmniCoach/omnicoach"><img src="https://img.shields.io/badge/GitHub-omnicoach-181717?logo=github" alt="Code"></a>
  <a href="https://github.com/Open-OmniCoach/video-agent-evalkit"><img src="https://img.shields.io/badge/Eval-video--agent--evalkit-0F766E" alt="EvalKit"></a>
  <a href="https://huggingface.co/collections/Open-OmniCoach/open-omnicoach-6b02b581ecac90284c6009d9"><img src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Open--OmniCoach-FFD21E" alt="HF Collection"></a>
  <a href="https://open-omnicoach.github.io"><img src="https://img.shields.io/badge/Project-Page-2E5D66?logo=googlechrome&logoColor=white" alt="Project Page"></a>
</p>

</div>

**Open-OmniCoach** develops evidence-seeking omni-modal video agents trained with multi-span active perception, reflection recovery trajectories (**OmniCoach-240K**), and Step-Level Evidence-Guided Policy Optimization (**SEPO**).

### Repositories

| Repository | Description |
| --- | --- |
| [**Open-OmniCoach/omnicoach**](https://github.com/Open-OmniCoach/omnicoach) | Main repository: offline trace-collection harness (`harness/`), multi-turn Agent SFT (`sft/`), Qwen3-Omni RL with Turn-Level GSPO on `THUDM/slime` (`rl/`), and evaluation submodule (`evalkit/`). |
| [**Open-OmniCoach/video-agent-evalkit**](https://github.com/Open-OmniCoach/video-agent-evalkit) | Unified multimodal & video agent benchmark evaluation toolkit (`evalkit/` submodule, [`omnicoach`](https://github.com/Open-OmniCoach/video-agent-evalkit/tree/omnicoach) integration branch). |
| [**Open-OmniCoach/open-omnicoach.github.io**](https://github.com/Open-OmniCoach/open-omnicoach.github.io) | Interactive project page and trajectory explorer. |

### Hugging Face Artifacts

- **Collection**: [Open-OmniCoach Collection](https://huggingface.co/collections/Open-OmniCoach/open-omnicoach-6b02b581ecac90284c6009d9)
- **Models**: [Open-OmniAgent-30B-A3B](https://huggingface.co/Open-OmniCoach/Open-OmniAgent-30B-A3B) · [Open-OmniAgent-7B](https://huggingface.co/Open-OmniCoach/Open-OmniAgent-7B)
- **Dataset**: [OmniCoach-240K](https://huggingface.co/datasets/Open-OmniCoach/OmniCoach-240K)
