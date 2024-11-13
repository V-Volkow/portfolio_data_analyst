# Исследование российского кинопроката
[Ссылка на проект](https://github.com/V-Volkow/portfolio_data_analyst/blob/main/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%80%D0%BE%D1%81%D1%81%D0%B8%D0%B9%D1%81%D0%BA%D0%BE%D0%B3%D0%BE%20%D0%BA%D0%B8%D0%BD%D0%BE%D0%BF%D1%80%D0%BE%D0%BA%D0%B0%D1%82%D0%B0/%D0%98%D1%81%D1%81%D0%BB%D0%B5%D0%B4%D0%BE%D0%B2%D0%B0%D0%BD%D0%B8%D0%B5%20%D1%80%D0%BE%D1%81%D1%81%D0%B8%D0%B9%D1%81%D0%BA%D0%BE%D0%B3%D0%BE%20%D0%BA%D0%B8%D0%BD%D0%BE%D0%BF%D1%80%D0%BE%D0%BA%D0%B0%D1%82%D0%B0.ipynb)
## Цель исследования
Изучить рынок российского кинопроката и выявить текущие тренды. Уделить отдельное внимание фильмам, получившим поддержку от государства.
## Описание
Заказчик этого исследования — Министерство культуры Российской Федерации. <br>
Данные взяты на портале открытых данных Министерства культуры. <br>
В проекте проведена предобработка данных, для повышения качества исследования. Исследование проводилось в 2 этапа. В первом этапе использованы все фильмы и данные о них, а во втором лишь те, которые получили государственную поддержку
## Результаты исследования
Начиная с 2014 года можно наблюдать динамику увеличения более кассовых фильмов, к 2019 году есть фильмы, собравшие 3 млрд в Российском прокате. <br>
    Также и количество фильмов, которые принесли более 100 млн в прокате, увеличивается. В 2014 таких фильмов 10, в 2018 - таких фильмов уже 50.  <br>
  </p>
    
  *Таблица годовых показателей фильмов по сумме и годам*
    
  <table style="border-collapse: collapse; width: 70%; margin-top: 10px;">
    <tr>
      <th style="border: 1px solid #ccc; padding: 5px;">год</th>
      <th style="border: 1px solid #ccc; padding: 5px;">количество фильмов, принесших более 100 млн</th>
      <th style="border: 1px solid #ccc; padding: 5px;">медианная сумма сборов</th>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 5px;">2014</td>
      <td style="border: 1px solid #ccc; padding: 5px;">12</td>
      <td style="border: 1px solid #ccc; padding: 5px;">18 тыс.</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 5px;">2015</td>
      <td style="border: 1px solid #ccc; padding: 5px;">49</td>
      <td style="border: 1px solid #ccc; padding: 5px;">4 млн 28 тыс.</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 5px;">2016</td>
      <td style="border: 1px solid #ccc; padding: 5px;">58</td>
      <td style="border: 1px solid #ccc; padding: 5px;">3 млн 16 тыс.</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 5px;">2017</td>
      <td style="border: 1px solid #ccc; padding: 5px;">43</td>
      <td style="border: 1px solid #ccc; padding: 5px;">7 млн 30 тыс.</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 5px;">2018</td>
      <td style="border: 1px solid #ccc; padding: 5px;">60</td>
      <td style="border: 1px solid #ccc; padding: 5px;">7 млн 29 тыс.</td>
    </tr>
    <tr>
      <td style="border: 1px solid #ccc; padding: 5px;">2019</td>
      <td style="border: 1px solid #ccc; padding: 5px;">56</td>
      <td style="border: 1px solid #ccc; padding: 5px;">4 млн 17 тыс.</td>
    </tr>
  </table>

    
Наибольшее количество фильмов, вышедших в прокат, имеют категорию 16+ и 18+.  
Куда меньше, по количеству, занимают произведения с категорием 6+, однако, практически во все года, они имеют огромные кассовые сборы.  <br>
Что касается спонсируемых государством фильмов, популярны такие жанры, как драмы и комедии. Чем больше бюджет у фильма, тем больше составят сборы в кинопррокате.  
Также по сборам, больше кассовых средств приносят фильмы, полностью спонсируемые государством, а не на какой-либо процент от общего бюджета.
## Используемые библиотеки
- pandas
- matplotlib
- seaborn
- numpy 
