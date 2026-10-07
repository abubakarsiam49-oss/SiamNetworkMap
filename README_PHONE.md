# Siam Network Map — Phone-only APK Build

আপনার PC লাগবে না। ফোন থেকেই GitHub-এ এই project upload করে Actions চালানো যাবে।

## ধাপ
1. GitHub-এ একটি নতুন repository বানান।
2. এই ZIP-এর সব file repository-তে upload করুন।
3. GitHub → Actions → Build APK → Run workflow চাপুন।
4. `api_url`-এ আপনার **HTTPS backend API URL** দিন।
5. Build শেষ হলে Artifacts থেকে `SiamNetworkMap-debug-apk` download করুন।
6. APK ফোনে install করুন।

## গুরুত্বপূর্ণ
- `https://YOUR-DOMAIN.example.com` শুধু placeholder।
- আপনার production backend আগে HTTPS-এ চালু করতে হবে।
- এই starter-এ GPS + OpenStreetMap আছে।
- পরের build-এ real login, database nodes/fibers, multi-point fiber route, customer এবং audit log যুক্ত করা যাবে।
