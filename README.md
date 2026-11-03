<div align="center">

# ZΞI ForceSubs

### Kontenmu. Gerbangmu. Aturanmu.

Runtime ForceSubs untuk ekosistem **ZΞI Project**.

![Python](https://img.shields.io/badge/Python-3.12%2B-8B5CF6?style=flat-square)
[![GPL-3.0](https://img.shields.io/badge/License-GPL--3.0-22D3EE?style=flat-square)](LICENSE)

[Gate](https://github.com/H3llnn/ZEI-Gate) · [Payment](https://github.com/H3llnn/ZEI-Payment) · [Userbot](https://github.com/H3llnn/ZEI-Userbot)

</div>

## Yang ditangani runtime ini

- Pengaturan channel database dan tujuan ForceSubs.
- Pembuatan link konten serta batch.
- Pemeriksaan keanggotaan dan tombol Coba Lagi.
- Pengiriman konten dan penghapusan terjadwal.
- Pengaturan pemilik serta akses pembuatan link untuk admin.

`zei_forcesubs/child_ui.py` memiliki antarmuka bot anak. `zei_forcesubs/service.py` memiliki pengiriman konten, pemeriksaan akses, dan cleanup.

## Memasang

Letakkan **ZEI-Gate**, **ZEI-ForceSubs**, **ZEI-Payment**, dan **ZEI-Userbot** berdampingan. Jalankan `python install.py` dari folder Gate. Buka bot induk yang sama untuk membuat layanan; pengaturan bot anak tetap melalui `/setting`.

Ini paket runtime yang membutuhkan Gate sebagai host. Token, izin, database dan enkripsi tetap dikelola Gate. Repo terpisah tidak berarti harus memakai server atau bot induk terpisah.

## Pengujian dan pembaruan

Tes integrasi ada di Gate dan dijalankan CI repo ini dengan memasang seluruh runtime. Gunakan versi yang cocok dengan Gate; jangan mengganti runtime di instalasi aktif sebelum mencadangkan konfigurasi dan data.

[Struktur empat repo](https://github.com/H3llnn/ZEI-Gate/blob/main/docs/RUNTIME-SPLIT.md) · [Panduan update](https://github.com/H3llnn/ZEI-Gate/blob/main/docs/UPDATE-GUIDE.md)

## Lisensi

GPL-3.0. Kode diekstrak dari ZEI-Gate; riwayat sumber sebelumnya tersedia di repo Gate. Lisensi dan atribusi tetap dipertahankan dalam [LICENSE](LICENSE) dan [THIRD_PARTY_NOTICES.md](THIRD_PARTY_NOTICES.md).

**ZΞI PROJECT** · Maintained by **Zeisss**
