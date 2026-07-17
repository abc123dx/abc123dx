<p align="center">
  <img
    src="./assets/profile-header.svg"
    alt="abc123dx — agent systems, modern runtimes, and trustworthy tools"
    width="100%"
  />
</p>

<p align="center">
  <a href="#modern-systems-lab">Modern lab</a>
  ·
  <a href="#established-ai-tooling">AI tooling</a>
  ·
  <a href="#engineering-map">Engineering map</a>
</p>

<p align="center">
  I build small, inspectable systems for agent interoperability, portable
  runtimes, local-first reliability, GPU compute, and WebAssembly.
  <br />
  <sub>Agent 系统 · 现代运行时 · 可信开发工具</sub>
</p>

<p align="center">
  <code>TypeScript 5</code>&nbsp;
  <code>Python 3.11+</code>&nbsp;
  <code>Rust stable</code>&nbsp;
  <code>A2A 1.0</code>&nbsp;
  <code>WebGPU / WGSL</code>&nbsp;
  <code>CRDT</code>&nbsp;
  <code>WASI 0.3</code>
</p>

## Modern systems lab

<p align="center">
  <img
    src="./assets/lab-constellation.svg"
    alt="Five independent labs for Agent protocols, edge runtimes, WebGPU, local-first synchronization, and WASI components"
    width="100%"
  />
</p>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/abc123dx/a2a-contract-lab">
          A2A Contract Lab
        </a>
      </h3>
      <p>
        <code>Python</code>
        <code>A2A 1.0</code>
        <code>v0.1.0</code>
      </p>
      <p>
        Offline-first contract testing for Agent Cards and A2A HTTP+JSON
        behavior, with a bounded loopback mock agent and portable evidence.
      </p>
      <p>
        <strong>54 tests · 9/9 scenarios</strong><br />
        Terminal · JSON · JUnit · self-contained HTML
      </p>
      <p>
        <a href="https://github.com/abc123dx/a2a-contract-lab">Repository</a>
        ·
        <a href="https://github.com/abc123dx/a2a-contract-lab/releases/tag/v0.1.0">Release</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/abc123dx/webgpu-kernel-lab">
          WebGPU Kernel Lab
        </a>
      </h3>
      <p>
        <code>TypeScript</code>
        <code>WGSL</code>
        <code>v0.1.0</code>
      </p>
      <p>
        An interactive compute workbench with real vector, matrix, and image
        convolution kernels, deterministic CPU references, and local metrics.
      </p>
      <p>
        <strong>39 tests · 3 WGSL kernels</strong><br />
        Median / p95 timing · error validation · JSON export
      </p>
      <p>
        <a href="https://github.com/abc123dx/webgpu-kernel-lab">Repository</a>
        ·
        <a href="https://github.com/abc123dx/webgpu-kernel-lab/releases/tag/v0.1.0">Release</a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/abc123dx/edge-api-atlas">
          Edge API Atlas
        </a>
      </h3>
      <p>
        <code>Python + JS</code>
        <code>WinterTC</code>
        <code>v0.1.0</code>
      </p>
      <p>
        Behavior-level portability probes for Node, Deno, and Bun across web
        APIs, streams, crypto, compression, timing, and structured data.
      </p>
      <p>
        <strong>37 tests · 21 network-free probes</strong><br />
        JSON · Markdown · HTML · cross-runtime comparison
      </p>
      <p>
        <a href="https://github.com/abc123dx/edge-api-atlas">Repository</a>
        ·
        <a href="https://github.com/abc123dx/edge-api-atlas/releases/tag/v0.1.0">Release</a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/abc123dx/sync-chaos-lab">
          Sync Chaos Lab
        </a>
      </h3>
      <p>
        <code>TypeScript</code>
        <code>Automerge 3</code>
        <code>Yjs</code>
        <code>v0.1.0</code>
      </p>
      <p>
        Deterministic CRDT fault injection for partitions, packet loss,
        duplication, reordering, latency, and replica restarts.
      </p>
      <p>
        <strong>35 tests · exact cross-process replay</strong><br />
        CLI · interactive explorer · JSON / single-file HTML
      </p>
      <p>
        <a href="https://github.com/abc123dx/sync-chaos-lab">Repository</a>
        ·
        <a href="https://github.com/abc123dx/sync-chaos-lab/releases/tag/v0.1.0">Release</a>
      </p>
    </td>
  </tr>
  <tr>
    <td colspan="2" valign="top">
      <h3>
        <a href="https://github.com/abc123dx/wasi-component-lens">
          WASI Component Lens
        </a>
      </h3>
      <p>
        <code>Rust</code>
        <code>WASI 0.3</code>
        <code>Component Model</code>
        <code>v0.1.0</code>
      </p>
      <p>
        Static interface and composition analysis for WebAssembly core modules,
        Components, WIT contracts, and WASI capabilities. It inventories,
        snapshots, diffs, and composes artifacts without executing them.
      </p>
      <p>
        <strong>50 tests · Rustfmt clean · Clippy clean</strong><br />
        Terminal · stable JSON · Mermaid · macOS arm64 release binary
      </p>
      <p>
        <a href="https://github.com/abc123dx/wasi-component-lens">Repository</a>
        ·
        <a href="https://github.com/abc123dx/wasi-component-lens/releases/tag/v0.1.0">Release</a>
      </p>
    </td>
  </tr>
