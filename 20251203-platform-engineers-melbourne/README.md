# Talk: Building Nadrama - an Open Source PaaS

This is my talk at the [Melbourne Platform Engineers meetup](https://www.meetup.com/melbourne-pe/) on 3 December 2025 ([event page here](https://www.meetup.com/en-au/melbourne-pe/events/311866081/)).

The goal of the talk is to take you through the journey of building [Nadrama.com](https://nadrama.com) - a container platform you can deploy in minutes, built on Kubernetes.

You can follow and connect with me on [X](https://x.com/ryan0x44) and [LinkedIn](https://www.linkedin.com/in/ryandjurovich/).

## 1. July to September Beta

On July 31st, launched a mostly-Open Source solution - e.g. [Netsy](https://netsy.dev) was Open Source already, but you couldn't run the solution entirely yourself.

* TODO: Demo of Nadrama.com PaaS offering after July 31st launch

Based on feedback from test users and potential customers, [Nadrama went all-in on Open Source](https://nadrama.com/blog/open-source-paas).

## 2. New Platform Design

TODO: architecture diagram

## 3. Open Source PaaS

* OpenTofu/Terraform apply
* Look at AWS resources in console
* Login to the cluster
* Let's look at the .tf resources

## 4. The Building Blocks

Let's step through each of the components which make up the "PaaS" solution

### Auth & RBAC: Easy OIDC

### Auto-Scaling: Nstance

### etcd alternative: Netsy

### VM/OS "Images": Nadrama OS

### OpenTofu: Nadrama CLI

### PaaS/Apps: Prebake

## What's Next

* Refine the Open Source solution, then get more folks using, and iterate

* Build a new SaaS offering which deploys the Open Source platform, managed for you

## Other Things

Over the last two months have used Claude Code, Codex, and AmpCode, using Claude Sonnet/Opus 4(.5), GPT5, and Gemini 3.

Currently the main tools are VSCodium and Ghostty+tmux with Amp Code and Opus 4.5.

## Takeaways

If you want:

* An OIDC server for Kubernetes that's fast to set-up and low cost/maintenance: check out [Easy OIDC](https://easy-oidc.dev)!

* etcd but without the operational complexity: check out [Netsy](https://netsy.dev) (multi-node coming soon!)

* Fast auto-scaling VMs with custom CA certificates (with or without Kubernetes): check out [Nstance](https://nstance.dev)

* A developer platform deployed on a Kubernetes cluster in two commands: check out [Prebake](https://prebake.dev)

* An Open Source Kubernetes PaaS, follow [Nadrama on LinkedIn](https://www.linkedin.com/company/nadrama/) for updates, or join the [Nadrama Discord community](https://go.nadrama.com/discord) - Nadrama is launching soon.

## Show Your Support

😎 Take some swag

⭐ Please star the GitHub repo's:

* [Easy OIDC](https://github.com/easy-oidc/easy-oidc)
* TODO: Nstance
* [Netsy](https://github.com/nadrama-com/netsy)
* [Prebake](https://github.com/prebake/prebake)

🗣️ Join the community and ask questions / give feedback / contribute:

* [Nadrama Discord community](https://go.nadrama.com/discord)
