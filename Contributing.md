<!DOCTYPE html>
<html lang="ru">
 <head>
  <meta charset="utf-8">
  <title>Каталог"</title> 
 </head>

 <body>
  <header class="page header">
   <nav class="navigation">
    <ul class="navigation-list">
      <li class="navigation-item">
        <a class="navigation-link" href="catalog.html">Каталог товаров</a>
      <li class="navigation-item">
        <a class="navigation-link" href="delievery.html">Доставка</a>
      </li>  
      <li class="navigation-item">
        <a class="navigation-link" href="guarantee.html">Гарантия</a>
      </li>   
      <li class="navigation-item">
        <a class="navigation-link" href="contacts.html">Контакты</a>  
      </li>
    </ul>  
    <ul class="navigation-user">
      <li class="navigation-item">
        <a class="navigation-link" href="entrance.html">
        Войти</a>  
      </li>  
      <li class="navigation-item">
        <a class="navigation-link" href="comparison.html">Сравнить</a>
      </li>
      <li class="navigation-item">
        <a class="navigation-link" href="guarantee.html">Гарантия</a>
      </li>   
    </ul>
    <ul class="navigation-user">  
      <li class="navigation-item">
        <form action="catalog.html"><img src="loupe.jpg">><label><input name="Search"></label></form>
      </li> 
    </ul>  
   </nav>
  </header> 
  <main class="main-inner">
    <header class="inner-header">
      <h2 class="inner-header-title">Моноподы для селфи</h2>
      <ul class="product-list">
        <li class="product-item">
          <a class="product-link" href="index.html">Главная</a>
        </li>
        <li class="product-item"><a class="product-link" href="catalog.html">Каталог товаров</a></li>
        <li class="product-item"><a class="product-link">Моноподы для селфи</a></li>
      </ul>  
    </header>
    <section class="filter-products">
      <form class="catalog-filter" action="catalog.html" nethod="get">
        <fieldset class="catalog-filter-group"> 
          <legend class="catalog-filter-title">Цена</legend>
          <button class="range toggle toggle-min" type="button">
            <span class="visually-hidden">Изменить минимальную цену</span></button><label class="catalog-filter-label">от<input class="catalog-filter-input" type="number" name="min price">Р</label>
            <button class="range toggle toggle-max" type="button">
            <span class="visually-hidden">Изменить максимальную цену</span></button>
            <label class="catalog-filter-label">до<input class="catalog-filter-input" type="number" name="max price">Р</label>
          </fieldset>
          
          <fieldset class="catalog-filter-group">
          <ul><legend class="catalog-filter-title">Цвет</legend><label class="control">
            <li><input class="visually-hadden control-input" type="checkbox" name="black">
          <span class="control-color">Черный</span></li>
          <li><input class="visually-hadden control-input" type="checkbox" name="white">
          <span class="control-color">Белый</span></li>
          <li><input class="visually-hadden control-input" type="checkbox" name="blue">
          <span class="control-color">Синий</span></li><li><input class="visually-hadden control-input" type="checkbox" name="red">
          <span class="control-color">Красный</span>
          <li><input class="visually-hadden control-input" type="checkbox" name="pink">
          <span class="control-color">Розовый</span></li>
          
          </label></ul></fieldset>
          <fieldset class="catalog-filter-group">
          <legend class="catalog-filter-title">Bluetooth</legend><ul>
          <li><input class="visually-hadden control-input" type="radio" name="colour">
          <span class="control-color">Есть</span></li><li><input class="visually-hadden control-input" type="radio" name="colour">
          <span class="control-color">Нет</span></li></ul></fieldset>
          <button class="button" type="submit">Показать</button>
        </form>
    </section>
    <form class="sorting-type">
      <label class="visually-hidden" for sorting>Сортировка</label>
      <select class="select control" id="sorting" name="sorting">
        <option value="popular">Сначала популярное</option>
        <option value="cheap">Сначала дешевое</option>
        <option value="expensive">Сначала дорогое</option></select>
        <button class="visually-hidden" tupe="submit">Отсортировать</button>
    </form>
    <section>
      <div class="product-card">
        <a class="product-card-link" href="product.html">
          <img class="product card-image" src="#" alt="*">
          <h3 class="product-card-title">Любительская селфи-палка</h3></a>
          <span class="product-card-price">500р</span>
      </div>
      <div class="product-card">
        <a class="product-card-link" href="product.html">
          <img class="product card-image" src="#" alt="*">
          <h3 class="product-card-title">Профессиональная селфи-палка</h3></a>
          <span class="product-card-price">1500р</span>
      </div>
      <div class="product-card">
        <a class="product-card-link" href="product.html">
          <img class="product card-image" src="#" alt="*">
          <h3 class="product-card-title">Непотопляемая селфи-палка</h3></a>
          <span class="product-card-price">2500р</span>
      </div>
      <div class="product-card">
        <a class="product-card-link" href="product.html">
          <img class="product card-image" src="#" alt="*">
          <h3 class="product-card-title">Селфи-палка "Следуй за мной"</h3></a>
          <span class="product-card-price">4900р</span>
      </div>
      <button class="download-more" type="button">Загрузить еще</button>
      <ul class="pagination">
        <li class="pagination-item">
          <a class="pagination-link pagination-prev pagination-disabled">
            <span class="back">Назад</span></a></li>
            
            <li class="pagination-item">
          <a class="pagination-link pagination-current">1</a></li>
          <li class="pagination-item">
          <a class="pagination-link" href="#">2</a></li>
          <li class="pagination-item">
          <a class="pagination-link" href="#">3</a></li>
          <li class="pagination-item">
          <a class="pagination-link" href="#">...</a></li>
          <li class="pagination-item">
          <a class="pagination-link" href="#">15</a></li>
          
            
            <li class="pagination-item">
          <a class="pagination-link pagination-next" href="#">
            <span class="next">Вперед</span></a></li>
            </ul>
     </section>  
  </main>  
  <footer>
    <h2 class="foot">device</h2> 
    <p>Санкт-Петербург, набережная
реки Карповки, 5, литера П.</p>
<nav class="footer">
    <ul class="footer-list">
      <li class="footer-item">
        <a class="footer-link" href="delievery.html">Доставка</a>
      </li>  
      <li class="footer-item">
        <a class="footer-link" href="guarantee.html">Гарантия</a>
      </li>   
      <li class="footer-item">
        <a class="footer-link" href="contacts.html">Контакты</a>  
      </li>
    </ul> 
    </nav>
    <nav class="social-list">
      <form action="https://www.facebook.com/htmlacademy">
   <button type="button"><img src="fb.jpeg"></button>
  </form>
  <form action="https://www.instagram.com/htmlacademy">
   <button type="button"><img src="inst.jpg"></button>
  </form>
  <form action="https://www.twitter.com/htmlacademy_ru">
   <button type="button"><img src="twit.jpg"></button>
  </form>
    </nav>
    <p class="telephone">Тел.: +7 (812) 812-12-12</p>
    <a class="academy" href="https://htmlacademy.ru">.html academy</a>
    </footer>  
 </body>
</html>

