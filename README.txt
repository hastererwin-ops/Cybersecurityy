CYBERSEC ADMIN PANEL

Login: admin / admin333

Termux:
cd ~/cybersec-web
python -m http.server 8080

Buka http://127.0.0.1:8080

Fitur:
- Dashboard Admin
- Tombol titik tiga (⋮) kanan atas
- Side menu slide dari kanan
- Profile/Account Settings
- HTML Manager: Upload, Preview, Apply, Reset
- Security Center, Hacker Profiles, Activity Logs, System Monitor
- Responsive Android

HTML Manager memakai localStorage. Apply mengubah tampilan dashboard pada browser, bukan menimpa file dashboard.html di Termux. Script/iframe/object/embed dari HTML yang di-apply dihapus saat dimasukkan ke dashboard.
