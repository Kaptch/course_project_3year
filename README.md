# Изоморфизм тривиального расслоения и семейства типов
# Equivalence of family of types and fibration

Работа выполнена на основе [MMCS SFEDU thesis](https://github.com/mmcs-sfedu/mmcs_sfedu_thesis)

## Аннотация

Системы верификации --- программы, разработанные для формализации доказательств на компьютере. Большая часть из них базируется на теории типов, которая делится на множество подвидов.
Гомотопическая теория типов (Homotopy type theory, HoTT) выделяется тем, что базируется на связи между теорией типов и теорией гомотопий. Эта область лежит в основе Унивалентных оснований математики (Univalent Foundation, UF) --- попытки формализовать математику, используя в качестве фундамента не множества, а гомотопические типы, а также высшие индуктивные типы (Higher Inductive Types, HIT). Этот подход интересен тем, что позволяет работать с гомотопической теорией, используя синтетический метод, то есть, не опираясь на более базовые примитивы, как, например, множества.

В данный момент существует несколько систем верификации, которые поддерживают гомотопическую теорию типов нативно или благодаря расширениям, но эта поддержка обеспечивается различными наборами примитивных операций, для некоторых из которых существует совсем мало примеров.
В работе рассматривается формализация нетривиального расслоения над окружностью --- ленты Мёбиуса, а также портирование доказательства изоморфизма тривиальных расслоений и зависимых типов на верификатор доказательств Arend. Это доказательство показывает, что базовые теоретико-типовые конструкции соответствуют гомотопическим.

Код, которому посвящена данная работа, можно найти на GitHub в репозитории организации Groupoid Infinity. Доказательство выполнено в файле [Fiber.ard](https://github.com/groupoid/arend/blob/master/src/Fiber.ard), формализация ленты Мёбиуса --- в файле [Moebius.ard](https://github.com/groupoid/arend/blob/master/src/Moebius.ard).

## Annotation

In this paper I report on formalizing a Moebius strip and on porting a proof of equivalence of fibration and family of types using the proof assistant Arend. The former task is a demonstration of basic Arend features and the latter is an evidence of a correspondence between basic constructions of homotopy and type theories. The code can be found in Arend Groupoid Infinity repository (moebius strip: [Moebius.ard](https://github.com/groupoid/arend/blob/master/src/Moebius.ard), proof: [Fiber.ard](https://github.com/groupoid/arend/blob/master/src/Fiber.ard).

## Contacts

mail: kaptch@gmail.com
tg: @kaptch
