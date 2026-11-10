# Systems & Network Administrator Apprentice

I'm a **Systems & Network Administrator apprentice at CNRS**, working within the Laboratory of Analysis and Applied Mathematics (**LAMA, UMR 8050**) in France. I'm also in the second year of a **BTS SIO SISR** degree.

What interests me most is how an infrastructure comes together: the hardware behind it, the network between its parts, and the choices that make a design understandable and workable. I explore those questions through Linux, virtualisation, and my Proxmox homelab.

![Linux](https://img.shields.io/badge/Linux-142940?style=flat-square&logo=linux&logoColor=white)
![Networking](https://img.shields.io/badge/Networking-168FAB?style=flat-square)
![Virtualisation](https://img.shields.io/badge/Virtualisation-5374BF?style=flat-square)
![Proxmox homelab](https://img.shields.io/badge/Proxmox%20homelab-D98929?style=flat-square&logo=proxmox&logoColor=white)

---

## What I build

Two projects, each looking at a different layer of infrastructure:

| Project | Focus |
| --- | --- |
| **🟦 Rawbox** | A container runtime built from scratch to understand what runs beneath Docker. |
| **🟧 Private cloud** · In progress | A fictional-company lab with Nextcloud, a separate database and Redis cache, and S3 object storage distributed across four RustFS nodes. |

---

## Rawbox — looking beneath Docker

![Project type: container runtime](https://img.shields.io/badge/PROJECT-Container%20runtime-168FAB?style=flat-square)

Containers are easy to use without ever seeing what the runtime does. **Rawbox** is my attempt to close that gap by building a container runtime from scratch.

The point of the project is to understand the layer Docker normally hides: what it means to run a container, and what responsibilities belong to the runtime itself.

---

## Private cloud — designing the pieces together

![Status: in progress](https://img.shields.io/badge/STATUS-In%20progress-D98929?style=flat-square)
![Project type: architecture lab](https://img.shields.io/badge/PROJECT-Architecture%20lab-5374BF?style=flat-square)

**Fictional-company lab**

This project starts with an architecture question: how should the application, its supporting services, and its storage fit together in a private cloud?

The design uses **Nextcloud** as the application, with a **separate database** and **Redis cache**. Its **S3 object storage** is distributed across **four RustFS nodes**. The fictional-company setting gives me a concrete way to work through service boundaries, data flow, networking, and hardware choices as the lab develops.
