Ну вобщем запустив захват я увидел кучу трафика

<a href="https://ibb.co/NLQcyf2"><img src="https://i.ibb.co/9qzQrBH/image.png" alt="image" border="0"></a>

TCP дефолтный мусорный трафик винды обычное его,UDP похоже идет либо с Дискорда либо с Ютуба

<a href="https://ibb.co/LhDSm1m"><img src="https://i.ibb.co/XkfX1t1/image.png" alt="image" border="0"></a>

<a href="https://ibb.co/bm7ZW2f"><img src="https://i.ibb.co/LRvWkJG/image.png" alt="image" border="0"></a>

что за TLS и STUN не ясно

![](3c107e7ea41584bced6fae5dc9d29fe3_w200.gif)

юзанул я win+r

<a href="https://imgbb.com/"><img src="https://i.ibb.co/tX2qXWR/image.png" alt="image" border="0"></a>

cmd

и вуаля

<a href="https://ibb.co/6Jp39v9"><img src="https://i.ibb.co/G31KYsY/image.png" alt="image" border="0"></a>

пришлось остановить захват что найти в этой куче мусорных пакетов нужные найти

всёровно юзал фильтр по итогу взяв айпи из командной строки 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/485mLzp/image.png" alt="image" border="0"></a>

проанализировав первый пакет внейшний айпи отправки он не показал,показал айпи цели и внутрий айпи компа в домашней сети 

<a href="https://ibb.co/LxQJGdZ"><img src="https://i.ibb.co/Mc8GXkC/image.png" alt="image" border="0"></a>

TTL был равен одному

<a href="https://imgbb.com/"><img src="https://i.ibb.co/qnD3d2J/image.png" alt="image" border="0"></a>

<a href="https://imgbb.com/"><img src="https://i.ibb.co/R2P0j60/image.png" alt="image" border="0"></a>

в заголовке IP содержалось 20 байт 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/k0NkJKW/image.png" alt="image" border="0"></a>

весь пакет весил 106 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/LRG3vQ6/image.png" alt="image" border="0"></a>

значит в поле данных содержалось 86 байт

ну собствено вопросы перед 6 пунктом мне понравились

<a href="https://ibb.co/DKRmLp2"><img src="https://i.ibb.co/HgHRXd8/image.png" alt="image" border="0"></a>

![](tenor.gif)

ну вот и концовка получается не такая уж и большая лаба

(16.09.20)делаю заранее походу по этому и нет заданий хд

значит открыл я сайт барбершупа и отфильтровал трафик

<a href="https://ibb.co/4NBqK2J"><img src="https://i.ibb.co/88FCNbX/image.png" alt="image" border="0"></a>

ну посльку он был открыт последним скорей всего его ip назначения 185.165.123.36 ну и этот пакет я буду анализировать

остальное скорее всего ютьюб

<a href="https://ibb.co/hyCt66z"><img src="https://i.ibb.co/c1x7BBn/image.png" alt="image" border="0"></a>

вот она наша пара 

<a href="https://ibb.co/rQ4LDbB"><img src="https://i.ibb.co/cyDp4bW/image.png" alt="image" border="0"></a>

вот это задание я не очень понял но вроде так 

<a href="https://ibb.co/pJHMPxv"><img src="https://i.ibb.co/syTNP2v/image.png" alt="image" border="0"></a>

т.e это втрой пакет с контентом который прислал сервер

подумав пару минут и перечитав всётаки это первый пакет(наверное)

<a href="https://ibb.co/mcrV221"><img src="https://i.ibb.co/pL6BMMG/image.png" alt="image" border="0"></a>

а ещё я понял что мое заявление что upd трафик это с ютуба не верно

получается это дискорд

![](3c107e7ea41584bced6fae5dc9d29fe3_w200.gif)

тип запроса и версия получаеться 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/Zd2VgHv/image.png" alt="image" border="0"></a>

айпи адрес компа и сервера (айпи компа внутрений опятьже)

<a href="https://imgbb.com/"><img src="https://i.ibb.co/SNvZFdV/image.png" alt="image" border="0"></a>


код состояния http 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/rFwnm0M/image.png" alt="image" border="0"></a>

длина тела сообщения 

<a href="https://imgbb.com/"><img src="https://i.ibb.co/8g7Xjqm/image.png" alt="image" border="0"></a>

хотя это уверености нет(и вообще ласт задание самое непонятное из всей практики)

или вот это

<a href="https://imgbb.com/"><img src="https://i.ibb.co/YXWTP2s/image.png" alt="image" border="0"></a>

ну и поскольку это ласт на этом всё

![](teno.gif)


17.09.20 время доделовать


для изучения я взял сайт http://wforum.heroes35.net/

определить айпи было легко

<a href="https://ibb.co/x1Pvw9y"><img src="https://i.ibb.co/Ht1vRw0/image.png" alt="image" border="0"></a>

<a href="https://ibb.co/CbWFKNW"><img src="https://i.ibb.co/JvCPj0C/image.png" alt="image" border="0"></a>

<a href="https://ibb.co/zmCQm8m"><img src="https://i.ibb.co/fXZqX8X/Screenshot-2020-09-17-13-52-30-730-com-thecrackertechnology-andrax.jpg" alt="Screenshot-2020-09-17-13-52-30-730-com-thecrackertechnology-andrax" border="0" /></a>

получается  Server IP: 208.113.129.154
