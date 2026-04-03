# Docker Hardened Images — Technical Learning Notes

An interactive, self-contained learning site covering Docker Hardened Images (DHI) in depth — from layer anatomy and CVE reduction to supply chain security and Azure cloud integration.

## 🌐 Live Site

> Deployed via GitHub Pages

## 📚 What's Inside

| Section | Description |
|---|---|
| **01 / Core Concepts** | What "hardened" actually means, comparison table vs standard images |
| **02 / Five Pillars** | Distroless base, CVE-free builds, Cosign signing, rootless, read-only FS |
| **03 / Interactive Explorer** | Layer anatomy, simulated CVE scanner, attack path simulator |
| **04 / Supply Chain Security** | SBOM, SLSA Level 3, Cosign provenance, multi-stage Dockerfile pattern |
| **05 / Azure Integration** | AKS, ACR, Defender for Containers, DevOps pipeline, Key Vault, WAF |
| **06 / Tradeoffs & Reference** | Known limitations, quick-reference CLI commands |

## 🛠️ Tech

Single-file static site — pure HTML, CSS, and vanilla JavaScript. No build step, no dependencies. Deployable anywhere static files are served.

## 🚀 Running Locally

```bash
# Just open index.html in your browser, or serve with any static file server:
npx serve .
# or
python -m http.server 8080
```

## 🔗 Key References

- [Docker Hardened Images Docs](https://docs.docker.com/trusted-content/hardened-images/)
- [Docker Scout](https://docs.docker.com/scout/)
- [Sigstore / Cosign](https://docs.sigstore.dev/)
- [SLSA Framework](https://slsa.dev/)
- [Google Distroless](https://github.com/GoogleContainerTools/distroless)
- [Azure Well-Architected Framework — Security](https://learn.microsoft.com/en-us/azure/well-architected/security/)

---

*Notes generated from a deep-dive learning session. Part of an ongoing Azure cloud architect study track.*
