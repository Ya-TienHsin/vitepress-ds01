<template>
  <div class="l-filters">
    <div class="l-filters--btn btnAll">全部</div>
    <div class="l-filters--line"></div>
    <div class="l-filters--btnGroup">
      <div class="l-filters--btn">野村投信</div>
      <div class="l-filters--btn">第一金投信</div>
      <div class="l-filters--btn">摩根投信</div>
      <div class="l-filters--btn">玉山投信</div>
      <div class="l-filters--btn">瀚亞投信</div>
      <div class="l-filters--btn">野村投信</div>
      <div class="l-filters--btn">第一金投信</div>
      <div class="l-filters--btn">摩根投信</div>
      <div class="l-filters--btn">玉山投信</div>
      <div class="l-filters--btn">瀚亞投信</div>
      <div class="l-filters--btn">摩根投信</div>
      <div class="l-filters--btn">玉山投信</div>
      <div class="l-filters--btn">瀚亞投信</div>
    </div>
    <div class="l-filters--btn btnMore">更多</div>
  </div>
</template>

<script setup>
  import {
    onMounted
  }

  from 'vue'
  import $ from 'jquery' // 後續底色可自行新增 更換成其他套件 import Highcharts函式名稱 from 'highcharts資料夾名稱'

  onMounted(() => {
      $(document).ready(function () {
          const $buttons = $('.l-filters--btn');
          const $btnAll = $('.btnAll');
          const $btnGroup = $('.l-filters--btnGroup');
          const $btnMore = $('.btnMore');
          const $btnGroupBtns = $btnGroup.find('.l-filters--btn');
          const maxVisible = 10;

          // 1. 一般按鈕點擊處理 (排除 .btnMore)
          $buttons.not('.btnMore').on('click', function () {
            $(this).toggleClass('active');
            $btnAll.removeClass('active');
          });

          // 2. 「全部」按鈕點擊處理
          $btnAll.on('click', function () {
            $buttons.removeClass('active');
            $(this).addClass('active');
          });

          // 3. 初始化「更多」按鈕顯示邏輯
          if ($btnGroupBtns.length > maxVisible) {
            $btnGroupBtns.slice(maxVisible).hide(); // 隱藏索引 10 之後的按鈕
            $btnMore.show().text('更多');
          } else {
            $btnMore.hide();
          }

          // 4. 「更多」按鈕展開/收合處理
          $btnMore.on('click', function () {
            const isExpanded = $(this).text() === '收合';

            if (isExpanded) {
              $btnGroupBtns.slice(maxVisible).hide();
              $(this).text('更多');
            } else {
              $btnGroupBtns.slice(maxVisible).css('display', 'inline-block');
              $(this).text('收合');
            }
          });
        }

      );
    }

  )
</script>

<style scoped>
  .l-filters {
    max-width: 500px;
  }

  .l-filters--btnGroup {
    display: inline;
  }

  .l-filters--btn {
    min-width: 100px;
    padding: 4px 18px;
    font-size: 16px;
    border: solid 1px #ACACAC;
    border-radius: 4px;
    margin: 10px 5px;
    display: inline-block;
    text-align: center;
    cursor: pointer;
    background-color: #fff;
  }

  .l-filters--btn.active {
    background-color: #00a19b;
    border: 1px solid #00a19b;
    color: #fff;
  }

  .l-filters--btn:hover {
    opacity: 0.8;
  }

  .l-filters--btn.btnAll {
    margin-right: 5px;
    min-width: auto;
  }

  .l-filters--btn.btnMore {
    min-width: auto;
    border: solid 1px #00a19b;
    color: #00a19b;
    background-color: #fff;
  }

  .l-filters--btn.btnMore.active {
    border: solid 1px #00a19b;
    color: #00a19b;
    background-color: #fff;
  }

  .l-filters--line {
    display: inline-block;
    width: 1px;
    background-color: #D9D9D9;
    height: 32px;
    vertical-align: middle;
  }
</style>