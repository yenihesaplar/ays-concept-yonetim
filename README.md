# AYS CONCEPT YÖNETİM – Supabase giriş sürümü

1. ZIP içindeki `index.html`, `config.js` dosyalarını GitHub deposunun ana dizinine yükleyin ve eski `index.html` dosyasını değiştirin.
2. Supabase > Project Settings > API Keys bölümünden **Publishable key** değerini kopyalayın.
3. `config.js` dosyasını GitHub'da düzenleyin. `BURAYA_SUPABASE_PUBLISHABLE_KEY` yazan yere publishable key'i yapıştırın.
4. `config.js` değişikliğini kaydedin. GitHub Pages yeniden yayınlanınca siteyi açın.
5. Oluşturduğunuz Supabase kullanıcı e-postası ve şifresiyle giriş yapın.

Project URL config.js içinde önceden ayarlanmıştır: https://etmcdxzyltyllangnzgt.supabase.co

Güvenlik:
- Yalnızca Publishable key (veya eski anon public key) kullanılmalıdır.
- `secret` veya `service_role` anahtarını asla GitHub'a ya da tarayıcı koduna koymayın.
- Bu sürüm yalnızca giriş/çıkış ve demo paneli sağlar; pazaryeri API bağlantısı ve veri işlemleri henüz etkin değildir.
