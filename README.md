# Leonardo Lopes Pereira

I write systems software in C, C++ and Go, and I have been contributing to the
GNU Mach microkernel since 2006. Studying at 42 Paris.

---

## Open source

**[GNU Mach](https://www.gnu.org/software/hurd/microkernel/mach/gnumach.html)** —
contributor since 2006, in the IPC and thread internals: FIPC, `MACH_IPC_COMPAT`,
`CONTINUATIONS`, `MIGRATING_THREADS` and `MACH_TTD`.

**mushroom-os** — my own Linux. A bootc OCI image on Fedora Silverblue, signed
with cosign and consumed via `bootc switch`. Proprietary NVIDIA modules compiled
from the upstream installer against the base's exact kernel, because the open
modules crash external-display hotplug on Turing cards without Resizable BAR.

**push_swap.go** — the push_swap algorithm reimplemented in Go: two stacks, a
fixed instruction set, and the shortest sequence that sorts them. Laid out as a
real Go module — `cmd`, `internal`, `pkg` — rather than a coursework single file.

My own infrastructure is Terraform — DNS, zones and repositories managed
declaratively rather than by clicking.

---

## École 42 projects

Working toward 42's **Architecte en Technologie du Numérique** title — RNCP level 7,
the Master's-equivalent French certification.

**ft_nm** — `nm`, reimplemented. Parses ELF32 and ELF64 executables, object files
and shared libraries directly, with no `libelf` or `libbfd`, and reproduces the
system `nm`'s output byte for byte. Every offset read from an untrusted file is
bounds-checked before it is followed.

**ft_transcendence** — a multi-user real-time social platform: profiles and
friendships, posts with images, likes and comments, private messages and
notifications, secured with JWT, 2FA and GitHub OAuth and shipped as an
installable PWA. Built as a five-person team with a Go backend.

---

## Skills

| Area | Skills |
| --- | --- |
| Programming | C, low-level programming, algorithms, functional and procedural programming |
| Python | Python, Matplotlib, Bokeh |
| Cloud & containers | AWS, Kubernetes, Istio, OpenShift, containers, autoscaling, YAML |
| Systems | Linux, Bash, shell scripting |
| Version control | Git, GitHub, GitLab, pull requests, open source |
| Engineering | Software architecture, software engineering, SDLC |
| Language | English — C1 Advanced (EF SET) |

---

## Certifications

| Certification | Issuer | Issued |
| --- | --- | --- |
| AWS Certified Developer – Associate | AWS Training and Certification | 2024 |
| CLA — C Certified Associate Programmer | C++ Institute | 2026 |
| CLE — C Certified Entry-Level Programmer | C++ Institute | 2026 |
| PCEP — Certified Entry-Level Python Programmer | Python Institute | 2023 |
| CodinGame C Certification | CodinGame | 2025 |
| CodinGame Kotlin Certification | CodinGame | 2025 |
| Container & Kubernetes Essentials | Coursera | 2024 |
| Linux Commands & Shell Scripting Essentials | Coursera | 2024 |
| Git and GitHub Essentials | Coursera | 2024 |
| Python for Data Science and AI | Coursera | 2024 |
| Software Engineering Essentials | Coursera | 2024 |
| English for IT B2 / GSE 59–75 | OpenEDG | 2024 |
| EF SET Certificate — C1 Advanced (62/100) | EF | 2025 |

Badges verified on [Credly](https://www.credly.com/users/leonardo-lopes-pereira); the
certificate PDFs are in [`certifications/`](certifications).

---

## Reach me

[![Email](https://img.shields.io/badge/email-leonardolopespereira@outlook.com-blue?style=flat-square)](mailto:leonardolopespereira@outlook.com)
[![LinkedIn](https://img.shields.io/badge/linkedin-leonardo--lopes--pereira-0A66C2?style=flat-square)](https://www.linkedin.com/in/leonardo-lopes-pereira)

My [résumé](https://github.com/llp42/resume) is written in LaTeX and builds from
source. Open to conversations about systems programming, kernel work and open
source. English, Portuguese and French are all fine.
