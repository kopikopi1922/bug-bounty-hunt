# Bug Bounty Hunt

Catatan perburuan bug bounty: metodologi, program yang dipantau, dan pelacak temuan.

## Program yang dipantau

- Ethereum Foundation — Glamsterdam (scope 18 EIP, hadiah s.d. $1M)
- Immunefi — Metric DEX (s.d. $500.000)

## Metodologi

- Audit kode sumber baris demi baris (execution client, smart contract, spesifikasi).
- Buktikan tiap temuan dengan Proof of Concept yang bisa dijalankan ulang.
- Nilai severity dengan jujur — jangan membesarkan temuan.
- Cek duplikasi terhadap laporan audit yang sudah terbit sebelum submit.
- Tidak ada submission tanpa go-ahead eksplisit.

## Peralatan

- Foundry (forge), Go, Rust
- NucleiFuzzer (Web2: dalfox, sqlmap)
- Agentic Bug Hunter (metodologi audit)

## Pelacak temuan

| ID | Program | Status |
|----|---------|--------|
| — | — | — |

Temuan detail dicatat di `findings/` (satu file per temuan, format laporan program).
