# Title

**Scene Understanding-oriented Semantic Communications: An Open Joint Source-Channel Coding Scheme**
-------
# Video demo
https://github.com/user-attachments/assets/25a25a4b-6309-4409-b728-e7a0ab6189ee
# Abstrast
As communication systems evolve beyond simple symbol transmission, 6G networks prioritize semantic communication to improve robustness and reduce redundancy across text, speech, and images.However, existing approaches rely on static coding strategies and task-specific knowledge bases, limiting adaptability in dynamic environments.Traditional semantic communication for scene understanding encodes entire images without extracting meaningful representations,leading to inefficiencies and inconsistencies. Furthermore,sender-receiver knowledge misalignment due to localized knowledge bases hinders accurate semantic interpretation.To overcome these challenges, we introduce Open Joint Source-Channel Coding (OpenJSCC)—a novel framework 
that integrates structured semantic representations with task aware knowledge base construction. Unlike conventional methods that focus on low-level feature encoding, Open-JSCC leverages large language models (LLMs) and scene graph generation to capture object relationships and contex-tual semantics, enhancing visual-textual reasoning in tasks like visual question answering (VQA). Experimental results demonstrate that OpenJSCC enhances both transmission efficiency and semantic accuracy, outperforming existing communication methods in VQA tasks across simulated and real-world environments.
# Introduction
<img src="https://github.com/user-attachments/assets/74b2c32f-b95f-4b2b-aa53-8f4a85514dd5" width="1024px">

**Key Problems:**     
              (1):How to achieve multimodal semantic fusion that enhances interpretable visual-textual reasoning while maintaining transmission efficiency?     
              (2):How to design dynamic channel coding mechanisms to eliminate dependency on static knowledge bases?   
              (3):How to balance semantic compression and transmission robustness through joint optimization in complex environments?     
-------
# Framework
<img src="https://github.com/user-attachments/assets/bf28610e-4f8d-4766-b496-5a35288423f7" width="1024px">

**The OpenJSCC Framework for scene understanding-oriented semantic communication with the semantic-channel encoding/decoding modules, the physical channel, the VQA-oriented RAG-LLM semantic decoding module.**
-------
# Hardware Platform
<img src="https://github.com/user-attachments/assets/e65ad5e7-5ffb-4756-96e9-7422ff4459c1" width="1024px">

**The architecture of the scene understanding orient semantic communication prototype platform.**
-------
# Experiment
<img src="https://github.com/user-attachments/assets/ae5ff906-df19-4d4a-abae-629c9c235e0d" width="1024px">

**Comparison of communication performance between a traditional communication method (JPEG+LDPC) and our OpenJSCC scheme in real-world scenarios**  
-------

<img src="https://github.com/user-attachments/assets/af6067a3-a90b-4512-8e96-ba71ebfdbbbc" width="1024px">

**Performance comparison when different models are used as VQA-LLM.**
-------

<img src="https://github.com/user-attachments/assets/2d55d8f0-e55d-40af-95dc-7e9de432954d" width="1024px">

**Average number of symbols transmitted by each method.**
-------
<img src="https://github.com/user-attachments/assets/58cf2cac-acd4-45bf-8024-e8ad83149d03" width="1024px">

**Comparison of our method and baselines for VQA on an image from the AUG dataset.**
-------


