# Priority-Driven Hierarchical Multi-Agent Systems with Fine-Tuned LLMs

Project page for our paper published in *Applied Sciences* (MDPI):

> A. Tudela, Ó. Pons, J. Galeas, J. P. Bandera and A. Bandera, "Priority-Driven Hierarchical Multi-Agent Systems with Fine-Tuned LLMs," *Applied Sciences*, vol. 16, no. 16, p. 8250, 2026. https://doi.org/10.3390/app16168250

- **Paper:** https://www.mdpi.com/2076-3417/16/16/8250
- **Code:** https://github.com/grupo-avispa/hierarchical_multiagent_langgraph
- **Video:** https://www.youtube.com/watch?v=w20pUtpIV34

## About

We propose a hierarchical multi-agent architecture for robot deliberation that combines LLM-based planning with structured, priority-driven execution inside ROS 2. A supervisor agent decomposes natural-language instructions into prioritised subtasks, delegated to Single-Purpose Agents orchestrated via LangGraph and coordinated through a priority-aware scheduler. Behaviour Trees are exposed as callable tools through the Model Context Protocol (MCP), and lightweight (~0.6B) LLMs are LoRA fine-tuned for the supervisor and SPA roles to enable efficient, low-latency inference on edge hardware. The architecture is evaluated in a real Ambient Assisted Living deployment.

## Running locally

This is a static site (HTML/CSS/JS, no build step). Serve it with any static file server, e.g.:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000`.

## Citation

```bibtex
@article{Tudela2026Priority,
  title={Priority-Driven Hierarchical Multi-Agent Systems with Fine-Tuned LLMs},
  author={Tudela, Alberto and Pons, {\'O}scar and Galeas, Jos{\'e} and Bandera, Juan Pedro and Bandera, Antonio},
  journal={Applied Sciences},
  volume={16},
  number={16},
  pages={8250},
  year={2026},
  publisher={MDPI},
  doi={10.3390/app16168250},
  url={https://www.mdpi.com/2076-3417/16/16/8250}
}
```

## Acknowledgments

This page was built with the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), adopted from the [Nerfies](https://nerfies.github.io/) project page. The website source is licensed under a [Creative Commons Attribution-ShareAlike 4.0 International License](http://creativecommons.org/licenses/by-sa/4.0/).
