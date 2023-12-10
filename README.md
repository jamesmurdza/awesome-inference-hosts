# List of cloud hosts for inference and fine-tuning

## Hosts
### Inference:
- [banana.dev](https://www.banana.dev/): Hosting focused on high-throughput inference. [Deploys](https://www.banana.dev/blog/how-to-deploy-mistral-7b) from a GitHub repo.
- [fal.ai](https://www.fal.ai/): Hosting for inference, image generation and audio generation with [playgrounds](https://www.fal.ai/models) and shared endpoints for open source models. A100s, A10Gs and T4s. Pricing scales to zero.
- [replicate.com](https://replicate.com/): Lots of preconfigured models and playgrounds for text, image, music and speech generation. A100s, A40s, and T4s. [Pricing](https://replicate.com/pricing) scales to zero.
- [lepton.ai](https://www.lepton.ai/): Hosting and inference via CLI tools. Can deploy prebuilt HuggingFace models with a single command. [Pricing](https://www.lepton.ai/pricing) scales to zero.
- [titanml.co](https://titanml.co/): Inference deployements focused on CLI and enterprise.
    
### Inference and fine-tuning:
- [anyscale.com](https://www.anyscale.com/endpoints): Inference and fine-tuning. Shared endpoints for Llama 2, Code Llama and Mistral 7B. Supports a common fine-tuning API with OpenAI. A10s, A100s and (coming soon) H100s.
- [together.ai](https://www.together.ai/): Inference and fine-tuning. [68 shared endpoints](https://api.together.xyz/playground) and playgrounds for text and image generation. A40s, A100s and H100s. [Pricing](https://www.together.ai/pricing) scales to zero.
- [brev.dev](https://brev.dev/): Focused on instance hosting and CLI tools. Ten types of GPU including A100s and H100s. Supports deploying to your existing AWS and GCP accounts. Serverless [prices](https://brev.dev/pricing) are constantly updated. Deploying to your existing cloud is free.
- [gradient.ai](https://gradient.ai/): Focused on fine-tuning via CLI, Python, NodeJS and an online console to create and manage jobs.
- [fireworks.ai](https://fireworks.ai/): Inference platform focused on CLI with a number of [shared endpoints](https://app.fireworks.ai/models). Supports LoRA addons. [Pricing](https://readme.fireworks.ai/page/pricing).

## Table
| Service | URL | Focus | GPU Types | Pricing | Additional Features |
|---------|-----|-------|-----------|---------|---------------------|
| **Banana.dev** | [banana.dev](https://www.banana.dev/) | High-throughput inference | Not specified | Scales to zero | Deploys from GitHub repo |
| **Fal.ai** | [fal.ai](https://www.fal.ai/) | Inference, image and audio generation | A100s, A10Gs, T4s | Scales to zero | Playgrounds and shared endpoints |
| **Replicate.com** | [replicate.com](https://replicate.com/) | Text, image, music, speech generation | A100s, A40s, T4s | [Scales to zero](https://replicate.com/pricing) | Preconfigured models and playgrounds |
| **Lepton.ai** | [lepton.ai](https://www.lepton.ai/) | Hosting and inference via CLI | Not specified | [Scales to zero](https://www.lepton.ai/pricing) | Deploys HuggingFace models |
| **TitanML.co** | [titanml.co](https://titanml.co/) | CLI and enterprise inference deployments | Not specified | Not specified | - |
| **Anyscale.com** | [anyscale.com](https://www.anyscale.com/endpoints) | Inference and fine-tuning | A10s, A100s, H100s (soon) | Not specified | Shared endpoints for various models |
| **Together.ai** | [together.ai](https://www.together.ai/) | Inference and fine-tuning | A40s, A100s, H100s | [Scales to zero](https://www.together.ai/pricing) | 68 shared endpoints and playgrounds |
| **Brev.dev** | [brev.dev](https://brev.dev/) | Hosting and CLI tools | A100s, H100s, others | [Varies](https://brev.dev/pricing), Free for existing cloud | Deploys to AWS and GCP |
| **Gradient.ai** | [gradient.ai](https://gradient.ai/) | Fine-tuning via CLI/Python/NodeJS | Not specified | Not specified | Online console for job management |
| **Fireworks.ai** | [fireworks.ai](https://fireworks.ai/) | CLI inference platform | Not specified | [Varies](https://readme.fireworks.ai/page/pricing) | Shared endpoints, supports LoRA addons |
