<h1>Какими способами можно взаимодействовать между сервером-клиентом в реальном времени?</h2>
<p><I>Based on JavaScript.</I></p>

Давайте вообще начнем с начала, зачем это нужно, где используется и с чем едят. Я буду обьяснять базовые понятия и приводить базовые примеры, <I> куски кода есть в репозитории </I>
Взаимодействие в реальном времени сейчас испольуется почти везде, мессенджеры, комп.игры и прочие приложения, где юзеры контактируют между собой и не только.

Всего есть три вида взаимодействия в real-time:<hr>
  1) Long Pulling
  2) Event Sourcing
  3) WebSocket
  
 Пойдем по порядку, к каждому типу будут примеры, надеюсь они вам помогут.
 <h3>Long Pulling</h3>
 ![image](https://user-images.githubusercontent.com/60395869/125396354-17a1d680-e3b5-11eb-839b-42b254c669cf.png)

