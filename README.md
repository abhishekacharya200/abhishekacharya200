# Abhishek Acharya

**AI engineer in Kathmandu, Nepal.** I build retrieval (RAG) and agent systems, and I measure how well they work.
Open to remote roles.

[Portfolio](https://abhishekacharya200.com.np) · [LinkedIn](https://www.linkedin.com/in/abhishek-acharya-5b187b283/) · [Email](mailto:javascript1415@gmail.com)

---

### What I'm working on

- **AI and Automation Intern at K&A Power:** a document search service over about 50,000 company files, a daily tender tracker for ADB, World Bank and AIIB notices, and invoice matching for 1000+ documents a month.
- **Open source:** fixing bugs in Python and AI projects, currently focused on LiteLLM and PyTorch Lightning.

### Featured projects

| Project | What it is | Proof |
|---|---|---|
| [**Production RAG**](https://github.com/abhishekacharya200/Production__rag) | Document search and QA: hybrid dense and BM25 search in Qdrant, LLM reranking, per document access control, cited answers | nDCG@10 **0.795** on the public BEIR SciFact benchmark (dense only: 0.646, BM25: 0.667) |
| [**Fixgate**](https://github.com/abhishekacharya200/Fixgate) | Agent that reproduces a GitHub issue in a sandbox, writes and checks a fix, and opens a PR only after a person approves the exact patch | Resolved **22 of 31** SWE-bench Verified issues (71%, partial run) at about $0.02 each |
| [**vault2okf**](https://github.com/abhishekacharya200/vault2okf) | Converts Obsidian vaults into Open Knowledge Format bundles for AI agents, then validates and repairs them | Published on [PyPI](https://pypi.org/project/vault2okf/), with a GitHub Action and pre-commit hook |
| [**RAG Gateway**](https://github.com/abhishekacharya200/RAG-Gateway) | Local server that speaks the OpenAI, Anthropic and Gemini APIs, for building and testing RAG apps | Used to run the Production RAG benchmark |

### Open source contributions (merged)

- [redis-py #4444](https://github.com/redis/redis-py/pull/4444): JSON commands treat `path=None` as the root path instead of failing
- [Google Cloud Python, BigQuery #18603](https://github.com/googleapis/google-cloud-python/pull/18603): paging no longer sends `startIndex` together with a page token
- [NVIDIA NeMo Agent Toolkit #2359](https://github.com/NVIDIA/NeMo-Agent-Toolkit/pull/2359): the GitHub issue tool sends label filters in the format the API expects
- [Unsloth #13333](https://github.com/unslothai/unsloth/pull/13333): Studio lists Qwen Image GGUF models as image models instead of chat models
- [CPython #159014](https://github.com/python/cpython/pull/159014) and [#159516](https://github.com/python/cpython/pull/159516): documentation fixes

[All my merged pull requests](https://github.com/search?q=is%3Apr+is%3Amerged+author%3Aabhishekacharya200+-user%3Aabhishekacharya200&type=pullrequests)

### Tools I use

- **AI:** RAG, hybrid search, reranking, LLM evaluation, agents and tool calling, OpenAI, Claude and Gemini APIs, Ollama
- **Search and data:** Qdrant, FAISS, ChromaDB, PostgreSQL, Redis
- **Engineering:** Python, FastAPI, Django REST Framework, TypeScript, Docker, GitHub Actions
