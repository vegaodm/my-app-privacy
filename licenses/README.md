# Third-Party Licenses

License notices for models and bundled open-source software in **LocalLLMClient / Pocket LLM**.

The published page is served from GitHub Pages at:

<https://vegaodm.github.io/my-app-privacy/licenses/>

## Contents

| File | Purpose |
| --- | --- |
| [index.html](index.html) | Human-readable page with attribution and links to the full texts |
| [LFM3-LICENSE.txt](LFM3-LICENSE.txt) | LFM Open License v1.0 |
| [Bonsai-NOTICE.txt](Bonsai-NOTICE.txt) | Prism ML NOTICE and Qwen3.5-2B attribution |
| [Bonsai-APACHE-2.0.txt](Bonsai-APACHE-2.0.txt) | Apache License 2.0 |

## Models

### LFM3 1.7B (4-bit MLX)

- Repository: <https://huggingface.co/LiquidAI/LFM3-1.7B-MLX-4bit>
- Copyright © Liquid AI, Inc.
- Licensed under the [LFM Open License v1.0](LFM3-LICENSE.txt).
- Commercial use is licensed only for Legal Entities with annual revenue under US$10 million.

### Bonsai 2 2B (ternary, MLX 2-bit)

- Repository: <https://huggingface.co/prism-ml/Ternary-Bonsai-2-2B-mlx-2bit>
- Copyright 2026-present Prism ML, Inc.
- Licensed under the [Apache License 2.0](Bonsai-APACHE-2.0.txt).
- Built from Qwen3.5-2B, Copyright 2026 Alibaba Cloud, also licensed under Apache 2.0.
- Attribution: "Created using Bonsai by Prism ML."

## Open Source Software

This app bundles or depends on open-source software. Full license texts and notices for
these dependencies are available in the app under **⋯ → Licenses…** (and will be included
in the published licenses page). Key dependencies include (non-exhaustive):

| Component | License | Notes |
| --- | --- | --- |
| [LocalLLMClient](https://github.com/tattn/LocalLLMClient) | MIT | Copyright © 2025 Tatsuya Tanaka (with additional contributions). |
| [mlx-swift-lm](https://github.com/ml-explore/mlx-swift-lm) (fork in repo) | MIT | ml-explore; modified in this fork. |
| [mlx-swift](https://github.com/ml-explore/mlx-swift) | MIT | ml-explore. |
| [swift-transformers](https://github.com/huggingface/swift-transformers) | Apache 2.0 | Hugging Face. |
| [swift-jinja](https://github.com/huggingface/swift-jinja) | Apache 2.0 | Hugging Face. |
| [swift-huggingface](https://github.com/huggingface/swift-huggingface) | Apache 2.0 | Hugging Face. |
| [Swift Crypto](https://github.com/apple/swift-crypto) | Apache 2.0 | Apple Inc. (see NOTICE). |
| [Swift ASN1](https://github.com/apple/swift-asn1) | Apache 2.0 | Apple Inc. (see NOTICE). |
| [swift-collections](https://github.com/apple/swift-collections) | Apache 2.0 | Apple Inc. |
| [swift-numerics](https://github.com/apple/swift-numerics) | Apache 2.0 | Apple Inc. |
| [yyjson](https://github.com/ibireme/yyjson) | MIT | © 2020 YaoYuan. |
| [EventSource](https://github.com/mattt/EventSource) | MIT | © 2025 Mattt. |

## In the app

The same notices are bundled with the app and shown under **⋯ → Licenses…**, so they remain readable offline.

## Publishing

Upload this folder to the `my-app-privacy` GitHub Pages repository as `licenses/`:

```text
my-app-privacy/
├── index.html          # privacy policy
├── support.html
└── licenses/
    ├── index.html
    ├── README.md
    ├── LFM3-LICENSE.txt
    ├── Bonsai-NOTICE.txt
    └── Bonsai-APACHE-2.0.txt
```

GitHub Pages serves the page at `/licenses/` with no build step.

The app links to <https://vegaodm.github.io/my-app-privacy/licenses/> from its
**Licenses** screen. If the repository or path changes, update that URL in
`Example/LocalLLMClientExample/LicensesView.swift` as well.
