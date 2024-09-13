### DockerRun
```sh
sh scripts/build.sh && exit # Сборка проекта
```
```sh
sh scripts/start.sh && exit # Запуск проекта
```
```sh
sh scripts/stop.sh && exit # Остановка проекта
```
<details class="block"><summary>Docker mirrors</summary>

- Добавить зеркала для Docker (Windows: `%USERNAME%\.docker\daemon.json`)
```text
"registry-mirrors": [
    "https://huecker.io",
    "https://dockerhub.timeweb.cloud",
    "https://daocloud.io",
    "https://mirror.gcr.io"
]
```

</details>

### Homeworks
<details class="block"><summary>lesson 1</summary>

![lesson_1](screenshots/lesson_1.png)

</details>
<details class="block"><summary>lesson 2</summary>

[lesson_2 commit](https://github.com/nikita242114/php_laravel_hw/commit/b31b809c815c542f0f3371c97fde2c3d00463670)

</details>
<details class="block"><summary>lesson 3</summary>

![lesson_3](screenshots/lesson_3.png)
[lesson_3 commit](https://github.com/nikita242114/php_laravel_hw/commit/75eabeec02bfb34a9cad59eaf7972df0b5e4bebe)

</details>
<details class="block"><summary>lesson 4</summary>

[lesson_4 commit](https://github.com/nikita242114/php_laravel_hw/commit/b5dacb198993aefa6b8fb248dbc1b3fe42381260)

</details>
<details class="block"><summary>lesson 5</summary>

[lesson_5 commit](https://github.com/nikita242114/php_laravel_hw/commit/8045ef7959eef803ac6e5fee2b5332c9d8a870dd)

</details>
<details class="block"><summary>lesson 6</summary>

[lesson_6 commit](https://github.com/nikita242114/php_laravel_hw/commit/5c416ff7b2cd9abca908a68ff3b90c9911f83f98)

</details>
<details class="block"><summary>lesson 7</summary>

[lesson_7 commit](https://github.com/nikita242114/php_laravel_hw/commit/62af5e336f5b81debdec2f91dbad324c0c86ec83)

</details>
<details class="block"><summary>lesson 8</summary>

[lesson_8 commit](https://github.com/nikita242114/php_laravel_hw/commit/236426fef39336bd1e20e88e46df9f74ca0ea1f1)

</details>
<details class="block"><summary>lesson 9</summary>

[lesson_9 commit](https://github.com/nikita242114/php_laravel_hw/commit/dcd11b77149602b9dd35649fab250ed070322726)

</details>
<details class="block"><summary>lesson 10</summary>

[lesson_10 commit](https://github.com/nikita242114/php_laravel_hw/commit/93c0784068f910bdbbdec9d1f99693f6c4877f1d)
```console
php artisan queue:listen
php artisan schedule:work
```

</details>
<details class="block"><summary>lesson 11</summary>

[lesson_11 commit](https://github.com/nikita242114/php_laravel_hw/commit/8a449c2b55e28feca758c144ba3df21cbd31daa6)
```console
docker exec -it laravel bash
npm i
nmp run build
```

</details>
<details class="block"><summary>lesson 12</summary>

[lesson_12 commit](https://github.com/nikita242114/php_laravel_hw/commit/1fca2e25f85b3c622826367f0a927cc1d213dbef)
```console
docker exec -it laravel bash
npm i
nmp run build
```

</details>
<details class="block"><summary>lesson 13</summary>

[lesson_13 commit](https://github.com/nikita242114/php_laravel_hw/commit/43dae5e40a02caa4da68c646440074313605fad3)
```console
docker exec -it laravel bash
php artisan db:seed
npm i
nmp run build
```

- Index: ![lesson_13_index](screenshots/lesson_13/index.png)
- Show: ![lesson_13_show](screenshots/lesson_13/show.png)
- Store: ![lesson_13_store](screenshots/lesson_13/store.png)
- Update: ![lesson_13_update](screenshots/lesson_13/update.png)
- Destroy: ![lesson_13_destroy](screenshots/lesson_13/destroy.png)

</details>
<details class="block"><summary>lesson 14 (Промежуточная аттестация)</summary>

[lesson_14 commit](https://github.com/nikita242114/php_laravel_hw/commit/d8544cf8c2929f14729786f3524f592aa12daf07)
```console
docker exec -it laravel bash
php artisan db:seed
npm i
nmp run build
```

</details>

### <div class="hidden">Other</div>
<details class="block hidden"><summary>Стили для IDE</summary>

<style>
h1, h2, h3, h4, h5, h6 {
    font-weight: 800;
    margin: 0 0 10px;
    padding: 20px 0 10px;
}
.block {
    margin: 0 0 0 1em;
    padding: 0 0 1em;
}
.block > summary {
    margin: 0 0 0 -1em;
    font-weight: bold;
    cursor: pointer;
}
.block pre {
    border-radius: 10px;
    margin: 10px 0;
    padding: 0.8em 1em;
}
.block pre + pre {
    margin: -8px 0 10px;
}
.hidden {
  display: none;
}
</style>

</details>
