ЛОКАЛЬНЫЙ ЗАПУСК
в терминале:
cd /Users/agdelesha/CascadeProjects/bulkqr
python3 -m http.server 5500 --bind 0.0.0.0
в браузере http://192.168.31.35:5500/




Локально проверь:
Запуск: python3 -m http.server 5500 --bind 0.0.0.0
Десктоп: http://127.0.0.1:5500/?debug=1
Телефон в той же сети: http://192.168.31.35:5500/?debug=1
Закоммить и запушь:
git status
git add -A
git commit -m "upd: <что поменял>"
git push -u origin main
Подождать 30–120 секунд. Открой: https://agdelesha.github.io/bulkqr/


git status
git add -A
git commit -m "upd: теперь квадратная форма вместо круглой"
git push -u origin main