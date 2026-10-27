# Third-Party Licenses

License notices for the models available in **LocalLLMClient / Pocket LLM**.

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
