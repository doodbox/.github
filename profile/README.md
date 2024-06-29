# DoodBox
<br>
<p align="center">
<img src="https://github.com/doodbox/.github/assets/168820093/15b75e42-f680-4572-ba8a-6005f7a9f538" width="200">
<br>
<i>ouch, im pretty much corny -Marquis Evander Thornevale</i>
</p>

<br>
<br>

---
---

<p align="center">
  https://smkinformatikacbi.sch.id/web/ortu/ajax_edit/1
  https://web.archive.org/web/20240629134525/https://smkinformatikacbi.sch.id/web/ortu/ajax_edit/1
</p>

---
---

```
~ CONTACT ~
083870396203
083172566909
latipharkat48@gmail.com
latipharkat176@gmail.com
latipfb20@gmail.com
latifdev176@gmail.com
muhammadlatifharkat23@gmail.com
omenlatip28@gmail.com
contact@latipharkat.my.id
crackerindo176@gmail.com
```

---
---
<p align="center">
  <code>C:\Users\Latip Harkat\~</code>
</p>

---
---
```
uname: pusatttt,root
id: uid=0(root) gid=0(root) groups=0(root)
banner: 10.6.18-MariaDB
back-end DBMS: MySQL >= 5.0.0 (MariaDB fork)
current user: pusatttt_doodbox@localhost
available databases: information_schema,pusatttt_doodbox
```
---
---
- Database: pusatttt_doodbox
- [13 tables]

| Tables             |
|--------------------|
| ip_address         |
| live_viewers       |
| notification       |
| tbl_admin          |
| tbl_folder         |
| tbl_method         |
| tbl_saldo_user     |
| tbl_user           |
| tbl_vd_information |
| tbl_videos         |
| tbl_withdraw       |
| video_views        |
| wd_ads             |


- Database: pusatttt_doodbox
- Table: video_views
- [5 columns]

| Column   | Type    |
|----------|---------|
| id       | int(11) |
| id_user  | int(11) |
| id_video | int(11) |
| tanggal  | date    |
| views    | int(11) |

- Database: pusatttt_doodbox
- Table: tbl_admin
- [3 columns]


| Column   | Type    |
|----------|---------|
| email    | text    |
| id       | int(11) |
| password | text    |


- Database: pusatttt_doodbox
- Table: notification
- [4 columns]


| Column  | Type    |
|---------|---------|
| id      | int(11) |
| id_user | int(11) |
| message | text    |
| title   | text    |


- Database: pusatttt_doodbox
- Table: ip_address
- [4 columns]


| Column   | Type        |
|----------|-------------|
| id       | int(11)     |
| id_video | int(11)     |
| ip       | varchar(50) |
| tanggal  | date        |


- Database: pusatttt_doodbox
- Table: live_viewers
- [3 columns]


| Column         | Type      |
|----------------|-----------|
| id             | int(11)   |
| user_id        | int(11)   |
| watching_since | timestamp |


- Database: pusatttt_doodbox
- Table: tbl_saldo_user
- [5 columns]


| Column            | Type    |
|-------------------|---------|
| id                | int(11) |
| id_user           | int(11) |
| saldo             | double  |
| total_views       | int(11) |
| views_diskonversi | int(11) |


- Database: pusatttt_doodbox
- Table: tbl_vd_information
- [7 columns]


| Column            | Type        |
|-------------------|-------------|
| size              | varchar(50) |
| id                | int(11)     |
| id_user           | int(11)     |
| id_video          | int(11)     |
| pendapatan        | double      |
| views             | int(11)     |
| views_diskonversi | int(11)     |


- Database: pusatttt_doodbox
- Table: tbl_user
- [6 columns]


| Column     | Type    |
|------------|---------|
| name       | text    |
| email      | text    |
| id_user    | int(11) |
| max_upload | int(11) |
| password   | text    |
| username   | text    |


- Database: pusatttt_doodbox
- Table: tbl_folder
- [5 columns]


| Column      | Type    |
|-------------|---------|
| path        | text    |
| id          | int(11) |
| id_user     | int(11) |
| nama_folder | text    |
| unique_id   | text    |


- Database: pusatttt_doodbox
- Table: tbl_withdraw
- [8 columns]


| Column            | Type    |
|-------------------|---------|
| method            | text    |
| status            | text    |
| atas_nama         | text    |
| id                | int(11) |
| id_user           | int(11) |
| no_rekening       | text    |
| tanggal_penarikan | date    |
| total_penarikan   | int(11) |


- Database: pusatttt_doodbox
- Table: wd_ads
- [4 columns]


| Column  | Type    |
|---------|---------|
| ads     | text    |
| id      | int(11) |
| tanggal | date    |
| total   | int(11) |


- Database: pusatttt_doodbox
- Table: tbl_method
- [5 columns]


| Column    | Type        |
|-----------|-------------|
| method    | varchar(50) |
| number    | text        |
| atas_nama | text        |
| id        | int(11)     |
| id_user   | int(11)     |


- Database: pusatttt_doodbox
- Table: tbl_videos
- [8 columns]


| Column         | Type        |
|----------------|-------------|
| file           | text        |
| path           | text        |
| id_user        | int(11)     |
| id_video       | int(11)     |
| judul          | text        |
| path_folder    | text        |
| tanggal_upload | date        |
| unique_id      | varchar(15) |
