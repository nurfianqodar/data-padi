---
author:
- Nurfian Qodar
authors:
- affiliations:
  - Universitas Siliwangi
  name: Nurfian Qodar
date: 2025-03-07
subtitle: Data produksi, luas lahan, dan produktivitas padi dari
  berbagai Provinsi di Indonesia dari tahun 2018-2024
title: Produksi dan Luas Lahan Padi di Indonesia
toc-title: Table of contents
---

# Load Data

> Data source: [Badan Pusat Statistik
> Indonesia](https://www.bps.go.id/id/statistics-table/2/MTQ5OCMy/luas-panen--produksi--dan-produktivitas-padi-menurut-provinsi.html)
> Cleaned Data:
> [Here](https://raw.githubusercontent.com/nurfianqodar/data-padi/refs/heads/main/data-padi.csv)

:::: cell
::: cell-output-display
  province                 harvest_area   productivity   production   year
  ---------------------- -------------- -------------- ------------ ------
  SUMATERA BARAT             3116712300           4758   1482996010   2019
  JAWA TIMUR                17474812000           5602   9789587670   2021
  KALIMANTAN BARAT           2240685200           3125    700290800   2023
  RIAU                        647331300           3764    243685040   2020
  NUSA TENGGARA BARAT        2817178400           5159   1453408370   2024
  GORONTALO                   469521500           5002    234862880   2024
  NUSA TENGGARA BARAT        2700929000           5379   1452945000   2022
  PAPUA SELATAN                      NA             NA           NA   2022
  KEP. BANGKA BELITUNG        172335900           2653     45724690   2018
  JAWA TIMUR                17024263600           5628   9580933880   2019

  : Sample data luas panen, produksi, dan produktivitas
:::
::::

## Legend

:::: cell
::: cell-output-display
  Nama Kolom     Deskripsi          Satuan    Tipe Data
  -------------- ------------------ --------- ------------------
  province       Nama provinsi      $-$       char, not null
  harvest_area   Luas lahan panen   $m^2$     double, nullable
  prductivity    Produktivitas      $kg/ha$   double, nullable
  production     Produksi           $kg$      double, nullable
  year           Tahun pendataan    $-$       int, not null

  : Keterangan nama kolom tabel
:::
::::
