# F2 FF HUB — telefondan GitHub-a əlavə etmək

## ZIP-i aç
Android-də Fayllar / Files tətbiqində ZIP-i tap, üzərinə toxun və Extract / Çıxart seç.

## GitHub-a yüklə
1. Chrome-da repozitoriyanı aç: https://github.com/fnuruyev5-cloud/F2-FF-HUB
2. GitHub hesabına daxil ol.
3. `Add file` → `Upload files` seç.
4. ZIP-dən çıxan faylları seç: `index.html`, `supabase-config.js`, `README.md`, `.nojekyll` və `supabase` qovluğu.
5. `Commit changes` düyməsinə bas.
6. `Upload files` görünmürsə, Chrome-un ⋮ menyusunda `Desktop site` seç.

## Saytı yayımla
Repo → `Settings` → `Pages` → `Deploy from a branch` → Branch `main` → Folder `/(root)` → `Save`.
Bir neçə dəqiqə sonra: https://fnuruyev5-cloud.github.io/F2-FF-HUB/

## Vacib
Bu layihə mövcud Supabase layihəsinə qoşulmaq üçün hazırlanıb. Əgər cədvəllər artıq Supabase-də yaradılıbsa, `supabase/schema.sql`-i təkrar işə salma. Saytın mesajlaşması Supabase cədvəlləri, RLS siyasətləri və `start_direct_conversation` RPC funksiyasının düzgün qurulmasını tələb edir. GitHub Pages sadəcə saytı yayımlayır.
`supabase-config.js`-dəki publishable key brauzer üçün public açardır; service_role/secret key-i heç vaxt HTML/JS-ə əlavə etmə.
Bu, ilkin versiyadır və rəsmi Garena xidməti deyil.
