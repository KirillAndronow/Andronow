Для создания ключа:
    ssh-keygen -t ed25519 -C "почта@.com"
    пароль не нужен
    Текстовый файл - публичный ключ
Дать агенту ключ:
    ssh-add .ssh/название ключа
    ssh -T git@github.com      подключиться к github
Клонировать репозиторий
    git clone git@github.com:username/repository.git