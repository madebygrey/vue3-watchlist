<template>
  <aside class="main-aside">
    <div class="main-aside__overlay"></div>
    <div class="main-aside__box">
      <div class="main-logo">
        <img src="../assets/img/logo.svg" alt="" />
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
            <router-link :to="{ name: 'home' }"
              ><i class="icon-home"></i>Home</router-link
            >
          </li>
          <li>
            <router-link :to="{ name: 'history' }">
              <i class="icon-history"></i>History
            </router-link>
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
          <img src="../assets/img/user-empty.png" alt="" />
        </span>
        <span class="aside-user__name">GUEST</span>
        <i class="icon-dots"></i>
      </a>
    </div>
  </aside>
</template>

<script setup></script>

<style lang="scss" scoped></style>
