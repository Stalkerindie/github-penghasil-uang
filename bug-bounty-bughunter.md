# Claude-BugHunter — Bundle Skill Bug Bounty & Red-Team

> Satu bundle metodologi perburuan bug: 82 skill, 15 slash command, 681 pola laporan
> yang sudah diungkap, mencakup 24 kelas kerentanan inti — plus matriks serangan
> enterprise identity + infrastruktur.

- **Repo:** [elementalsouls/Claude-BugHunter](https://github.com/elementalsouls/Claude-BugHunter)
- **Lisensi:** MIT
- **Star:** 18.764 (verifikasi 23 Nov 2026) · 2.041 fork · dibuat 5 Mei 2026

## Cara Memakai Bundle Ini

Bundle ini **bukan plugin yang di-install mentah-mentah**. Baca file skill-nya satu per satu
dari repo sebagai DATA saat sebuah perburuan butuh: metodologi, checklist, pola laporan,
atau skill khusus satu kelas kerentanan. Pakai hanya yang perburuan itu butuhkan.

## Yang Paling Relevan

Sebagian besar isi bundle ini adalah **Web2 / red-team** (gaya HackerOne/Bugcrowd) —
payload-nya tidak berlaku untuk Solidity. Yang bisa dipakai untuk perburuan smart-contract:
metodologi, recon/triage, penulisan laporan, dan pola laporan yang sudah diungkap sebagai
checklist "seperti apa laporan yang menang".

Skill yang paling dekat dengan perburuan smart-contract:
`web3-audit` · `meme-coin-audit` · `bb-methodology` · `report-writing` ·
`triage-validation` · `recon-scope-triage`.

## 15 Slash Command

`autopilot` · `chain` · `hunt` · `intel` · `memory-gc` · `pickup` · `recon` ·
`remember` · `report` · `scope` · `surface` · `token-scan` · `triage` · `validate` ·
`web3-audit`

## 82 Skill (per kategori)

- **Metodologi & pelaporan:** bb-methodology · bug-bounty · bugcrowd-reporting ·
  evidence-hygiene · recon-scope-triage · report-writing · triage-validation ·
  redteam-mindset · redteam-report-template · security-arsenal
- **Web3:** web3-audit · meme-coin-audit
- **Recon & OSINT:** bb-local-toolkit · offensive-osint · osint-methodology ·
  web2-recon · hunt-subdomain · hunt-source-leak · supply-chain-attack-recon
- **Auth & sesi:** hunt-auth-bypass · hunt-ato · hunt-brute-force ·
  hunt-forgot-password · hunt-jwt-crypto · hunt-mfa-bypass · hunt-oauth ·
  hunt-saml · hunt-session · hunt-captcha-bypass
- **Injection & server-side:** hunt-sqli · hunt-nosqli · hunt-xss · hunt-xxe ·
  hunt-ssti · hunt-rce · hunt-ssrf · hunt-lfi · hunt-deserialization ·
  hunt-file-upload · hunt-html-injection · hunt-dom · hunt-http-smuggling
- **API & logika:** hunt-api-misconfig · hunt-graphql · hunt-fintech-graphql ·
  hunt-grpc · hunt-websocket · hunt-shadow-api · hunt-spa-api ·
  hunt-business-logic · hunt-race-condition · hunt-idor · hunt-cors · hunt-csrf ·
  hunt-clickjacking · hunt-host-header · hunt-open-redirect · hunt-cache-poison
- **Cloud & infra:** cloud-iam-deep · hunt-cloud-misconfig · hunt-k8s · hunt-cicd ·
  hunt-tls-network · enterprise-vpn-attack · vmware-vcenter-attack ·
  m365-entra-attack · okta-attack · hunt-ntlm-info · hunt-ldap
- **App stack:** hunt-aspnet · hunt-laravel · hunt-nextjs · hunt-nodejs ·
  hunt-springboot · hunt-llm-ai · hunt-rag-vector · hunt-misc ·
  hunt-exceptional-conditions · mid-engagement-ir-detection
- **Mobile:** apk-redteam-pipeline · ios-redteam-pipeline
- **Pipeline:** hunt-dispatch

## Aturan Main

- Jangan pernah submit laporan bug bounty tanpa persetujuan eksplisit per temuan.
- Jangan pernah exploit di mainnet atau mengirim transaksi mainnet.
- Jangan bayar apa pun tanpa persetujuan eksplisit.

*Dikurasi oleh Aspri untuk Rifai · 23 Nov 2026*
