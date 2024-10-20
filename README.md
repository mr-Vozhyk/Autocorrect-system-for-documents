<div id="header" >
 <img src="https://github.com/mr-Vozhyk/Autocorrect-system-for-documents/blob/main/icon/%D0%A1%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D0%B0_%D0%B4%D0%BE%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9_%D0%B0%D0%B2%D1%82%D0%BE%D0%B7%D0%B0%D0%BC%D0%B5%D0%BD%D1%8B.png" width="150"/>
</div>

# Система дополненной автозамены – кратное ускорение создания документов

## Введение
В процессе подготовки внутренних правовых актов и отчетности я обратил внимание на множество повторяющихся формулировок и устойчивых выражений. 

Предварительный анализ показал, что автоматизация заполнения этих блоков значительно сократит время на подготовку документов.

**Результаты - создание внутренней документации ускорилось в 2,5 раза**.

👁️‍🗨️[Ссылка на полное pdf-описание проекта](https://github.com/mr-Vozhyk/Autocorrect-system-for-documents/blob/main/%D0%92%D0%BD%D0%B5%D0%B4%D1%80%D0%B5%D0%BD%D0%B8%D0%B5%20%D1%81%D0%B8%D1%81%D1%82%D0%B5%D0%BC%D1%8B%20%D0%B4%D0%BE%D0%BF%D0%BE%D0%BB%D0%BD%D0%B5%D0%BD%D0%BD%D0%BE%D0%B9%20%D0%B0%D0%B2%D1%82%D0%BE%D0%B7%D0%B0%D0%BC%D0%B5%D0%BD%D1%8B.pdf)

## Краткое описание проекта
### Реализация

Проанализировав документы, я составил список наиболее часто встречающихся словосочетаний и блоков текста. 

Затем я создал таблицу с парами "ключ-значение" для добавления **```в базу автозамены Microsoft Office```**. 

В качестве "ключа" использовались сокращения от словосочетаний (кодовые слова) или названия блоков (скриптов), а в качестве "значения" – их полная расшифровка или сам скрипт.

### Практика применения

Система дополненной автозамены активно используется и актуализируется работниками управления организации. 

После дополнений/актуализации, "системный" файл с данными автозамены Microsoft Office может обновляться на всех необходимых устройствах, не требуя ручного ввода пар на каждом конкретном устройстве.

### Результаты
Внедренная система дополненной автозамены улучшила ряд показателей:
1. **```создание внутренней документации ускорилось в 2,5 раза```**
- это подтверждается как практическими измерениями (сравнение времени, затраченного на подготовку однотипных документов одним и тем же сотрудником с использованием системы автозамены и без нее), так и теоретическими расчетами (в ряде документов доля сокращений и скриптов составляет более 70%);
2. **```снизилась доля ошибок в именах, должностях и формулировках```**
- ранее ввод данных осуществлялся по памяти и с использованием справочных материалов, что могло приводить к ошибкам из-за неточности ввода или копирования. Теперь система автоматически подставляет правильные данные, обеспечивая точность и сокращая время на ввод;
3. **```расширились возможности по взаимозаменяемости сотрудников при сохранении качества документов```**
- Шаблоны формулировок и блоков позволяют новым исполнителям готовить документы в соответствии с установленными ранее требованиями. Это снижает зависимость от конкретных специалистов и упрощает процесс обучения новых сотрудников.
