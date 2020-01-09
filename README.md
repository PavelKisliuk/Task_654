# Task_654
https://acmp.ru/index.asp?main=task&amp;id_task=654

Большой концертный зал Байтланда — известное на весь мир место, где мечтают выступать величайшие оперные певцы и певицы. В желающих послушать их выступления, как правило, недостатка нет. Поэтому Министерством культуры Байтланда было принято решение увеличить размеры зала.

Однако это вызвало другую проблему: на задних рядах обновленного концертного зала посетители практически ничего не слышат. Поэтому Инженерный институт предложил проект акустической системы, которая будет состоять из микрофонов, записывающих происходящее на сцене, и динамиков, транслирующих усиленный звук в зал.

В идеальном случае динамики должны достоверно воспроизводить звук, записываемый с микрофонов. На практике этого добиться почти невозможно, так как при текущем уровне развития технологий практически все динамики воспроизводят различные частоты с различной громкостью. Мириться с этим инженеры, однако, не собираются.

В лаборатории удалось измерить АЧХ (амплитудно-частотную характеристику) динамиков и представить ее в следующей форме:

весь диапазон частот, воспроизводимых динамиками, разделен на N последовательных интервалов, нумеруемых от 1 до N;
в i-м интервале известно Ai - значение усредненной по интервалу громкости в децибелах (Прим.: децибел (дБ) — единица измерения громкости).

АЧХ из примера №2 и усилители, которые нужны, чтобы ее «выровнять» на уровне в 4 дБ (5 штук, усилители применяются в порядке от верхних к нижним)
АЧХ динамиков можно править с помощью специальных электронных устройств — усилителей. Усилитель может поднять силу сигнала на всех интервалах с A-го по B-й на 1 дБ, где A, B — произвольные натуральные числа, не превосходящие N, A ≤ B. Из-за особенностей применяемых в устройстве радиодеталей, сила сигнала перед применением усилителя должна быть одинакова на всех интервалах с A-го по B-ой. Так как стоимость усилителя достаточно велика, то их количество должно быть минимально.

Считается, что динамики воспроизводят звук достоверно, если на всех интервалах значение громкости одинаково. Напишите программу, которая вычислит минимальное число усилителей, необходимое для достижения достоверного звучания.
