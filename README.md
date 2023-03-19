## Installation:

Gunakan: `sudo ./install.sh [OPTIONS...]`

```
  -t, --tema      varian tema              [tela|vimix|stylish|whitesur]       (default tela)
  -i, --ikon      varian ikon              [color|white|whitesur]              (default color)
  -s, --layar     varian tampilan layar     [1080p|2k|4k|ultrawide|ultrawide2k] (default 1080p)
  -r, --hapus     hapus tema               [tela|vimix|stylish|whitesur]       (harus menambahkan opsi nama tema, default tela)

  -b, --boot      pasang tema ke '/boot/grub' atau '/boot/grub2'
  -g, --generate  bukan menginstal tetapi menghasilkan tema ke direktori yang dipilih       (harus menambahkan direktori Anda)

  -h, --help      Menampilkan bantuan
```

_Untuk Resolusi 1080p itu background nya anime look yah..., kalo untuk resolusi lain itu beda dari 1080p_

#### Hanya Untuk Linux System.

### Examples:

- Pasang tema tela dengan resolusi 2k:

```sh
sudo ./install.sh -t tela -s 2k
```

- Pasang tema Tela ke /boot/grub/themes:

```sh
sudo ./install.sh -b -t tela
```

- Menghapus Tela theme:

```sh
sudo ./install.sh -r -t tela
```

### Config Background

- Di dalam root folder ada backgrounds, ganti dengan background kamu sendiri, dengan nama yang sama seperti defaultnya

_Good Luck!!_
