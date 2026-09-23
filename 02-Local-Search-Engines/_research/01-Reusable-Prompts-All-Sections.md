STEP 1 — Reusable prompts for all sections
Course 02 — Local Search Engines
Task source: 00-Research-Outline-Course-02.md

You are free to install software, programs and write codes, research the internet so as to meet our goals.

---

**Section 1: Text Retrieval Foundations — Tokenization and Indexing with Stdlib**

Task: Python-standard-library text pipelines: normalization, tokenization, stop handling, and inverted-index construction over dataset rows with zero dependencies.

Absorbed skills:
- Build tokenizers and inverted indexes with stdlib only
- normalize text correctly
- index dataset rows for instant lookup


---

**Section 2: Ranking Science — TF-IDF to BM25**

Task: Term-frequency statistics through BM25: saturation, length normalization, tuning k1 and b, and why BM25 remains the default for keyword relevance.

Absorbed skills:
- Implement BM25 from scratch
- tune k1 and b per corpus
- explain ranking decisions quantitatively


---

**Section 3: Dataset Pipelines — Rows to Searchable Documents**

Task: Ingesting CSV and JSON rows into searchable documents: field selection, per-field weighting, incremental updates, and persistence without external services.

Absorbed skills:
- Build row-to-document ingest pipelines
- weight fields by importance
- persist and update indexes incrementally


---

**Section 4: Query Understanding — Keywords, Phrases and Operators**

Task: Query parsing for phrases, boolean operators, prefixes, and typo tolerance, plus empty-result recovery through relaxation and suggestion.

Absorbed skills:
- Parse advanced query syntax
- recover gracefully from zero results
- suggest corrections users accept


---

**Section 5: Performance Engineering — Speed Without Dependencies**

Task: Profiling with cProfile, posting-list optimization, caching hot paths, and memory discipline so local search stays instant on modest hardware.

Absorbed skills:
- Profile and optimize retrieval hot paths
- cache judiciously
- hold latency budgets on small machines


---

**Section 6: Relevance Tuning — Measuring and Improving Results**

Task: Building judged query sets, measuring precision at k, diagnosing failure classes, and iterating analyzers and weights against evidence.

Absorbed skills:
- Build judged evaluation sets
- measure precision at k
- tune analyzers from failure evidence


---

**Section 7: Packaging Local Search — Embeddable Zero-Dependency Modules**

Task: Clean embeddable API design, index serialization formats, versioning indexes across releases, and documentation for integrators.

Absorbed skills:
- Ship zero-dependency search modules
- version index formats
- document integration for other developers


---

**Section 8: Capstone — Production Local Search Engine**

Task: Full capstone: BM25 search engine over a real multi-thousand-row dataset, benchmarked for latency and relevance, packaged with tests and docs.

Absorbed skills:
- Deliver a benchmarked local search engine
- evidence latency and relevance
- hand off tested, documented code

