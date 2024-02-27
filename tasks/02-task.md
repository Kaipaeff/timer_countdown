# Задание 2. Countdown
Реализуем в виде отдельного компонента Countdown.

Блок ввода начального времени (выносим в отдельный компонент):
- Можно установить время с помощью двух полей (минуты и секунды) или слайдера (компонент Slider) - от 0 до 60 минут. Когда перемещаешь слайдер - он должен изменять время с шагом 15 секунд. Ввод с клавиатуры должен ограничиваться 720 минутами. Слайдер и текстовые инпуты должны быть связаны друг с другом (менять значение текстовых, если двигаем слайдер и наоборот)
- После запуска поля блокируются до сброса таймера

Блок результата:
- Отображается время в минутах и секундах до конца обратного отсчета.
- Отображается визуальный прогресс (через компонент Progress), сколько в процентах от начального времени прошло
- По окончанию таймера проигрывается звуковой сигнал (на ваше усмотрение)

Блок управления:
- 2 кнопки: запустить/пауза и сброс

## Создание компоненты Countdown

Реализуем в виде отдельного компонента Countdown.  

Блок ввода начального времени (выносим в отдельный компонент):
- Можно установить время с помощью двух полей (минуты и секунды) или слайдера (компонент Slider) - от 0 до 60 минут. Когда перемещаешь слайдер - он должен изменять время с шагом 15 секунд. Ввод с клавиатуры должен ограничиваться 720 минутами. Слайдер и текстовые инпуты должны быть связаны друг с другом (менять значение текстовых, если двигаем слайдер и наоборот)
- После запуска поля блокируются до сброса таймера

Блок результата:
- Отображается время в минутах и секундах до конца обратного отсчета.
- Отображается визуальный прогресс (через компонент Progress), сколько в процентах от начального времени прошло
- По окончанию таймера проигрывается звуковой сигнал (на ваше усмотрение)

Блок управления:
- 2 кнопки: запустить/пауза и сброс

## Требования
1. Подключенный prettier, eslint и публикация на github pages.
2. Компоненты должны быть оптимизированы
3. Используем Styled Components (MUI)
4. Не должно быть ошибок в eslint