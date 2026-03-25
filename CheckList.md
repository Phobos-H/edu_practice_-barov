  ЧАСТЬ №1
Шаг 1 создание топологии
<img width="1336" height="581" alt="Снимок экрана 2026-03-19 152155" src="https://github.com/user-attachments/assets/b1348557-609e-4a36-b2b6-8973fbf9aa39" />

Шаг 2 создание MOTD на роутерах
<img width="474" height="73" alt="image" src="https://github.com/user-attachments/assets/7dc5a3cc-2fea-4de9-bdd4-5b783f586bb5" />

Шаг 3 Переименовывание утсройств
<img width="247" height="58" alt="image" src="https://github.com/user-attachments/assets/c1946dae-893e-4c96-8226-8156eb9266ef" /> (r1)
<img width="246" height="71" alt="image" src="https://github.com/user-attachments/assets/39c5785b-1613-4e2b-bc66-0fe252948338" />(sw0)

Шаг 4 Настроить доменное имя на r1 sw0/1
<img width="313" height="15" alt="image" src="https://github.com/user-attachments/assets/972b91f3-1d51-41aa-aef4-7c8ab441125a" />
<img width="315" height="14" alt="image" src="https://github.com/user-attachments/assets/ea5409e1-2e6d-4fc9-b2e4-99a58a4c83b4" />
<img width="316" height="9" alt="image" src="https://github.com/user-attachments/assets/7d21fc21-7a30-4ec6-b2bc-b87ef571b604" />

Шаг 5 Создание VLAN 2,3,4 (без имён) на sw0/1
<img width="222" height="43" alt="image" src="https://github.com/user-attachments/assets/dfba7dc3-8ec8-4421-888f-53df330cef57" />

Шаг 6 Назначить порты vlan
<img width="344" height="185" alt="image" src="https://github.com/user-attachments/assets/4e83c32e-8139-4a74-8361-8dff496577e2" />
<img width="333" height="129" alt="image" src="https://github.com/user-attachments/assets/47dcfa13-6423-425c-a694-143b52dd9eaa" />

Шаг 7 Ethechannel между sw0 и sw1
<img width="421" height="296" alt="image" src="https://github.com/user-attachments/assets/33e91ba5-170d-4769-951d-59c5e677b42d" />
<img width="622" height="433" alt="image" src="https://github.com/user-attachments/assets/009329bd-c6e4-41fa-8fe5-19952bbce165" />

Шаг 8-9 Management interface на switch0 и sw1
<img width="428" height="98" alt="image" src="https://github.com/user-attachments/assets/2f215f06-5bc7-45bd-bb8d-980a19672f44" />
<img width="523" height="190" alt="image" src="https://github.com/user-attachments/assets/2c5c1510-18d8-4fbb-9e39-85757b41e800" />

Шаг 10 Настройка SSHv2 на sw0/1
<img width="483" height="194" alt="image" src="https://github.com/user-attachments/assets/c0b7dc5d-695d-4cad-a9e0-706660b4c680" />
<img width="486" height="206" alt="image" src="https://github.com/user-attachments/assets/a6daf23f-3623-4d5f-af2c-135b3096fbfb" />

Шаг 11 Настройка транка на порту f0/24 Sw0
<img width="351" height="56" alt="image" src="https://github.com/user-attachments/assets/2b332e65-cc72-40bf-94c1-3c923adbb8e8" />

Шаг 12 MOTD для sw0/1
<img width="397" height="13" alt="image" src="https://github.com/user-attachments/assets/595ced3d-8d68-4bd3-86ec-57c0fd9b0984" />
<img width="391" height="15" alt="image" src="https://github.com/user-attachments/assets/318e75c6-59ec-4627-b9c1-7bfb7aabb2f1" />

Шаг 13 Настройка портов f0/2, /03, /04 на обоих sw
<img width="529" height="375" alt="image" src="https://github.com/user-attachments/assets/a31c51a8-e54a-43e1-b7f6-d88b33b7d757" />
<img width="522" height="236" alt="image" src="https://github.com/user-attachments/assets/62484841-4099-41cf-bcdd-4118543bd247" />

Шаг 14 Защита консоли
<img width="271" height="30" alt="image" src="https://github.com/user-attachments/assets/d168add6-9d4a-418f-8571-d8de2de756f4" />
<img width="271" height="26" alt="image" src="https://github.com/user-attachments/assets/bd4c67c3-ba0a-4b56-ba31-50783173ee2e" />

Шаг 15 Отключение таймаута и логирования в консоль + буфер
<img width="306" height="154" alt="image" src="https://github.com/user-attachments/assets/eb39258c-fb0f-4013-bb4d-74c7548e91de" />
<img width="306" height="135" alt="image" src="https://github.com/user-attachments/assets/c52050eb-02d0-4f8f-9c42-b38a1ede89ff" />

  
  ЧАСТЬ 2

Шаг 1 Ip адрес на интерфейсе f0/1 роутера r1
<img width="597" height="230" alt="image" src="https://github.com/user-attachments/assets/04586fe4-4ed5-4b3e-8bf8-f68b9c124ed2" />

Шаг 2 Маршрутизация между VLAN на r1
<img width="621" height="510" alt="image" src="https://github.com/user-attachments/assets/7ead73bc-d8f6-4b53-94f3-4725e77a5f67" />
<img width="628" height="338" alt="image" src="https://github.com/user-attachments/assets/d8eb906d-0b77-41b2-8db9-3910dbe40733" />

