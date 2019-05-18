<h1>mi(Martin and Iva) css library</h1>

<h2>Амииии Документация:</h2>

<h2>Задължителни класове за всяка страница</h2>
<table>
  <tr>
    <th>Име на класа</th>
    <th>Описание</th>
  </tr>
  <tr>
    <td>.mi-layout</td>
    <td>Слага се задължително на div елемента, непосредствено след body! Този клас се слага на елемент който играе ролята wrapper за цялата страница. По този начин навигация, хедър и футър ще са винаги респонсив и подредени правилно.</td>
  </tr>
  <tr>
    <td>.mi-navbar</td>
    <td>Слага се на елемент, който е предвиден за навигация. В него трябва да има <b><i>ul</i></b> елементи, не повече от едно ниво на вътре! Възможно е да се ползват и dropdown менюта.</td>
  </tr>
  <tr>
    <td>.mi-header</td>
    <td>Слага се задължително на header елемента!</td>
  </tr>
  <tr>
    <td>.mi-main</td>
    <td>Слага се задължително на main елемента!</td>
  </tr>
  <tr>
    <td>        .mi-footer        </td>
    <td>Слага се задължително на footer елемента в страницата!</td>
  </tr>
  <tr>
    <td colspan=2>

              <h2>habala babala</h2>

    </td>
  </tr>
</table>

<h2>Полезни</h2>
<table>
  <tr>
    <th>Име на клас</th>
    <th>Описание</th>
  </tr>
  <tr>
    <td>.mi-icon</td>
    <td>Все още се разработва.</td>
  </tr>
</table>

<h2>Бутони</h2>
<table>
  <tr>
    <th>Име на клас</th>
    <th>Описание</th>
  </tr>
  <tr>
    <td>mi-btn-primary</td>
    <td>Бутон (a или button елемент) който семантично е основен бутон за сайта.</td>
  </tr>
  <tr>
    <td>mi-btn-success</td>
    <td>Бутон (a, button) който семантично е за успешно дествие.</td>
  </tr>
  <tr>
    <td>mi-btn-warning</td>
    <td>Бутон (a, button) който семантично е за предупреждение/повишено внимание.</td>
  </tr>
  <tr>
    <td>mi-btn-danger</td>
    <td>Бутон (a, button) който семантично е за опасно действие.</td>
  </tr>
  <tr>
    <td>mi-btn-info</td>
    <td>Бутон (a, button) който семантично води до информация за нещо или страница за нещото.</td>
  </tr>
  <tr>
    <td>mi-btn-link</td>
    <td>Бутон (a, button) който семантично представя анкар таг(линк).</td>
  </tr>
  <tr>
    <td>mi-btn-nav</td>
    <td>Бутон (a, button). Ползва се в навигационното меню. Следва стиловете от темата на сайта. Ползва се само в nav елемент с клас .mi-navbar</td>
  </tr>
  <tr>
    <td>mi-btn-footer</td>
    <td>Бутон (a, button). Ползва се във футъра на сайта. Следва стиловете от темата на сайта. Ползва се само във footer елемент с клас .mi-footer</td>
  </tr>
</table>

<h2>Полезни за навигацията</h2>
<table>
  <tr>
    <th>Име на клас</th>
    <th>Описание</th>
  </tr>
  <tr>
    <td>.mi-search-input-nav</td>
    <td>Ако има нужда от търсачка в навигацията, това е правилният клас. Слага се форма в li елемент. В тази форма се слага input със тип search. Логично е да се използва и бутонче за изпращане на формата, което е прието да ползва класа .mi-search-button-nav.</td>
  </tr>
  <tr>
    <td>.mi-search-button-nav</td>
    <td>Стилизира бутона за изпращане на формата за търсене, в навигационното меню.</td>
  </tr>
  <tr>
    <td>#haburger</td>
    <td>Това id бива сложено на елемент input от тип checkbox. Позволява контрола върху навигацията само със CSS, когато има нужда от респонсив екстри.</td>
  </tr>
  <tr>
    <td>#hamburger-button</td>
    <td>Слага се на обикновен див елемент. Важното е да се сложат 3 на брой празни дива в текущият. Така ще бъдат стилизирани чертичките на хамбургер бутона.</td>
  </tr>
  <tr>
    <td>.mi-dropdown-nav</td>
    <td>Нужно е да покажа примерен код за този клас!</td>
  </tr>
  <tr>
    <td>.mi-dropdown-content-nav</td>
    <td>Нужно е да покажа примерен код за този клас!</td>
  </tr>
</table>

