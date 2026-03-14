---
date: '2024-01-30T02:41:45+07:00'
draft: false
title: 'Ranger File Manager'
tags: [tech, tutorial, ranger]
description: 'Ranger merupakan file manager yang berbasis terminal, sehingga tidk perlu GUI. Ranger memiliki banyak fitur-fitur yang sangat berguna dibandingkan program file manager lainnya yang berbasis GUI.'
---

{{< img src="/ranger.png" title="Ranger FM" alt="Ranger" >}}

Ranger merupakan terminal based program yang berfungsi sebagai file manager sebgaimana. Pada tutorial ini saya menggunakan Ranger pada WSL di Windows 11 dengan distro **Ubuntu**. Ranger juga tersedia pada repository lain seperti Arch Repo, dnf, dan nix-pkg. 

Ada beberapa fitur yang tidak dapat berjalan pada WSL contohnya seperti Image Preview hal ini dikarenakan image preview membutuhkan X-Server/Display server seperti halnya di linux. 

Pada blog post ini saya ingin menunjukkan cara membuka program windows dari ranger pada WSL. Sebelum itu kita harus install Ranger terlebih dahulu. Berikut cara instalasinya:
1. Buka WSL Pada Terminal
2. Install ranger
```shell
sudo apt install ranger
```
3. Copy Ranger Config dari GitHub saya
```shell
git clone -n --depth=1 --filter=tree:0 https://github.com/Linc2427/DotFiles.git && cd DotFiles && git sparse-checkout set --no-cone ranger && git checkout && mv ranger ../ && cd ../ && rm -rf DotFiles
```
4. Jalankan Ranger
```shell
ranger
```

Nah! Sekarang jika kalian membuka file misalkan docx maka nantinya akan langsung membuka microsoft word atau default word processor kalian. 👍😁👍

Untuk Keybinding dapat dilihat pada rc.conf pada folder ranger yang ada di .config.

Sumber:
 - https://gist.github.com/TaipanRex/5db9a19304743fe6367b9ef291d2b69b
