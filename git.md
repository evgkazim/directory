#### —оздание локального репозитори€

<code>git init</code>

####  лонирование удаленного репозитори€ в локальный

<code>git clone https://github.com/evgkazim/directory.git </code>

####  лонирование локального репозитори€ на удаленный

+ —в€зываем локальный репозиторий с удаленным <br>
  <code>git remote add origin https://github.com/evgkazim/directory.git </code><br>
+ ¬ерифицируем что удаленный репозиторий св€зан с нашим <br>
  <code>git remote -v</code><br>
+ ѕубликуем ветку master на удаленном репозитории <br>
  <code>git push -u origin master</code><br>

#### «адаем им€ пользовател€ и электронную почту

+ √лобально дл€ всех проектов текущего пользователь€ <br>
  <code>git config Цglobal user.name УuserФ</code><br>
  <code>git config Цglobal user.email user@example.com</code><br>
+ ƒл€ конкретного проекта (эти настройки переопредел€т глобальные) <br>
  <code>git config Цlocal user.name УuserФ</code><br>
  <code>git config Цlocal user.email user@example.com</code><br>

#### ќсновные функции
* git fetch - используетс€ дл€ скачивани€ изменений из удаленного или локального репозитори€ в свой локальный репозиторий.