<h2>Контейнери</h2>
<table>
  <tr>
    <th>име на класа</th>
    <th>описание</th>
  </th>
  <tr>
    <td>
      .mi-column-for-desktop
    </td>
    <td>Елементите в този елемент ще са подредени в 1 колона, когато резолюцията е за desktop.</td>
  </tr>
  <tr>
    <td>
      .mi-?-columns-for-desktop
    </td>
    <td>Елементите в този елемент ще са подредени в ? колони, където ? може да е между 2 и 12, когато резолюцията е за desktop.</td>
  </tr>
  </tr>
  <tr>
    <td>
      .mi-row-for-desktop
    </td>
    <td>Елементите в този елемент ще са подредени в 1 ред, когато резолюцията е за desktop.</td>
  </tr>
  <tr>
    <td>
      .mi-?-rows-for-desktop
    </td>
    <td>Елементите в този елемент ще са подредени в ? реда, където ? може да е между 2 и 10, когато резолюцията е за desktop.</td>
  </tr>
  <tr>
    <td>
      .mi-column-for-notebook
    </td>
    <td>Елементите в този елемент ще са подредени в 1 колона, когато резолюцията е за notebook.</td>
  </tr>
  <tr>
    <td>
      .mi-?-columns-for-notebook
    </td>
    <td>Елементите в този елемент ще са подредени в ? колони, където ? може да е между 2 и 12, когато резолюцията е за notebook.</td>
  </tr>
  <tr>
    <td>
      .mi-row-for-notebook
    </td>
    <td>Елементите в този елемент ще са подредени в 1 ред, когато резолюцията е за notebook.</td>
  </tr>
  <tr>
    <td>
      .mi-?-rows-for-notebook
    </td>
    <td>Елементите в този елемент ще са подредени в ? реда, където ? може да е между 2 и 10, когато резолюцията е за notebook.</td>
  </tr>
  <tr>
    <td>
      .mi-column-for-tablet
    </td>
    <td>Елементите в този елемент ще са подредени в 1 колона, когато резолюцията е за tablet.</td>
  </tr>
  <tr>
    <td>
      .mi-?-columns-for-tablet
    </td>
    <td>Елементите в този елемент ще са подредени в ? колони, където ? може да е между 2 и 12, когато резолюцията е за tablet.</td>
  </tr>
  <tr>
    <td>
      .mi-row-for-tablet
    </td>
    <td>Елементите в този елемент ще са подредени в 1 ред, когато резолюцията е за tablet.</td>
  </tr>
  <tr>
    <td>
      .mi-?-rows-for-tablet
    </td>
    <td>Елементите в този елемент ще са подредени в ? реда, където ? може да е между 2 и 10, когато резолюцията е за tablet.</td>
  </tr>
  <tr>
    <td>
      .mi-column-for-mobile
    </td>
    <td>Елементите в този елемент ще са подредени в 1 колона, когато резолюцията е за tablet.</td>
  </tr>
  <tr>
    <td>
      .mi-?-columns-for-mobile
    </td>
    <td>Елементите в този елемент ще са подредени в ? колони, където ? може да е между 2 и 12, когато резолюцията е за mobile.</td>
  </tr>
  <tr>
    <td>
      .mi-row-for-mobile
    </td>
    <td>Елементите в този елемент ще са подредени в 1 ред, когато резолюцията е за mobile.</td>
  </tr>
  <tr>
    <td>
      .mi-?-rows-for-mobile
    </td>
    <td>Елементите в този елемент ще са подредени в ? реда, където ? може да е между 2 и 10, когато резолюцията е за mobile.</td>
  </tr><tr>
    <td>
      .mi-gap-?-for-desktop
    </td>
    <td>Помага на елементи с display: grid; намиращи се на резолюция за desktop, да дишат(примерно във footer елемента). Нужно е да ? да се замести със стойност от 0 до 5. Колкото по-голямо е числото, толкова повече място ще бъде осигурено.</td>
  </tr>
  <tr>
    <td>
      .mi-gap-?-for-notebook
    </td>
    <td>Помага на елементи с display: grid; намиращи се на резолюция за notebook, да дишат(примерно във footer елемента). Нужно е да ? да се замести със стойност от 0 до 5. Колкото по-голямо е числото, толкова повече място ще бъде осигурено.</td>
  </tr>
  <tr>
    <td>
      .mi-gap-?-for-tablet
    </td>
    <td>Помага на елементи с display: grid; намиращи се на резолюция за tablet, да дишат(примерно във footer елемента). Нужно е да ? да се замести със стойност от 0 до 5. Колкото по-голямо е числото, толкова повече място ще бъде осигурено.</td>
  </tr>
  <tr>
    <td>
      .mi-gap-?-for-mobile
    </td>
    <td>Помага на елементи с display: grid; намиращи се на резолюция за mobile, да дишат(примерно във footer елемента). Нужно е да ? да се замести със стойност от 0 до 5. Колкото по-голямо е числото, толкова повече място ще бъде осигурено.</td>
  </tr>
</table>