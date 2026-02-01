# GUI Agents Evaluation Suite Collection

This repository collects information about HuggingFace's GUI Agents Evaluation Suite - **ScreenSuite**.

## About ScreenSuite

ScreenSuite is HuggingFace's comprehensive benchmarking suite for evaluating Graphical User Interface (GUI) agents across areas of ability: perception, single-step and multi-step agentic behaviour.

**Official Repository:** https://github.com/huggingface/screensuite

## Desktop Environment-Related Grounding Benchmarks

Based on the official ScreenSuite benchmarking documentation, the desktop environment-related Grounding benchmarks and their HuggingFace dataset links are:

- OSWorld (Ubuntu): https://huggingface.co/datasets/xlangai/ubuntu_osworld
- OSWorld (Windows): https://huggingface.co/datasets/xlangai/windows_osworld
- OSWorld (macOS): https://huggingface.co/datasets/xlangai/macos_osworld
- OSWorld-G (Grounding extension): https://huggingface.co/datasets/MMInstruction/OSWorld-G
- OSWorld Screenshots: https://huggingface.co/datasets/andersonbcdefg/osworld_screenshots
- OSWorld Icons: https://huggingface.co/datasets/andersonbcdefg/osworld-icons
- OSWorld Verified Trajectories: https://huggingface.co/datasets/xlangai/ubuntu_osworld_verified_trajs
- GELATO OSWorld Agent Trajectories: https://huggingface.co/datasets/mlfoundations/gelato-osworld-agent-trajectories

## Note

According to the official ScreenSuite Grounding/Perception Benchmarks table, the listed benchmarks (ScreenSpot, ScreenSpot v2, Visual-WebBench, etc.) are focused on Web and Mobile platforms. OSWorld is the primary desktop environment benchmark included in ScreenSuite under the "Multi-step - Online Agent Benchmarks" category, with various grounding-related datasets available in the HuggingFace Hub.

## References

- ScreenSuite GitHub: https://github.com/huggingface/screensuite
- OSWorld GitHub: https://github.com/xlang-ai/OSWorld
- OSWorld Paper: https://arxiv.org/abs/2404.07972
- OSWorld Website: https://os-world.github.io/
