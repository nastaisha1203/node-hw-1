# Отримуємо і виводимо весь список контактів у вигляді таблиці (console.table)

node index.js --action="list" https://ibb.co/MRgd7Lq

# Отримуємо контакт по id

node index.js --action="get" --id=5 https://ibb.co/PMxM5Qt

# Додаємо контакт

node index.js --action="add" --name="Mango" --email="mango@gmail.com" --phone="322-22-22" https://ibb.co/j8BrMPQ

# Видаляємо контакт

node index.js --action="remove" --id=3 https://ibb.co/jVnTN6K
