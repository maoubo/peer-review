<h1>IntraGuard</h1>

Note: Because Anonymous GitHub does not support files larger than 8 MB, we provide only a small number of representative samples in the  `/data` directory.

<h2>Environment Setup</h2>

1. **Transfer Environment File:**
    - Move the environment configuration file `environment.yml` to your target server.

2. **Create Conda Environment:**
    - Run the following command to create a new Conda environment:
      ```
      conda env create -n reviewer -f environment.yml
      ```

    - **Note:** If you prefer to install the environment manually (instead of using the `.yml` file), make sure to include the following key packages.  We recommend using the exact versions listed below, as they have been tested to be mutually compatible:
      - `python = 3.14`
      - `pymupdf = 1.26.5`
      - `pikepdf = 10.0.0`

<h2>Evaluated Chatbots</h2>

| Chatbot   | Backbone Model            | Official Website                        | Manufacturer  |
|-----------|---------------------------|------------------------------------------|---------------|
| Qwen Chat (v1) | Qwen3-Max                 | https://www.qianwen.com/chat            | Alibaba Cloud |
| Qwen Chat (v2) | Qwen3.5-Plus              | https://www.qianwen.com/chat            | Alibaba Cloud |
| ChatGPT (v1)   | GPT-5.1                   | https://chatgpt.com                     | OpenAI        |
| ChatGPT (v2)   | GPT-5.2                   | https://chatgpt.com                     | OpenAI        |
| SuperGrok      | Grok-4.1                  | https://grok.com                        | xAI           |
| Kimi           | Kimi-K2.5                 | https://www.kimi.com/                   | Moonshot AI   |
| Doubao         | Doubao-Seed-2.0           | https://www.doubao.com/chat             | ByteDance     |

<h2>Evaluated Venues</h2>

| Abbreviation | Full Name | Review Policy | Format | Avg Pages | Avg Size (MB) |
|---|---|---|---|---:|---:|
| CCS | ACM Conference on Computer and Communications Security | Single-blind | Double-column | 14.9 | 3.11 |
| S&P | IEEE Symposium on Security and Privacy | Single-blind | Double-column | 18.6 | 1.08 |
| USENIX | USENIX Security Symposium | Double-blind | Double-column | 18.0 | 2.31 |
| NDSS | Network and Distributed System Security Symposium | Single-blind | Double-column | 17.9 | 2.19 |
| NeurIPS | Neural Information Processing Systems | Single-blind | Single-column | 16.3 | 1.76 |
| ICLR | International Conference on Learning Representations | Double-blind | Single-column | 11.9 | 2.01 |
| ICML | International Conference on Machine Learning | Single-blind | Double-column | 13.6 | 2.54 |
| Nature | Nature | Single-blind | Double-column | 9.1 | 8.13 |
| Nat. Bio. | Nature Biotechnology | Single-blind | Double-column | 13.1 | 3.07 |
| Adv. Mater. | Advanced Materials | Single-blind | Double-column | 12.6 | 3.17 |
| Psychol. Rev. | Psychological Review | Single-blind | Double-column | 21.7 | 1.09 |
| T-ITS | IEEE Transactions on Intelligent Transportation Systems | Single-blind | Double-column | 13.8 | 2.51 |