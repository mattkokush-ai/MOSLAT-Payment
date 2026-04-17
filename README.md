# 1. Клонируйте исходный репозиторий с полной историей
git clone --mirror https://github.com/mattkokush-ai/moslat-payments.git moslat-payments.git

# 2. Создайте зеркальный push в новый репозиторий
cd moslat-payments.git
git push --mirror https://github.com/mattkokush-ai/MOSLAT-Payment.git

# 3. Очистите временные файлы
cd ..
rm -rf moslat-payments.git

# 4. Клонируйте новый репозиторий
git clone https://github.com/mattkokush-ai/MOSLAT-Payment.git

cd MOSLAT-Payment
