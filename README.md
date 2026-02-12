# kramell
Tables\Actions\DeleteAction::make()
rmdir public\storage
php aartisan storage:link

CEK ENV FILESYSTEM_DISK=public dan di filament ->disk('public')

# nabil
rmdir public\storage /s /q

Kalau masih error, coba dari dalam folder public
cd public
rmdir storage

Cara paling aman (biasanya berhasil 💯)
Tutup VS Code
Buka Command Prompt sebagai Run as Administrator
Masuk ke folder project Laravel

Jalankan:
rmdir public\storage
php artisan storage:link
