---
layout: multipage-overview
title: Обзор
scala3: true
partof: scala3-book
overview-name: "Scala 3 — Book"
type: section
description: На этой странице представлен обзор предыдущего раздела 'Функции'.
language: ru
num: 34
previous-page: fun-write-method-returns-function
next-page:
---

Это была длинная глава, поэтому давайте рассмотрим ключевые моменты, которые мы прошли.

Функция высшего порядка (HOF) часто определяется как функция, 
которая принимает другие функции в качестве входных параметров или возвращает функцию в качестве своего значения. 
В Scala это возможно, потому что функции являются объектами первого класса.

Двигаясь по разделам, сначала вы узнали:

- Как писать анонимные функции в виде небольших фрагментов кода.
- Как передать их десяткам HOF (методов) в классах коллекций, т.е. таким методам, как `filter`, `map` и т.д.
- Как с помощью этих небольших фрагментов кода и мощных HOF создавать множество функций с помощью небольшого кода.

Изучив анонимные функции и HOF, вы узнали:

- Функциональные переменные — это просто анонимные функции, привязанные к переменной.

Увидев, как быть потребителем HOF, вы увидели, как стать создателем HOF. 
В частности, вы узнали:

- Как писать методы, принимающие функции в качестве входных параметров
- Как вернуть функцию из метода

Полезным побочным эффектом этой главы является то, 
что вы увидели много примеров того, как объявлять сигнатуры типов для функций. 
Преимущество этого заключается в том, что вы используете один и тот же синтаксис 
для определения параметров функций, анонимных функций и функциональных переменных, 
а также становится легче читать Scaladoc для функций высшего порядка, таких как `map`, `filter` и другие.
