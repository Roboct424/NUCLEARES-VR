# NUCLEARES-VR
*ВР мод для игры NUCLEARES*
Мод создан для добавления в игру NUCLEARES поддержки SteamVR. Данный мод добавляет стереоскопическое зрение и 3DOF отслеживание шлема, что позволяет оглядываться в мире игры.
В планах добавить поддержку 6DOF отслеживания шлема и адаптировать интерфейс игры под использование в ВР.
Для работы мода требуется установленный клиент Steam и SteamVR.

Интеграция мода:
1. Установите [Rai-pal](https://github.com/Raicuparta/rai-pal.git)
2. Откройте программу `Rai-pal`
3. Нажмите `Add game` и кликните по центру открывшегося окна
4. В проводнике укажите путь к исполняемому файлу игры (Nucleares.exe)
5. В открывшимся окне нажмите `install` напротив `Beplnex` и `UUVR`
6. После успешной установки один раз запустите игру с помощью кнопки `Run Game Executable` для создания конфигурационных файлов
7. Закройте игру
8. Откройте в проводнике директорию игры
9. Из корня игры перейдите в директорию `/Nucleares_Data/`
10. Скопируйте туда папки `Plugins` и `UnitySubsystems` из этого репозитория
11. В `Rai-pal` нажмите на 3 точки напротив `UUVR` и в открывшейся плашке нажмите `Edit Mod Config`
12. Выберите открыть с помощью блокнота
13. Найдите строку `Camera Tracking Mode = RelativeTransform` и замените на `Camera Tracking Mode = Absolute`
14. Сохраните изменения
15. Запустите игру кнопкой `Run Game Executable`

Поддержать автора:

[![Поддержать через ЮMoney](https://img.shields.io/badge/Поддержать-ЮMoney-8B3FFD?style=for-the-badge&logo=yoomoney&logoColor=white)](https://yoomoney.ru/quickpay/fundraise/button?billNumber=1JHB9MVI77E.260808)
