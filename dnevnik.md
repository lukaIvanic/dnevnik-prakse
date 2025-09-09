### **Dnevnik stručne prakse**

**Student:** LUKA IVANIĆ  
**Tvrtka:** Huawei Warsaw Research Center  
**Mentor:** (Ime mentora)  
**Sveučilište:** Sveučilište u Rijeci, Tehnički fakultet  
**Studij:** Diplomski studij računarstva  
**Razdoblje obavljanja prakse:** 16.06.2025. - 11.07.2025.

---

#### **Tjedan 1: Optimizacija projekta i razvoj algoritamskog layouta**

| Datum | Opis posla |
| :--- | :--- |
| **16.06.2025.** | Upoznavanje s radnom okolinom, alatima (IDE, Codehub) i serverima. Početak analize i refaktoriranja projekta "Paper2Poster". |
| **17.06.2025.** | Implementacija "per-step caching" mehanizma. Zamjena postojećeg LLM sustava za generiranje layouta s novim, algoritamskim pristupom. |
| **18.06.2025.** | Istraživanje genetskih algoritama (DEAP library). Zamjena manualnih algoritama s evolucijskim genetskim algoritmima za optimizaciju layouta. |
| **19.06.2025.** | Optimizacija brzine "docling" biblioteke. Razvoj nove biblioteke za piksel-precizno računanje i generiranje layouta u PPTX formatu. |
| **20.06.2025.** | Prilagodba i omogućavanje "docling" biblioteke za rad na NPU (Neural Processing Units), postizanje 10x ubrzanja izvršavanja. |

---

#### **Tjedan 2: Triton Code Generation i NPU infrastruktura**

| Datum | Opis posla |
| :--- | :--- |
| **23.06.2025.** | Detaljno profiliranje performansi (torch profiler, cProfiler) radi identifikacije NPU komunikacijskih uskih grla. Početak literature reviewa za Triton. |
| **24.06.2025.** | Postavljanje razvojnog okruženja za Triton. Razvoj, testiranje i proučavanje jednostavnih Triton kernela za NPU. |
| **25.06.2025.** | Prilagodba TritonBench alata za rad na NPU-ovima. Razvoj skripte za custom Triton kompajliranje i "prompting" za TritonAscend kod. |
| **26.06.2025.** | Implementacija metode "AI CUDA Engineer" na TritonAscend koristeći Deepseek V3 model, s ciljem replikacije rezultata za NPU arhitekturu. |
| **27.06.2025.** | Razvoj automatiziranog "pipeline-a" za re-prompting, generiranje koda i izvršavanje. Implementacija "torchair" optimizacija. |

---

#### **Tjedan 3: Veliki jezični modeli (LLM) i multimodalni benchmarking**

| Datum | Opis posla |
| :--- | :--- |
| **30.06.2025.** | Nadogradnja "Paper2Poster" alata s automatskim pretraživanjem ArXiv-a i paralelizacijom obrade. Poboljšanje CLI sučelja. |
| **01.07.2025.** | Implementacija VLM i LLM benchmarka kao priprema za eksperimente s optimizacijom i kvantizacijom modela. |
| **02.07.2025.** | Pokretanje Qwen2.5-VL 7B modela na NPU-ovima. Razvoj novog multimodalnog benchmark sučelja, uključujući MMMU-Pro. |
| **03.07.2025.** | Evaluacija Qwen modela na razvijenom benchmarku i validacija s postojećim rezultatima. Provođenje eksperimenata s kvantizacijom. |
| **04.07.2025.** | Rad na optimizaciji "docling" procesa za drugi projekt, smanjenje vremena obrade s 50 na 2 minute. |

---

#### **Tjedan 4: Integracija modela i finalizacija projekata**

| Datum | Opis posla |
| :--- | :--- |
| **07.07.2025.** | Integracija MinerU 2.0 modela za NPU. Prilagodba izvornog koda Qwen2 VL modela za integraciju na 310P NPU čipove. |
| **08.07.2025.** | Benchmarking brzine i performansi MinerU modela na 910B i 310P NPU-ovima. Rješavanje problema sa "memory loading hang" na 310P. |
| **09.07.2025.** | Portanje postojećeg open-source multimodalnog benchmarka (MultiModal-Embedding/Baseline-Experiments) na NPU infrastrukturu. |
| **10.07.2025.** | Benchmarking 3 različita modela s 3 benchmarka na internim serverima tvrtke. Provođenje literature reviewa za Multimodal RAG. |
| **11.07.2025.** | Finalizacija tehničke dokumentacije za sve provedene zadatke, uključujući Paper2Poster, Triton pipeline i rezultate benchmarkinga. Prezentacija rezultata timu. |

---
