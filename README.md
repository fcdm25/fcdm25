I design and run identity and access management at enterprise scale — the control plane that decides **who, and what, is allowed to act inside a regulated payments business**.

Most of my work sits where authentication, authorization, and lifecycle governance meet the day-to-day running of the platform: standards-based federation that holds during an incident, least-privilege that doesn't quietly decay into standing access, and threat response the org can absorb without stalling. I've spent fifteen-plus years on it, across fintech, healthcare, public sector, and retail, in Europe and the Middle East. The recurring lesson: the hard part of IAM isn't the protocol. It's making the secure path the default one.

---

### What I focus on

- **Enterprise SSO and federation** — one of the founding engineers of Adyen's workforce SSO, designed as one coherent platform that scales with the org.
- **Phishing-resistant authentication** — helped move staff off phishable factors and onto credentials an attacker can't replay or relay.
- **Identity threat detection and response** — led the rollout of Okta Identity Threat Protection, wiring continuous risk signals into real-time session and access decisions, including universal logout.
- **Audit-ready governance** — controls built into how access is granted, so the evidence a GDPR, PCI DSS, or ISO audit asks for already exists instead of being reconstructed afterward.
- **Brokered, least-privilege access** — short-lived credentials governed by policy-as-code an on-call engineer can read top to bottom and reason about before it runs.

### In production

<table>
<tr><th align="left">Domain</th><th align="left">What that means in practice</th></tr>
<tr>
<td><b>Identity protocols</b></td>
<td>OAuth&nbsp;2.0, OIDC, SAML and SCIM treated as core infrastructure rather than one-off integrations.</td>
</tr>
<tr>
<td><b>Platforms</b></td>
<td>Okta, Microsoft Entra ID and Active Directory in production, with HashiCorp Vault issuing short-lived database, cloud and SSH credentials.</td>
</tr>
<tr>
<td><b>IGA / access lifecycle</b></td>
<td>Joiner/mover/leaver automation, periodic access reviews, and a recertification cadence that keeps entitlements current.</td>
</tr>
</table>

<sub>Okta Certified Administrator (current to 2026).</sub>

---

### Beyond the day job

- **[Auth Point](https://makarov.cloud)** — my IAM-only blog: universal logout, device trust for every employee, and the gap between an SSO diagram and SSO in production.
- **Public Stratum-2 NTP server** — `ntp.makarov.cloud`, in the [NTP Pool's Netherlands (`nl`) zone](https://www.ntppool.org/zone/nl), giving time back to clients across the pool.
- **Homelab as a permanent test bench** — Synology, UniFi (WiFi&nbsp;7), WireGuard / Reality VPN, and Home Assistant. Where authentication, networking, and DPI-resistant tunnels get broken long before any of it gets near production.
- **[sater.lv](https://sater.lv)** — a just-for-fun side build for a Riga appliance-repair shop: Next.js&nbsp;16 + TypeScript + Tailwind.

<sub>Working languages: English and Russian.</sub>
