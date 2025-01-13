# Case Study: Synchronous Clients

### Introduction

This case study explores the performance, resource consumption, and resilience of three different HTTP client libraries commonly used in Java-based microservices: **RestTemplate**, **Feign Client**, and **WebClient**. Each tool has unique characteristics and is suited for different use cases, such as simple synchronous operations or complex reactive programming. Through controlled experiments, we evaluate their behavior under varying loads and fault scenarios to provide insights for developers choosing the appropriate client for their needs.

### Repository Links

Here are the repositories containing the implementations and test setups for each client:

- **RestTemplate**: [HI_RestTemplate](https://github.com/ilyassoh/HI_RestTemplate)
- **Feign Client**: [HI_Feign-Client](https://github.com/ilyassoh/HI_Feign-Client)
- **WebClient**: [HI_WebClient](https://github.com/ilyassoh/HI_WebClient)

Each repository includes:
- Configuration files.
- Sample use cases.
- Performance testing scripts.
- Detailed instructions for running the experiments.

### Purpose

This study aims to:
1. Compare the **latency** and **throughput** of the three clients under similar conditions.
2. Assess **resource utilization**, including CPU, memory, and energy consumption.
3. Evaluate **resilience** in failure scenarios, such as network outages and service crashes.

By analyzing these factors, we provide actionable recommendations for selecting the most suitable client library in real-world applications.
