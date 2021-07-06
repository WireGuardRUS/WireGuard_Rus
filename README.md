# [WireGuard](https://www.wireguard.com/) для Windows

Это полнофункциональный клиент WireGuard для Windows, использующий Wintun. Это единственный официальный и рекомендуемый способ использования WireGuard в Windows.

## Загрузка &amp; Установка

Если вы пришли сюда, чтобы просто запустить WireGuard для Windows, [на главной странице загрузки есть ссылки] (https://www.wireguard.com/install/). Там вы найдете две вещи:

- [WireGuard Установщик](https://download.wireguard.com/windows-client/wireguard-installer.exe) &ndash; он выбирает самую последнюю версию для вашей архитектуры, загружает ее, проверяет подписи и хэши и устанавливает ее. 
- [Оффлайн пакет MSIs](https://download.wireguard.com/windows-client/) &ndash; он предназначен для системных администраторов, желающих развернуть MSI напрямую. Для большинства конечных пользователей рекомендуется использовать обычный установщик. 

## Documentation

In addition to this [`README.md`](README.md), the following documents are also available:

- [`adminregistry.md`](docs/adminregistry.md) &ndash; A list of registry keys settable by the system administrator for changing the behavior of the application.
- [`attacksurface.md`](docs/attacksurface.md) &ndash; A discussion of the various components from a security perspective, so that future auditors of this code have a head start in assessing its security design.
- [`buildrun.md`](docs/buildrun.md) &ndash; Instructions on building, localizing, running, and developing for this repository.
- [`enterprise.md`](docs/enterprise.md) &ndash; A summary of various features and tips for making the application usable in enterprise settings.
- [`netquirk.md`](docs/netquirk.md) &ndash; A description of various networking quirks and "kill-switch" semantics.

## License

This repository is MIT-licensed.

```text
Copyright (C) 2018-2021 WireGuard LLC. All Rights Reserved.

Permission is hereby granted, free of charge, to any person obtaining a
copy of this software and associated documentation files (the "Software"),
to deal in the Software without restriction, including without limitation
the rights to use, copy, modify, merge, publish, distribute, sublicense,
and/or sell copies of the Software, and to permit persons to whom the
Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING
FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER
DEALINGS IN THE SOFTWARE.
```
