•	добавление и удаление друзей;

```text
POST "vk/main/create-user
DELETE "vk/main/remove-user
```

•	просмотр друзей пользователя;

```text
GET "vk/main/friends/
```

•	просмотр анкеты пользователя;

```text
GET "vk/main/info/
```

•	публикация поста в ленту;

```text
POST "vk/main/create-post/
```

•	загрузка медиа файлов для постов;

```text
POST "vk/main/create-post/?post-id={id}/
```

•	просмотр ленты постов (домашней и пользователей);

```text
GET "vk/main/desc
```

```text
GET "vk/user/?id={id}/desc
```

•	просмотр диалогов и чатов пользователя;

```text
GET "vk/main/dialogs
```

```text
GET "vk/main/chats
```

•	отправка и чтение сообщений в диалогах и чатах.

```text
POST "vk/main/chats/?id_chat={id_chat}/
```

```text
GET "vk/main/chats/?id_chat={id_chat}/
```
------------------------------------
```text
POST "vk/main/dialogs/?id_dialogs={id_dialogs}/
```

```text
GET "vk/main/dialogs/?id_dialogs={id_dialogs}/
```
