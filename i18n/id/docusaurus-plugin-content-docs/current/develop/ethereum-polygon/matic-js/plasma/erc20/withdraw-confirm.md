---
id: withdraw-confirm
title: withdraw challenge
keywords:
- 'plasma client, erc20, withdrawChallenge, polygon, sdk'
description: 'Mengonfirmasi penarikan.'
---

Metode `withdrawConfirm` adalah langkah kedua dalam proses penarikan plasma. Dalam langkah ini - bukti dari transaksi bakar Anda (transaksi pertama) dikirimkan dan token erc721 dengan nilai setara diciptakan.

Setelah proses ini berhasil, periode tantangan dimulai dan setelah periode tantangan selesai, pengguna bisa mendapatkan kembali jumlah yang ditarik ke akun mereka di rantai root.

Periode tantangan berlangsung selama 7 hari untuk mainnet.

**Catatan** - transaksi withdrawStart harus diperiksa untuk menantang proses penarikan.

```
const erc20Token = plasmaClient.erc20(<token address>, true);

const result = await erc20Token.withdrawConfirm(<burn tx hash>);

const txHash = await result.getTransactionHash();

const txReceipt = await result.getReceipt();

```

Setelah periode tantangan selesai, `withdrawExit` dapat dipanggil untuk keluar dari proses penarikan dan mengembalikan jumlah yang ditarik.
