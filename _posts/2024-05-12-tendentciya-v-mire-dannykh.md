---
title:  "Тенденция в мире данных"
# author: 'Владимир Юсупов'
keywords: инженер-аналитик, analytics engineer, инженер по обработке данных, data engineer, аналитик данных, data analyst, BI-консультант, специализация в разработке хранилищ данных, специализация в мире данных
sidebar: general_sidebar
published: true
permalink: tendentciya-v-mire-dannykh.html
summary: ""
toc: false
lang: "ru"
tags: []
---

Мир данных уже не тот. Как и всё вокруг нас меняется с немыслимой скоростью, мир данных очень сильно изменился за последние несколько лет. Если 10–15 лет назад тенденция была такова, что от специалиста требовалось наличие широкого спектра навыков, то ситуация поменялась кардинальным образом – сейчас в тренде узкая специализация. Постараюсь пояснить на своём примере из сферы Business Intelligence (BI).

<!--more-->

Когда я начинал свой путь BI-консультанта в 2009 году, то мы выполняли весь комплекс задач: 
- проектирование хранилища, 
- подготовка данных в системах-источниках (по крайней мере, формирования требований для экспорта данных), 
- загрузка данных в хранилище, 
- преобразование данных по заданной бизнес-логике, 
- разработка витрин, 
- формирование отчётности и дашбордов, 
- обучение пользователей и т.д.

Что же мы видим сейчас? 

Весь объём работы, который выполнял раньше один BI-консультант (или BI-разработчик), разделён, как минимум, на «троих»:
- инженер по обработке данных (data engineer), 
- инженер-аналитик (analytics engineer), 
- аналитик данных (data analyst).

Сравним все эти роли относительно основных задач по разработке хранилища данных.

<table style="border: 1px solid #ddd; border-collapse: collapse; text-align: left; width: 100%;">
    <caption style="color: #6c6c6c; text-align: right;">Специалисты мира данных</caption>
    <colgroup>
    <col width="33%" />
    <col width="33%" />
    <col width="33%" />
    </colgroup>
    <thead>
        <tr class="header">
            <th style="border: 1px solid #ddd; text-align: left; padding: 15px;">Инженер по обработке данных (data engineer)</th>
            <th style="border: 1px solid #ddd; text-align: left; padding: 15px;">Инженер-аналитик (analytics engineer)</th>
            <th style="border: 1px solid #ddd; text-align: left; padding: 15px;">Аналитик данных (data analyst)</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td markdown="span" style="border: 1px solid #ddd; text-align: left; padding: 15px;">
                - Настраивает и обеспечивает бесперебойную загрузку данных (интеграцию) из систем-источников в хранилище<br>
                - Сосредотачивается на поддержке инфраструктуры доставки данных, а не на анализе самих данных
            </td>
            <td markdown="span" style="border: 1px solid #ddd; text-align: left; padding: 15px;">
                - Проектирует (моделирует) хранилище данных<br>
                - Преобразует данные из систем-источников по заданной бизнес-логике для проведения анализа конечными пользователями (аналитиками и/или бизнес-пользователями)<br>
                - Погружается как в техническую сторону обработки данных, так и в потребности бизнеса<br>
                - Оформляет и поддерживает документацию по хранилищу
            </td>
            <td markdown="span" style="border: 1px solid #ddd; text-align: left; padding: 15px;">
                - Отвечает за визуализацию данных (отчёты, дашборды)<br>
                - Тесно взаимодействует с бизнес-пользователями<br>
                - Глубоко погружается в потребности бизнеса
            </td>
        </tr>
    </tbody>
</table>

Понятно, что такое разделение очень условное. Если говорить про российские компании, то не везде все эти роли вообще есть, а если и есть, то часто имеют другие названия. Но курс на такое разделение обязанностей существует.

Тем не менее, инженеры по обработке данных и аналитики всем хорошо известны и у всех на слуху, а вот инженеры-аналитики появились буквально несколько лет назад. Если не ошибаюсь, то эта профессия родилась в 2018 году, благодаря компании dbt Labs. И вот как раз про эту новую роль в мире данных и продукт компании dbt Labs я хочу немного рассказать и порассуждать в нескольких последующих заметках.

{% include links.html %}