Шаг 3 Настройка DHCP сервера на R1
<img width="444" height="321" alt="image" src="https://github.com/user-attachments/assets/729b3771-0e79-4946-88e4-5887423b9a25" />
Шаг 4 Проверка связи
<img width="591" height="447" alt="изображение" src="https://github.com/user-attachments/assets/9fe64825-694d-4459-b7b7-32643c06f195" />

  ЧАСТЬ 3
Шаг 1 Переименование и вкл MLS
<img width="206" height="93" alt="изображение" src="https://github.com/user-attachments/assets/15420b00-3ab2-4e91-b05e-641bd8057fdb" />
<img width="119" height="38" alt="изображение" src="https://github.com/user-attachments/assets/fc1fc27c-74f1-440d-a9cf-7f3319594a2c" />

Шаг 2 Создать VLAN 100 и 200
<img width="166" height="194" alt="изображение" src="https://github.com/user-attachments/assets/40db4f8a-c507-4595-9bfe-bf439f593469" />

Шаг 3 Назначь порты в VLAN
<img width="289" height="268" alt="изображение" src="https://github.com/user-attachments/assets/da73014e-c2c3-4a2e-88fc-f3ae0483fca8" />

Шаг 4 Настрить SVI для VLAN 100 и 200
<img width="395" height="272" alt="изображение" src="https://github.com/user-attachments/assets/2c03207d-fb4e-434e-b55e-0a491bbde4cf" />

Шаг 5 — Настрой интерфейсы 3-го уровня
<img width="400" height="489" alt="изображение" src="https://github.com/user-attachments/assets/ac26cda4-17f0-4f2f-a65c-9aa082a98723" />

Проверка
<img width="856" height="579" alt="изображение" src="https://github.com/user-attachments/assets/10207678-bc08-4ce3-809c-1c2c9d1c1aca" />

  ЧАСТЬ 4
  
Шаг 1 — IP-адреса на R2 и R3
<img width="322" height="289" alt="изображение" src="https://github.com/user-attachments/assets/6f6f5629-4346-4505-87a6-ded7eb5360c1" />

<img width="330" height="304" alt="изображение" src="https://github.com/user-attachments/assets/d4fc7462-9ff8-42e0-bd8e-c1765bf8160b" />

Шаг 2 — HSRP на интерфейсе f0/0 (R2 и R3)
<img width="238" height="192" alt="изображение" src="https://github.com/user-attachments/assets/3172a41c-d295-46bf-b9e0-02335ff0c8ba" />

<img width="245" height="163" alt="изображение" src="https://github.com/user-attachments/assets/0c2d26bf-2df9-4ed5-9e08-e1b1f0dcb1ff" />

Шаг 3 — Проверка HSRP
<img width="761" height="108" alt="изображение" src="https://github.com/user-attachments/assets/26c4a110-cf73-4c75-9b79-c1fbaeed0f7b" />

<img width="761" height="110" alt="изображение" src="https://github.com/user-attachments/assets/fc061739-ef49-408e-a03f-3c7b2a4269f1" />

  ЧАСТЬ 5

Шаг 1 EIGRP AS 100
R1<img width="317" height="288" alt="изображение" src="https://github.com/user-attachments/assets/e8381e55-d212-4ea2-9547-61f955917a46" />

R2<img width="336" height="189" alt="изображение" src="https://github.com/user-attachments/assets/436fa52a-ce28-41cb-b76f-7064bd7013c6" />

R3<img width="333" height="196" alt="изображение" src="https://github.com/user-attachments/assets/687b222e-cabc-4c40-8ba1-afa7da65113c" />

MLS<img width="344" height="305" alt="изображение" src="https://github.com/user-attachments/assets/a34cb104-2250-4829-b78b-fc6b5a60c72d" />

Шаг 2 Проверка SSH с сервера 10.0.0.0/8 к SW1 и SW2

<img width="745" height="112" alt="изображение" src="https://github.com/user-attachments/assets/9d6b2a64-f7e0-4133-8fe4-6d7202aae5f3" />

Шаг 3 настройка сервера
<img width="617" height="225" alt="изображение" src="https://github.com/user-attachments/assets/58ecda63-efe2-47a6-8ccd-5a3700515ea5" />

<img width="525" height="317" alt="изображение" src="https://github.com/user-attachments/assets/6474af0f-e9a4-4eb4-ad41-2ef88534beb4" />


  ЧАСТЬ 6 
Шаг 1 ACL для веб-сервера
<img width="850" height="270" alt="изображение" src="https://github.com/user-attachments/assets/31acf718-9ff5-4887-b471-94e9119476da" />

Шаг 2. Запрет ping на R2 и R3
R2<img width="652" height="206" alt="изображение" src="https://github.com/user-attachments/assets/5679757a-97c7-4c16-94c2-3ab12d70a2ec" />

R3<img width="635" height="203" alt="изображение" src="https://github.com/user-attachments/assets/4684cb66-7dee-4752-8293-dab88ac6d487" />

Проверка

<img width="718" height="359" alt="изображение" src="https://github.com/user-attachments/assets/8abf0d08-343a-4c9a-8b37-4b4d5e83f4a1" />
<img width="711" height="371" alt="изображение" src="https://github.com/user-attachments/assets/3cb9f62c-e2bb-4166-bcb5-04151f091e0f" />

  ЧАСТЬ 7
