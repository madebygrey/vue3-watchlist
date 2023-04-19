<template>
  <div class="main-wrapper">
    <!-- BEGIN CONTENT -->

    <div class="content">
      <div class="wrapper">
        <div class="main">
          <aside class="main-aside">
            <div class="main-aside__overlay"></div>
            <div class="main-aside__box">
              <div class="main-logo">
                <img src="img/logo.svg" alt="" />
              </div>
              <div class="main-aside__search">
                <div class="form-box form-box__search">
                  <i class="icon-search"></i>
                  <input
                    type="search"
                    name="search"
                    class="form-control"
                    placeholder="Search" />
                </div>
              </div>
              <nav class="main-aside__nav">
                <ul>
                  <li>
                    <a href="#" class="active"><i class="icon-home"></i>Home</a>
                  </li>
                  <li>
                    <a href="#"><i class="icon-history"></i>History</a>
                  </li>
                </ul>
              </nav>
              <a href="#" class="btn"> + Create watchlist </a>
              <div class="aside-lists">
                <span class="aside-lists__title">My Lists</span>
                <ul>
                  <li>
                    <a href="#"><i class="icon-m"></i>Movies by Tom Cruise</a>
                  </li>
                </ul>
              </div>
              <a href="#" class="aside-user">
                <span class="aside-user__img">
                  <img src="img/user-empty.png" alt="" />
                </span>
                <span class="aside-user__name">GUEST</span>
                <i class="icon-dots"></i>
              </a>
            </div>
          </aside>
          <main class="main-content">
            <div class="main-welcome">
              <span class="main-welcome__title">
                Welcome to <span>Watchlists</span>
              </span>
              <p>
                Browse movies, add them to watchlists and share them with
                friends. Just click the
                <img src="img/icons/ribbon.svg" alt="" /> to add a movie, the
                poster to see more details or <i class="icon-check"></i> to mark
                the movie as watched.
              </p>
            </div>
            <div class="main-search">
              <div class="form-box form-box__search">
                <i class="icon-search"></i>
                <input
                  type="search"
                  name="search"
                  class="form-control"
                  placeholder="Search  for movies by title" />
                <button class="btn">search</button>
              </div>
            </div>
            <div class="movies-list movies-list__popular">
              <span class="movies-list__title">Popular movies right now</span>
              <div class="movies-list__box">
                <a href="#" class="movies-item">
                  <span class="movies-item__add"></span>
                  <div class="movies-item__img">
                    <img src="img/poster1.png" alt="" />
                  </div>
                  <div class="movies-item__rate">
                    <i class="icon-great"></i>
                    <span>83 <sup>/100</sup></span>
                  </div>
                  <span class="movies-item__title">
                    Top Gun: Maverick <span>(2022)</span>
                  </span>
                </a>
                <a href="#" class="movies-item">
                  <span class="movies-item__add"></span>
                  <div class="movies-item__img">
                    <img src="img/poster2.png" alt="" />
                  </div>
                  <div class="movies-item__rate">
                    <i class="icon-normal"></i>
                    <span>68 <sup>/100</sup></span>
                  </div>
                  <span class="movies-item__title">
                    Fantastic Beasts: The Secrets of Dumbledore
                    <span>(2022)</span>
                  </span>
                </a>
                <a href="#" class="movies-item">
                  <span class="movies-item__add"></span>
                  <div class="movies-item__img">
                    <img src="img/poster1.png" alt="" />
                  </div>
                  <div class="movies-item__rate">
                    <i class="icon-great"></i>
                    <span>83 <sup>/100</sup></span>
                  </div>
                  <span class="movies-item__title">
                    Top Gun: Maverick <span>(2022)</span>
                  </span>
                </a>
                <a href="#" class="movies-item">
                  <span class="movies-item__add"></span>
                  <div class="movies-item__img">
                    <img src="img/poster2.png" alt="" />
                  </div>
                  <div class="movies-item__rate">
                    <i class="icon-normal"></i>
                    <span>68 <sup>/100</sup></span>
                  </div>
                  <span class="movies-item__title">
                    Fantastic Beasts: The Secrets of Dumbledore
                    <span>(2022)</span>
                  </span>
                </a>
                <a href="#" class="movies-item">
                  <span class="movies-item__add"></span>
                  <div class="movies-item__img">
                    <img src="img/poster1.png" alt="" />
                  </div>
                  <div class="movies-item__rate">
                    <i class="icon-great"></i>
                    <span>83 <sup>/100</sup></span>
                  </div>
                  <span class="movies-item__title">
                    Top Gun: Maverick <span>(2022)</span>
                  </span>
                </a>
                <a href="#" class="movies-item">
                  <span class="movies-item__add"></span>
                  <div class="movies-item__img">
                    <img src="img/poster1.png" alt="" />
                  </div>
                  <div class="movies-item__rate">
                    <i class="icon-great"></i>
                    <span>83 <sup>/100</sup></span>
                  </div>
                  <span class="movies-item__title">
                    Top Gun: Maverick <span>(2022)</span>
                  </span>
                </a>
                <a href="#" class="movies-item">
                  <span class="movies-item__add"></span>
                  <div class="movies-item__img">
                    <img src="img/poster2.png" alt="" />
                  </div>
                  <div class="movies-item__rate">
                    <i class="icon-normal"></i>
                    <span>68 <sup>/100</sup></span>
                  </div>
                  <span class="movies-item__title">
                    Fantastic Beasts: The Secrets of Dumbledore
                    <span>(2022)</span>
                  </span>
                </a>
                <a href="#" class="movies-item">
                  <span class="movies-item__add"></span>
                  <div class="movies-item__img">
                    <img src="img/poster1.png" alt="" />
                  </div>
                  <div class="movies-item__rate">
                    <i class="icon-great"></i>
                    <span>83 <sup>/100</sup></span>
                  </div>
                  <span class="movies-item__title">
                    Top Gun: Maverick <span>(2022)</span>
                  </span>
                </a>
                <a href="#" class="movies-item">
                  <span class="movies-item__add"></span>
                  <div class="movies-item__img">
                    <img src="img/poster2.png" alt="" />
                  </div>
                  <div class="movies-item__rate">
                    <i class="icon-normal"></i>
                    <span>68 <sup>/100</sup></span>
                  </div>
                  <span class="movies-item__title">
                    Fantastic Beasts: The Secrets of Dumbledore
                    <span>(2022)</span>
                  </span>
                </a>
                <a href="#" class="movies-item">
                  <span class="movies-item__add"></span>
                  <div class="movies-item__img">
                    <img src="img/poster1.png" alt="" />
                  </div>
                  <div class="movies-item__rate">
                    <i class="icon-great"></i>
                    <span>83 <sup>/100</sup></span>
                  </div>
                  <span class="movies-item__title">
                    Top Gun: Maverick <span>(2022)</span>
                  </span>
                </a>
              </div>
            </div>
          </main>
        </div>
      </div>
    </div>

    <!-- CONTENT EOF   -->

    <!-- BEGIN HEADER -->

    <header class="header">
      <div class="wrapper">
        <div class="header-content">
          <div class="header-logo">
            <img src="img/logo.svg" alt="" />
          </div>
          <a href="#" class="header-create">+</a>
          <a href="#" class="header-user">
            <span class="aside-user__img">
              <img src="img/user-empty.png" alt="" />
            </span>
          </a>
          <a href="#" class="button-nav"><span></span></a>
        </div>
      </div>
    </header>

    <!-- HEADER EOF   -->
  </div>

  <div class="popups">
    <div class="popup" id="popupAdd">
      <div class="popup-overlay"></div>
      <div class="popup-box">
        <a href="#" class="popup-close">
          <i class="icon-cross"></i>
        </a>
        <div class="popup-add">
          <ul class="popup-add__content">
            <li>
              Add movie:
              <span class="popup-add__title">Top Gun: Maverick (2022)</span>
            </li>
            <li>
              To watchlist:
              <ul class="popup-add__list">
                <li>
                  <a href="#" class="btn btn-list"
                    ><i class="icon-m"></i>Movies by Tom Cruise</a
                  >
                </li>
              </ul>
              <a href="#" class="btn btn-new"><i>+</i>New watchlist</a>
            </li>
          </ul>
        </div>
      </div>
    </div>
    <div class="popup" id="popupNew">
      <div class="popup-overlay"></div>
      <div class="popup-box">
        <a href="#" class="popup-close">
          <i class="icon-cross"></i>
        </a>
        <form class="popup-new">
          <span class="popup-new__title">Create new watchlist</span>
          <div class="popup-new__form">
            <div class="form-box">
              <span class="form-box__label">Name</span>
              <input type="text" class="form-control" />
            </div>
            <div class="form-box">
              <span class="form-box__label">Description</span>
              <textarea class="form-control"></textarea>
            </div>
          </div>
          <div class="popup-new__btns">
            <a href="#">Cancel</a>
            <button class="btn">Save</button>
          </div>
        </form>
      </div>
    </div>
  </div>
</template>

<script setup></script>

<style lang="scss" scoped></style>
