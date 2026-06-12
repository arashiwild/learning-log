# Monorepo vs Polyrepo

## Monorepo
Semua project dalam satu repository. Memudahkan sharing code dan refactor lintas project, tapi butuh tooling khusus (Nx, Turborepo) untuk skala besar.

## Polyrepo
Setiap project punya repository sendiri. Lebih terisolasi, tapi sharing code antar project lebih rumit (perlu package terpisah).
