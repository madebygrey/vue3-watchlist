<script setup>
import { RouterLink, RouterView } from "vue-router";
import TheMenu from "./components/TheMenu.vue";
import TheHeader from "./components/TheHeader.vue";
</script>

<template>
  <div class="main-wrapper">
    <div class="content">
      <div class="wrapper">
        <div class="main">
          <TheMenu />
          <main class="main-content">
            <RouterView />
          </main>
        </div>
      </div>
    </div>
    <TheHeader />
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

<style scoped></style>
