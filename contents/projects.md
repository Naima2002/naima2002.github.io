
**Streaming GNN Inference**  
- Built one of the first real-time GNN inference pipelines on Apache Flink, integrating RocksDB, Kafka, and TorchServe; sustained 2,100+ queries/sec with <300 ms latency and 3–4× throughput gains over DGL/PyG.  
- Currently extending this into a disaggregated streaming system with a declarative API for event-driven GNN pipelines (fraud detection, recommendations, product classification).  

**FPGA-based In-situ GNN Sampling (DaMoN ’24 – Best Paper Award)**  
- Designed FPGA kernels for neighborhood sampling directly on SmartSSDs, achieving up to 4.26× faster sampling and cutting PCIe transfer by 29 GB/epoch.  
- Published at DaMoN ’24 with Best Paper recognition.  

**Distributed Consensus with OmniPaxos**  
- Implemented the OmniPaxos consensus protocol in Go and built a sharded key-value store on top.  
- Validated correctness and scalability with <10 ms latency and 175 ops/sec under concurrent load.  

**Data Carving for Scientific Reproducibility (SRI International)**  
- Worked with Dr. Ashish Gehani on container debloating for data-intensive applications by carving HDF5 files through system call and I/O library interposition, storing only accessed subsets while maintaining reproducibility.
- Reduced container storage by up to 97%, validated on NASA MODIS and synthetic HDF5 benchmarks.  

**JavaScript Unbundling (UC Davis & Virginia Tech)**  
- Detected bundled JavaScript that mixes tracking with essential functionality, where existing blockers fail.  
- Used PageGraphs and execution-context features to classify scripts, achieving 98% accuracy without breaking site functionality.  

**Data Voids in Search Engines (LUMS & SPARTA Lab, Univ. of Iowa)**  
- Investigated how missing information in search engines can be exploited to promote manipulative agendas.  
- Built scrapers across 4chan, Reddit, and Google Search; applied NLP to detect and analyze “data voids.”  

**Student–Tutor Platform (LUMS, Software Engineering)**  
- Built a website to connect students and tutors efficiently, using Node.js (backend), EJS (frontend), and Firestore.  
- Deployed on Heroku as part of a Software Engineering capstone project.  

**AI for Ecosystem Services (Omdena)**  
- Collaborated with 20+ contributors to build an AI system that identifies ecosystem services for endangered species.  
- Developed pipelines for automating data collection and valuation for socio-economic analysis.  

**Hindi Speech Recognition Challenge**  
- Trained Wav2Vec and XLSR models for Hindi ASR, applying Transformers and Conformers for sequence modeling.  
- Achieved 85% accuracy, outperforming baseline models.  

**Other Systems Projects**  
- Created a chat application using socket programming and reliable transfer protocols.  
- Published multiple programming tutorials/articles with illustrated code examples (C++/Python).  