</table>

## Established AI tooling

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/abc123dx/agent-skill-aegis">
          Agent Skill Aegis
        </a>
      </h3>
      <p>
        <code>TypeScript</code>
        <code>Node.js 20+</code>
        <code>v0.1.0</code>
      </p>
      <p>
        A local, deterministic supply-chain scanner for MCP configurations and
        Agent Skills. It turns risky configuration into reviewable terminal,
        JSON, HTML, or SARIF findings without executing discovered commands.
      </p>
      <ul>
        <li>12 inspectable security rules with redacted evidence</li>
        <li>Read-only discovery and four portable report formats</li>
        <li>Composite action for pull-request security gates</li>
      </ul>
      <p>
        <strong>Verified locally · 2026-07-17</strong><br />
        27/27 Vitest tests · ESLint clean · TypeScript typecheck clean
      </p>
      <p>
        <a href="https://github.com/abc123dx/agent-skill-aegis">
          Repository
        </a>
        ·
        <a href="https://github.com/abc123dx/agent-skill-aegis/releases/tag/v0.1.0">
          v0.1.0 release
        </a>
      </p>
    </td>
    <td width="50%" valign="top">
      <h3>
        <a href="https://github.com/abc123dx/traceforge-otel">
          TraceForge OTel
        </a>
      </h3>
      <p>
        <code>Python 3.11+</code>
        <code>OpenTelemetry</code>
        <code>v0.1.0</code>
      </p>
      <p>
        A local-first CLI that turns OTLP JSON and JSONL traces into practical
        AI-agent diagnostics: critical paths, tool failures, retries, token
        usage, and explicit cost estimates.
      </p>
      <ul>
        <li>Terminal, stable JSON, and self-contained HTML reports</li>
        <li>User-supplied pricing rules; no silently aging price table</li>
        <li>No backend, account, or telemetry upload</li>
      </ul>
      <p>
        <strong>Verified locally · 2026-07-17</strong><br />
        14/14 pytest tests · Ruff clean · strict mypy clean
      </p>
      <p>
        <a href="https://github.com/abc123dx/traceforge-otel">
          Repository
        </a>
        ·
        <a href="https://github.com/abc123dx/traceforge-otel/releases/tag/v0.1.0">
          v0.1.0 release
        </a>
      </p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="24%" valign="middle">
      <strong>
        <a href="https://github.com/abc123dx/Model-Relay-Station">
          Model Relay Station
        </a>
      </strong>
      <br />
      <code>Next.js 16</code> <code>TypeScript</code>
    </td>
    <td width="58%" valign="middle">
      One OpenAI-compatible endpoint for multiple model providers, with
      routing, failover, quotas, health checks, usage logs, and local SQLite
      storage. Currently in active early development.
    </td>
    <td width="18%" align="right" valign="middle">
      <a href="https://github.com/abc123dx/Model-Relay-Station">
        View project →
      </a>
    </td>
  </tr>
</table>

## Engineering map

<p align="center">
  <img
    src="./assets/project-system.svg"
    alt="Conceptual focus map: route model access, guard agent configuration, and observe runtime traces"
    width="100%"
  />
</p>

<p align="center">
  <sub>
    A conceptual map of the work, not a claim that the three repositories form
    one bundled platform.
  </sub>
</p>

## Current focus

- **Interoperable agents** — make Agent Cards, protocol behavior, and trust
  boundaries testable without depending on a remote service.
- **Portable compute** — compare runtime behavior at the web API, WebGPU, and
  WebAssembly component boundaries.
- **Reproducible distributed systems** — turn CRDT partitions and delivery
  faults into seeded traces that can be replayed exactly.
- **Inspectable AI infrastructure** — keep routing, configuration security, and
  runtime evidence local and understandable.

## Build philosophy

> Small interfaces. Explicit trust. Observable behavior.

Local-first when practical, typed at the boundaries, and explicit about
limitations. Every featured lab ships with runnable code, documentation,
tests, a release, and no account or telemetry requirement.
