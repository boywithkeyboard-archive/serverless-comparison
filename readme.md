## serverless comparison

| Service | Language | Low-Level Access | Cold Starts | Duration | Traffic Included | Pricing |
| --- | --- | --- | --- | --- | --- | --- |
| [**Cloudflare Workers**]() | JavaScript, WebAssembly | ✖️ | ✖️ | up to 50ms | ✔️ | $0.50/million requests |
| [**Deno Deploy**]() | JavaScript, WebAssembly | ✔️ | ✔️ | up to 50ms | ✖️ | $2/million requests |
| [**DigitalOcean Functions**]() | Node.js, Python, Go, PHP | ✔️ | ✔️ | variable | ✖️ | $0.0000185/GB-second |
