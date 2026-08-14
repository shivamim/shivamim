<div align="center">

<pre>
██████╗  █████╗  ██████╗ ██████╗ ████████╗
██╔══██╗██╔══██╗██╔════╝ ██╔══██╗╚══██╔══╝
██████╔╝███████║██║  ███╗██████╔╝   ██║
██╔══██╗██╔══██║██║   ██║██╔══██╗   ██║
██║  ██║██║  ██║╚██████╔╝██████╔╝   ██║
╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝ ╚═════╝    ╚═╝
</pre>

<b>declarative &middot; incremental &middot; tested embedding pipelines</b>

<a href="https://pypi.org/project/ragbt/"><img src="https://img.shields.io/pypi/v/ragbt?style=flat-square&color=111&label=pypi"></a>
<a href="https://pypi.org/project/ragbt/"><img src="https://img.shields.io/pypi/pyversions/ragbt?style=flat-square&color=111"></a>
<a href="https://github.com/shivamim/ragbt"><img src="https://img.shields.io/github/license/shivamim/ragbt?style=flat-square&color=111&label=license"></a>

</div>

---

## now

building <a href="https://github.com/shivamim/ragbt"><b>ragbt</b></a> — a dbt-style developer tool for RAG.  
content-hash diffing, retrieval assertions, lineage manifests, pluggable chunkers/embedders, HNSW-backed vector search.

```bash
pip install ragbt
ragbt init my_rag && cd my_rag
ragbt run    # incremental
ragbt test   # retrieval assertions
ragbt ls     # run history
```

stack: python, typer, pydantic, sqlalchemy[asyncio], asyncpg, pgvector, httpx, tenacity

## previously

- shipped <b>Ojas</b> (Next.js + Supabase) — patient management system in production
- rebuilt a live encryption-layer crash path (base64 plaintext inside AES-GCM column) without downtime
- shipped analytics infra across 340+ stores (revenue, EBITDA, wastage) serving 10k+ users
- implemented dual-head GPT-style Transformer from scratch with entropy-based uncertainty estimation

## systems

<table>
<tr>
<td width="50%" valign="top">

<b>languages & runtimes</b><br>
<img src="https://skillicons.dev/icons?i=python,ts,js&theme=dark" /><br>

<b>backend & data</b><br>
<img src="https://skillicons.dev/icons?i=fastapi,postgres,redis,docker,aws&theme=dark" /><br>

<b>frontend</b><br>
<img src="https://skillicons.dev/icons?i=react,nextjs,tailwind&theme=dark" /><br>

</td>
<td width="50%" valign="top">

<b>ai & ml</b><br>
PyTorch, Pandas, NumPy, scikit-learn, LangGraph, LangChain, Voyage AI, OpenAI, Groq<br><br>

<b>vector & retrieval</b><br>
pgvector, ChromaDB, BM25, RRF, HNSW<br><br>

<b>tools</b><br>
GitHub Actions, dbt, SQLAlchemy 2.0, Prisma, Supabase, BigQuery<br><br>

</td>
</tr>
</table>

## repositories

| project | description | stack |
|---|---|---|
| <a href="https://github.com/shivamim/ragbt"><b>ragbt</b></a> | dbt for RAG — incremental embedding pipelines with tests & lineage | python, typer, pgvector, pydantic |
| <a href="https://github.com/shivamim/SentinelIQ"><b>SentinelIQ</b></a> | autonomous SOC investigation platform with LangGraph agents & Neo4j threat graph | langgraph, neo4j, pgvector, redis |
| <a href="https://github.com/shivamim/Finance_AgenticAI"><b>Finance AgenticAI</b></a> | multi-agent stock market intelligence with live web retrieval | multi-agent, groq, openai |
| <a href="https://github.com/shivamim/Ojas-V2"><b>Ojas</b></a> | production patient management system | next.js, supabase, postgres |
| <a href="https://github.com/shivamim/KitchenIQ"><b>KitchenIQ</b></a> | 340+ store analytics (revenue, EBITDA, wastage) | power bi, python, sql |
| <a href="https://github.com/shivamim/self-diagnosing-gpt"><b>self-diagnosing-gpt</b></a> | dual-head GPT from scratch with uncertainty estimation | pytorch, transformers |

## stats

<div align="center">
<img height="150" src="https://github-readme-stats.vercel.app/api?username=shivamim&show_icons=true&theme=dark&hide_border=true&count_private=true&include_all_commits=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9"/>
<img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=shivamim&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&text_color=c9d1d9"/>
</div>

## connect

<a href="https://linkedin.com/in/shivam-s-shukla">linkedin</a> &middot;
<a href="mailto:shivam.shukla1688@gmail.com">email</a> &middot;
<a href="https://twitter.com/shivams001">twitter</a>
