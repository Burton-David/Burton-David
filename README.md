### David Burton

AI / agent engineer. I build LLM agents and tooling for work where being *confidently
wrong* is expensive — clinical research and quantitative finance — so my projects lean
hard on reproducibility, evaluation, and knowing the limits of an answer.

Background: peer-reviewed clinical-data analysis, live options-trading systems, and
production ML for healthcare, biotech, and finance clients. Now focused on agents you
can actually trust to deploy.

📍 New York, NY / San Diego, CA (bicoastal) · 🌐 [databurton.com](https://databurton.com)

---

#### Agents & MCP

- **[ResearchAssistantMCP](https://github.com/Burton-David/ResearchAssistantMCP)** —
  an MCP server for citation-finding research: extracts the claims in a draft, searches
  arXiv / Semantic Scholar / PubMed / OpenAlex, scores source quality, and explains each
  recommendation. Usable from any MCP client.
- **[ResearchAssistantAgent](https://github.com/Burton-David/ResearchAssistantAgent)** —
  a chain of LLM agents that finds relevant papers, returns AMA-format citations, and
  ranks sources by a customizable rigor rubric.

#### LLM & data tooling

- **[csvtriage](https://github.com/Burton-David/csvtriage)** — load messy CSVs
  (bad encodings, ragged rows, junk), recover what's parseable, and report every
  decision instead of failing silently.
- **[oalex](https://github.com/Burton-David/oalex)** — a typed, async, rate-limited
  Python client for the OpenAlex scholarly-works API.
- **[scicite-claims](https://github.com/Burton-David/scicite-claims)** — extract
  citation-worthy claim spans from scientific text with spaCy + linguistic patterns.

#### ML systems

- **[Recommender-Systems](https://github.com/Burton-David/Recommender-Systems)** —
  classic and modern recommender algorithms with a clean, typed, tested API.

---

*Currently building toward agents that are right — and honest about when they aren't.*
