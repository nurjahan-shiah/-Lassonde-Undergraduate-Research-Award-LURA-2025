# -Lassonde-Undergraduate-Research-Award-LURA-2025

## Generative AI for Software Architecture and AIOps
 
This project focuses on automatically using real-time performance data from microservices to build accurate performance models. We aim to improve the accuracy of performance predictions by enriching the performance model with actual data on CPU, memory, and network usage. This supports better capacity planning for microservices-based systems. To collect this data, we monitored the Spring PetClinic microservices using two tools: Prometheus and OpenZipkin. These tools captured metrics such as CPU time per request, memory usage changes, and network traffic under realistic workloads. A key part of our approach involved fine-tuning a large language model (LLM: GPT-3.5 Turbo & GPT-4o) to automatically generate the required files for Palladio Bench, a tool used for system performance analysis. The generated model includes details about the system’s hardware, service behaviours, deployment structure, and user interactions. Based on the collected metrics from PetClinic, the LLM is expected to generate all components of the model, including system architecture, hardware configuration, resource demands, and usage patterns. Our early results show that the generated Palladio model closely matches actual system performance, predicting response times with less than 15% error. It also helps identify performance bottlenecks, especially under heavier workloads. For instance, we observed that small increases in memory usage or network latency can lead to noticeable slowdowns causing issues that are not always obvious from monitoring data alone. By linking live performance monitoring with AI-driven modeling, this approach reduces manual effort while producing more reliable simulations. It also enables faster and smarter “what-if” analysis for microservices. In the future, this method could be extended to other cloud-native systems and integrated into CI/CD pipelines to support automatic performance tuning and scaling decisions.




<img width="596" height="446" alt="LURA2025" src="https://github.com/user-attachments/assets/2300dfd0-39c0-4e06-b1c6-289b723facb5" />




<img width="1109" height="577" alt="image" src="https://github.com/user-attachments/assets/3486034e-5fed-4df8-b682-b3717dc5ffb4" />

