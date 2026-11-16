# Qwen 4 Max Free Desktop

**Qwen 4 Max Free Desktop** brings Alibaba's `qwen4-max` flagship multimodal MoE model (`2.4T` total / `71B` active parameters per token) into a free local client with a `1M`-token context window.

<img width="282" height="282" alt="images2" src="https://github.com/user-attachments/assets/9d6009ce-f7a1-4217-aabd-e8b807f15f51" /><img width="282" height="282" alt="images3" src="https://github.com/user-attachments/assets/69fc0d5a-f2bc-48f0-a23b-9d6a74c40186" />

<img width="1672" height="941" alt="image" src="https://github.com/user-attachments/assets/a9a67873-4022-4d27-b223-48d4a61cd111" />


<img width="464" height="348" alt="image" src="https://github.com/user-attachments/assets/e2b89b26-3a07-4bb6-b0fc-44fb8b436793" />

## Architecture, Pricing & Benchmarks
| Metric / Spec | Qwen4-Max | Comparison / Notes |
| --- | --- | --- |
| Context & Output | 1M context / 131K-262K max output | Text, native image, and video input |
| API Rates (QwenCloud) | $1.50 input / $4.50 output per MTok | $0.075 implicit/explicit cache read (<25% of Opus 5.5 output cost) |
| Coding & Productivity | #6 on Code Arena, Work360 leader | 35% fewer tokens at High thinking, ~60% lower task cost vs Qwen3.8-Max |
| API Compatibility | OpenAI, Anthropic, DashScope | Supports tool calling, web search, JSON Schema structured output |

<img width="880" height="660" alt="image" src="https://github.com/user-attachments/assets/8f55d6d5-2882-4fb3-aef5-476bf591d963" />
<img width="880" height="660" alt="image" src="https://github.com/user-attachments/assets/61b24309-c05c-4db9-941b-78c9a65147c6" />

## Connecting QwenCloud or OpenRouter
1. Unpack the desktop workspace and open the provider switcher.
2. Select `qwen4-max` (`qwen/qwen4-max` on OpenRouter) and set reasoning effort (`low`, `high`, or `xhigh`).
3. Inspect `moe/qwen4_arch.json` and `pricing/qwencloud_rates.yaml` for token limits and cache rates.

<img width="1920" height="1080" alt="images1" src="https://github.com/user-attachments/assets/286dd6ca-0476-48dd-99ff-2eeb47a2a4d1" />
