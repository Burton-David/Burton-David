### David Burton

AI / agent engineer. I build LLM agents and tooling for work where being *confidently
wrong* is expensive: clinical research and quantitative finance. So my projects lean
hard on reproducibility, evaluation, and knowing the limits of an answer.

Background: peer-reviewed clinical-data analysis, live options-trading systems, and
production ML for healthcare, biotech, and finance clients. Now focused on agents you
can actually trust to deploy.

New York, NY / San Diego, CA (bicoastal) · [databurton.com](https://databurton.com)

---

#### Agents & MCP

- **[ResearchAssistantMCP](https://github.com/Burton-David/ResearchAssistantMCP)**:
  an MCP server for citation-finding research. It extracts the claims in a draft,
  searches arXiv, Semantic Scholar, PubMed and OpenAlex, scores source quality, and
  explains each recommendation. Usable from any MCP client.
- **[statskeptic](https://github.com/Burton-David/statskeptic)**: a data-analysis
  agent that red-teams its own conclusions and reports what the data can't support.
  `pip install statskeptic`

#### LLM & data tooling

- **[csvtriage](https://github.com/Burton-David/csvtriage)**: load messy CSVs
  (bad encodings, ragged rows, junk), recover what's parseable, and report every
  decision instead of failing silently.
- **[oalex](https://github.com/Burton-David/oalex)**: a typed async client for the
  OpenAlex scholarly-works API, with API-key auth, disk caching, and credit-aware
  retries. `pip install oalex`
- **[scicite-claims](https://github.com/Burton-David/scicite-claims)**: extract
  citation-worthy claim spans from scientific text with spaCy and linguistic patterns.
- **[lead-gen-pipeline](https://github.com/Burton-David/lead-gen-pipeline)**: scrape
  Chamber of Commerce member directories into structured business records, with a
  crawler that identifies itself and honors robots.txt.

#### ML systems & visualization

- **[Recommender-Systems](https://github.com/Burton-David/Recommender-Systems)**:
  classic and modern recommender algorithms behind one typed, tested API, benchmarked
  on MovieLens, with Rust kernels.
- **[cinestyle](https://github.com/Burton-David/cinematic-matplotlib)**: film-inspired
  matplotlib themes with a colorblind audit that repairs the palettes it flags.
  `pip install cinestyle`
- **[echo-translate](https://github.com/Burton-David/echo-translate)**: hear English
  spoken in another language in your own cloned voice, offline, for pronunciation
  practice.

---

*Currently building toward agents that are right, and honest about when they aren't.*
