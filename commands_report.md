Ось коротке пояснення команд Git:

- git init: Ініціалізує новий Git-репозиторій у поточній папці, створюючи приховану директорію `.git`.

- git commit -m "повідомлення": Фіксує зміни в локальному репозиторії з вказаним повідомленням, що описує зміни.

- git push: Надсилає зафіксовані зміни з локального репозиторію до віддаленого (наприклад, на GitHub).

- git add .: Додає всі змінені файли в поточній папці до індексу для наступного коміту.

- git checkout -b "назва-гілки": Створює нову гілку з вказаною назвою та одразу перемикається на неї.

- git remote: Показує список віддалених репозиторіїв, підключених до локального. З опціями (наприклад, `git remote add`) додає віддалений репозиторій.

- git branch: Показує список локальних гілок. З опціями може створювати чи видаляти гілки.

- git push -u origin main: Надсилає локальну гілку `main` до віддаленого репозиторію `origin` і встановлює зв’язок для подальших пушів.

- git config --global user.name "Ваше ім’я": Встановлює глобальне ім’я користувача для всіх Git-репозиторіїв.

- git config --global user.email "you@example.com": Встановлює глобальну електронну пошту користувача для всіх Git-репозиторіїв.