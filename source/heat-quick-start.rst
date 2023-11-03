=================
Quick Start
=================

1. Нажмите `Launch Stack <https://mekstack.ru/project/stacks/>`_

2. | Template Source -> **URL**
   Template URL -> **https://docs.mekstack.ru/_static/heat-quick-start.yaml** -> **Next**

3. После настройки нажмите **Launch**

4. | В `Instances <https://mekstack.ru/project/instances/>`_ появится ваша виртульная машина.
   | Туда можно подлкючиться с помощью SSH.
   | В Ubuntu пользователь ``ubuntu``, в Arch пользователь ``arch``, в Debian пользователь ``debian``.
   Конфигурационный файл vpn возьмите из `vpnaas.mekstack.ru <https://vpnaas.mekstack.ru>`_

5. Пока мы пишем NATaaS, публикация сайтов на виртуальных машинах доступна только по :doc:`quick-start`.

.. note::

   В окне запуска стека поле **Password for user** - это не пароль для виртуальной машины.
