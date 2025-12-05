<template>
  <p style="font-size: 20px;font-weight: bold;">Modals_Message</p>
  <div class="l-modals">
    <a class="show-popup" href="#" data-showpopup="1">Modals_Message-textLeft</a>、<a class="show-popup" href="#"
      data-showpopup="2">Modals_Message-textCenter</a>、<a class="show-popup" href="#"
      data-showpopup="3">Modals_Message-additional</a>、<a class="show-popup" href="#"
      data-showpopup="4">Modals_Message-Notice</a>
    <!-- 彈跳視窗內容放置區 -->
    <div class="overlay-bg">
      <div class="overlay"></div>
      <div class="l-modals--message textLeft popup" id="popup1">
        <div class="close-btn" href="">
          <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
            <g clip-path="url(#clip0_2205_464)">
              <mask id="mask0_2205_464" style="mask-type:luminance" maskUnits="userSpaceOnUse" x="7" y="5" width="18"
                height="23">
                <path d="M25 5H7V27.5H25V5Z" fill="white" />
              </mask>
              <g mask="url(#mask0_2205_464)">
                <path d="M8.125 8.375L23.875 24.125" stroke="#1C1C1C" stroke-width="2" stroke-linecap="round" />
                <path d="M23.875 8.375L8.125 24.125" stroke="#1C1C1C" stroke-width="2" stroke-linecap="round" />
              </g>
            </g>
            <defs>
              <clipPath id="clip0_2205_464">
                <rect width="32" height="32" fill="white" />
              </clipPath>
            </defs>
          </svg>
        </div>
        <p class="l-modals--title">注意事項</p>
        <div class="dragscroll scrollAreaWrapper">
          <p>創業需要準備多少資金？</p>
          <p>租金、營運支出、裝潢、設備 ……，根據調查，年輕人創業平均須準備 70 萬元以上。<br>不論是第 1 次還是第 n+1 次創業，資金來源要有依靠，慢慢拼出夢想藍圖。</p>
        </div>
        <div class="btnGroup">
          <a class="btn btnLine" href="#">次要按鈕</a>
          <a class="btn" href="#">主要按鈕</a>
        </div>
      </div>
    </div>
    <div class="overlay-bg">
      <div class="overlay"></div>
      <div class="l-modals--message textCenter popup" id="popup2">
        <div class="close-btn" href="">
          <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
            <g clip-path="url(#clip0_2205_464)">
              <mask id="mask0_2205_464" style="mask-type:luminance" maskUnits="userSpaceOnUse" x="7" y="5" width="18"
                height="23">
                <path d="M25 5H7V27.5H25V5Z" fill="white" />
              </mask>
              <g mask="url(#mask0_2205_464)">
                <path d="M8.125 8.375L23.875 24.125" stroke="#1C1C1C" stroke-width="2" stroke-linecap="round" />
                <path d="M23.875 8.375L8.125 24.125" stroke="#1C1C1C" stroke-width="2" stroke-linecap="round" />
              </g>
            </g>
            <defs>
              <clipPath id="clip0_2205_464">
                <rect width="32" height="32" fill="white" />
              </clipPath>
            </defs>
          </svg>
        </div>
        <p class="l-modals--title">公告</p>
        <div class="dragscroll scrollAreaWrapper">
          <p>若您出生地、國籍非屬中華民國，或具有美國、其他國家(含單一或多重)/地區稅務身分，須提供相關證明文件並親至分行辦理開戶。</p>
        </div>
        <div class="btnGroup">
          <a class="btn btnLine" href="#">次要按鈕</a>
          <a class="btn" href="#">主要按鈕</a>
        </div>
      </div>
    </div>
    <div class="overlay-bg">
      <div class="overlay"></div>
      <div class="l-modals--message additional popup" id="popup3">
        <div class="close-btn" href="">
          <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
            <g clip-path="url(#clip0_2205_464)">
              <mask id="mask0_2205_464" style="mask-type:luminance" maskUnits="userSpaceOnUse" x="7" y="5" width="18"
                height="23">
                <path d="M25 5H7V27.5H25V5Z" fill="white" />
              </mask>
              <g mask="url(#mask0_2205_464)">
                <path d="M8.125 8.375L23.875 24.125" stroke="#1C1C1C" stroke-width="2" stroke-linecap="round" />
                <path d="M23.875 8.375L8.125 24.125" stroke="#1C1C1C" stroke-width="2" stroke-linecap="round" />
              </g>
            </g>
            <defs>
              <clipPath id="clip0_2205_464">
                <rect width="32" height="32" fill="white" />
              </clipPath>
            </defs>
          </svg>
        </div>
        <svg class="l-modals--icon" width="64" height="64" viewBox="0 0 64 64" fill="none"
          xmlns="http://www.w3.org/2000/svg">
          <g clip-path="url(#clip0_2206_639)">
            <mask id="mask0_2206_639" style="mask-type:luminance" maskUnits="userSpaceOnUse" x="0" y="0" width="64"
              height="64">
              <path d="M64 0H0V64H64V0Z" fill="white" />
            </mask>
            <g mask="url(#mask0_2206_639)">
              <path
                d="M32 49.4667C32.9941 49.4667 33.8 48.6608 33.8 47.6667C33.8 46.6726 32.9941 45.8667 32 45.8667C31.0059 45.8667 30.2 46.6726 30.2 47.6667C30.2 48.6608 31.0059 49.4667 32 49.4667Z"
                fill="#00A19B" />
              <path
                d="M32 43.6667C31.2667 43.6667 30.6667 43.0667 30.6667 42.3333V35.2333C30.6667 34.5 31.2667 33.9 32 33.9C36.4 33.9 40 30.3 40 25.9C40 21.5 36.4 17.9 32 17.9C27.6 17.9 24 21.5 24 25.9C24 26.5333 24.0667 27.2 24.2333 27.8C24.4 28.5333 23.9667 29.2333 23.2667 29.4C22.5333 29.5667 21.8333 29.1333 21.6667 28.4333C21.4667 27.6 21.3667 26.7667 21.3667 25.9C21.3667 20.0333 26.1667 15.2333 32.0333 15.2333C37.9 15.2333 42.7 20.0333 42.7 25.9C42.7 31.3333 38.6333 35.8333 33.3667 36.5V42.3333C33.3333 43.0667 32.7333 43.6667 32 43.6667Z"
                fill="#00A19B" />
              <path
                d="M32 57.6667C18.0333 57.6667 6.66666 46.3 6.66666 32.3333C6.66666 18.3667 18.0333 7 32 7C45.9667 7 57.3333 18.3667 57.3333 32.3333C57.3333 46.3 45.9667 57.6667 32 57.6667ZM32 9.66667C19.5 9.66667 9.33332 19.8333 9.33332 32.3333C9.33332 44.8333 19.5 55 32 55C44.5 55 54.6667 44.8333 54.6667 32.3333C54.6667 19.8333 44.5 9.66667 32 9.66667Z"
                fill="#00A19B" />
            </g>
          </g>
          <defs>
            <clipPath id="clip0_2206_639">
              <rect width="64" height="64" fill="white" />
            </clipPath>
          </defs>
        </svg>
        <p class="l-modals--title">補充資訊標題</p>
        <div class="dragscroll scrollAreaWrapper">
          <p>若您出生地、國籍非屬中華民國，或具有美國、其他國家(含單一或多重)/地區稅務身分，須提供相關證明文件並親至分行辦理開戶。</p>
        </div>
        <div class="btnGroup">
          <a class="btn btnLine" href="#">次要按鈕</a>
          <a class="btn" href="#">主要按鈕</a>
        </div>
      </div>
    </div>
    <div class="overlay-bg">
      <div class="overlay"></div>
      <div class="l-modals--message notice popup" id="popup4">
        <div class="close-btn" href="">
          <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
            <g clip-path="url(#clip0_2205_464)">
              <mask id="mask0_2205_464" style="mask-type:luminance" maskUnits="userSpaceOnUse" x="7" y="5" width="18"
                height="23">
                <path d="M25 5H7V27.5H25V5Z" fill="white" />
              </mask>
              <g mask="url(#mask0_2205_464)">
                <path d="M8.125 8.375L23.875 24.125" stroke="#1C1C1C" stroke-width="2" stroke-linecap="round" />
                <path d="M23.875 8.375L8.125 24.125" stroke="#1C1C1C" stroke-width="2" stroke-linecap="round" />
              </g>
            </g>
            <defs>
              <clipPath id="clip0_2205_464">
                <rect width="32" height="32" fill="white" />
              </clipPath>
            </defs>
          </svg>
        </div>
        <svg class="l-modals--icon" width="64" height="64" viewBox="0 0 64 64" fill="none"
          xmlns="http://www.w3.org/2000/svg">
          <path
            d="M52.9599 31.9999C52.9599 20.424 43.5758 11.04 32 11.04C20.4241 11.04 11.04 20.4241 11.04 31.9999C11.04 43.5758 20.4241 52.9599 32 52.9599C43.5758 52.9599 52.9599 43.5758 52.9599 31.9999ZM55.6266 31.9999C55.6266 45.0486 45.0486 55.6266 32 55.6266C18.9513 55.6265 8.37332 45.0486 8.37332 31.9999C8.37334 18.9513 18.9513 8.37331 32 8.37329C45.0486 8.37329 55.6266 18.9513 55.6266 31.9999Z"
            fill="#EF7800" />
          <path
            d="M30.6667 38.6667V17.3333C30.6667 16.597 31.2636 16 32 16C32.7364 16 33.3333 16.597 33.3333 17.3333V38.6667C33.3333 39.403 32.7364 40 32 40C31.2636 40 30.6667 39.403 30.6667 38.6667Z"
            fill="#EF7800" />
          <path
            d="M30.6867 46.6667V45.1667C30.6867 44.4303 31.2836 43.8334 32.02 43.8334C32.7564 43.8334 33.3533 44.4303 33.3533 45.1667V46.6667C33.3533 47.4031 32.7564 48 32.02 48C31.2836 48 30.6867 47.4031 30.6867 46.6667Z"
            fill="#EF7800" />
        </svg>
        <p class="l-modals--title">補充資訊標題</p>
        <div class="dragscroll scrollAreaWrapper">
          <p>檔案無法辨識，請重新上傳。</p>
        </div>
        <div class="btnGroup">
          <a class="btn btnLine" href="#">次要按鈕</a>
          <a class="btn" href="#">主要按鈕</a>
        </div>
      </div>
    </div>
  </div>
  <p style="font-size: 20px;font-weight: bold;">Modals_Terms</p>
  <div class="l-modals">
    <a class="show-popup" href="#" data-showpopup="5">Modals_Terms</a>
    <!-- 彈跳視窗內容放置區 -->
    <div class="overlay-bg">
      <div class="overlay"></div>
      <div class="l-modals--terms popup" id="popup5">
        <div class="close-btn" href="">
          <svg width="32" height="32" viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
            <g clip-path="url(#clip0_2205_464)">
              <mask id="mask0_2205_464" style="mask-type:luminance" maskUnits="userSpaceOnUse" x="7" y="5" width="18"
                height="23">
                <path d="M25 5H7V27.5H25V5Z" fill="white" />
              </mask>
              <g mask="url(#mask0_2205_464)">
                <path d="M8.125 8.375L23.875 24.125" stroke="#1C1C1C" stroke-width="2" stroke-linecap="round" />
                <path d="M23.875 8.375L8.125 24.125" stroke="#1C1C1C" stroke-width="2" stroke-linecap="round" />
              </g>
            </g>
            <defs>
              <clipPath id="clip0_2205_464">
                <rect width="32" height="32" fill="white" />
              </clipPath>
            </defs>
          </svg>
        </div>
        <p class="l-modals--title">玉山銀行蒐集、處理及利用個人資料法定告知事項</p>
        <div class="dragscroll scrollAreaWrapper">
          <div class="scrollArea">
            <a class="text-link" href="#" target="_blank">下載全部條款</a>
            <p>茲因本人向玉山銀行(以下簡稱貴行)申請開立數位存款帳戶，本人同意並願意遵守以下
              數位存款帳戶開戶特別約定條款以及貴行「開戶總約定書」(路徑:法定公開揭露事項→定型
              化契約專區→開戶總約定書-目前為DG325A 2018.01)之相關約定，本人同時已審閱全部內容
              （審閱期間至少五日）後，方進行申請開戶：
            </p>
            <table>
              <tbody>
                <tr>
                  <td align="right" valign="top">壹、</td>
                  <td>本人瞭解數位存款帳戶僅提供具簽帳功能的Debit金融卡，同時不提供存摺，亦毋須約
                    定留存印鑑作為支付及約定相關依據。</td>
                </tr>
                <tr>
                  <td align="right" valign="top">貳、</td>
                  <td>本人知悉並瞭解開戶總約定書所記載之「玉山銀行蒐集、處理及利用個人資料法定告知
                    事項」之內容，且貴行向本存戶蒐集個人資料時，已依據個人資料保護法(以下稱個資
                    法)第八條第一項規定，明確告知本存戶下列事項：(1)非公務機關名稱(2)蒐集之目的
                    (3)個人資料之類別(4)個人資料利用之期間、地區、對象及方式(5)當事人依個資法第
                    三條規定得行使之權利及方式(6)當事人得自由選擇提供個人資料時，不提供將對其權
                    益之影響
                  </td>
                </tr>
                <tr>
                  <td align="right" valign="top">叁、</td>
                  <td>本人同意貴行、財團法人金融聯合聯徵中心、票據交換所、聯合信用卡處理中心、財金
                    資訊公司或其他往來金融機構及國內外金融事務處理相關機構等對業務所需，得依法令
                    規定蒐集、處理(包括委託第三人處理)及利用本人之個人資料。
                  </td>
                </tr>
                <tr>
                  <td align="right" valign="top">肆、</td>
                  <td>本人同意，數位存款帳戶無適用開戶總約定書以下章節，本人倘有需求，須另至貴行申
                    請轉換一般存款帳戶後，方能適用：
                    <table>
                      <tbody>
                        <tr>
                          <td valign="top">第四章</td>
                          <td>支票存款約定條款
                            <ol style="list-style: none;padding-left: 0px;">
                              <li>一、支票存款特別約定條款</li>
                              <li>二、支票存款約定書補充條款</li>
                            </ol>
                          </td>
                        </tr>
                        <tr>
                          <td valign="top">第七章</td>
                          <td>電子銀行服務約定條款
                            <ol style="list-style: none;padding-left: 0px;">
                              <li>三、企業網路銀行服務約定條款</li>
                            </ol>
                          </td>
                        </tr>
                        <tr>
                          <td valign="top">第十章</td>
                          <td>黃金存摺開戶約定條款</td>
                        </tr>
                      </tbody>
                    </table>
                  </td>
                </tr>
                <tr>
                  <td align="right" valign="top">伍、</td>
                  <td>若本人申請之數位存款帳戶屬信用卡驗證(第三類)數位存款帳戶，則無法申請金融卡、
                    網路銀行約定非本人帳戶轉帳功能以及非約定帳戶轉帳功能。</td>
                </tr>
                <tr>
                  <td align="right" valign="top">陸、</td>
                  <td>本人瞭解貴行就數位存款帳戶不受理臨櫃存款或臨櫃銷戶以外之帳務性交易；若有上述
                    以外之臨櫃交易需求時，本人得申請轉換為一般存摺存款帳戶。</td>
                </tr>
                <tr>
                  <td align="right" valign="top">柒、</td>
                  <td>本人同意持數位存款帳戶首次臨櫃處理非帳務性交易時，必須提供雙證件及同意貴行查
                    詢聯徵中心，並經首次驗證無誤後，方得執行。</td>
                </tr>
              </tbody>
            </table>

            <div class="d-flex justify-content-center">
              <a class="btn term-agree-btn ">同意</a>
            </div>
          </div>
        </div>
        <p class="scrollDown_btn">請滑動並詳閱本條款完整內容<br>Scroll Down to Read the Terms<svg width="32" height="32"
            viewBox="0 0 32 32" fill="none" xmlns="http://www.w3.org/2000/svg">
            <mask id="mask0_2267_1062" style="mask-type:luminance" maskUnits="userSpaceOnUse" x="0" y="0" width="32"
              height="32">
              <path d="M0 32L32 32L32 0L0 0L0 32Z" fill="white" />
            </mask>
            <g mask="url(#mask0_2267_1062)">
              <path
                d="M15.75 19.383C16.0067 19.3845 16.2552 19.2932 16.45 19.126L22.9109 13.426C23.0019 13.3504 23.0753 13.2556 23.1256 13.1484C23.1759 13.0413 23.2019 12.9244 23.2019 12.806C23.2019 12.6876 23.1759 12.5707 23.1256 12.4636C23.0753 12.3564 23.0019 12.2616 22.9109 12.186C22.7142 12.02 22.4652 11.929 22.2079 11.929C21.9506 11.929 21.7015 12.02 21.5049 12.186L15.7469 17.267L9.98889 12.186C9.79224 12.02 9.54321 11.929 9.28589 11.929C9.02857 11.929 8.77954 12.02 8.58289 12.186C8.49183 12.2616 8.41858 12.3564 8.36829 12.4636C8.31799 12.5707 8.29199 12.6876 8.29199 12.806C8.29199 12.9244 8.31799 13.0413 8.36829 13.1484C8.41858 13.2556 8.49183 13.3504 8.58289 13.426L15.0439 19.126C15.2402 19.2946 15.4913 19.3859 15.75 19.383Z"
                fill="#00A19B" />
            </g>
          </svg>
        </p>
      </div>
    </div>
  </div>
</template>

<script setup>
  import {
    onMounted
  } from 'vue'
  import $ from 'jquery' // 後續底色可自行新增 更換成其他套件 import Highcharts函式名稱 from 'highcharts資料夾名稱'

  onMounted(() => {

    $('.scrollDown_btn').click(function () {
      $(this).siblings('.scrollAreaWrapper').animate({
        scrollTop: $(this).siblings('.scrollAreaWrapper').find('.scrollArea').height()
      });
      $(this).css('display', 'none');
      $(this).parents('.scrollAreaWrapperOut').find('input').prop('disabled', false);
      $(this).parents('.popup').find('.term-agree-btn').removeClass('btnDisabled')
    })

    function showPopup(whichpopup) {
      $('#popup' + whichpopup).parent().fadeIn(200);
      $('body').addClass('active-body');
      $('#popup' + whichpopup).find('.scrollAreaWrapper').scroll(function () {

        var clientHeight = $(this).height();
        var scrollTop = $(this).scrollTop();

        var scrollHeight = $(this).find(".scrollArea").height();
        if (scrollTop + clientHeight + 1 >= scrollHeight) {

          $(this).parents('.popup').find('.term-agree-btn').removeClass('btnDisabled')
          $(this).siblings('.scrollDown_btn').css('display', 'none')

          $(".term-open").click(function () {
            $(this).find('.scrollAreaWrapper').animate({
              scrollTop: (scrollHeight)
            }, 0);
          })
          $(this).parents('.popup').find('.term-agree-btn').click(function () {
            $(this).parents('.popup_term').find('input').attr("checked", true);
            $(this).addClass('d-none')
          })
          $(this).parents('.popup_term').find('input').prop('disabled', false);
        }
      })
      $('#popup' + whichpopup).find('.term-agree-btn').click(function () {
        $(this).addClass('d-none')
        $(this).parents('.popup_term').find('input').attr("checked", true).prop('disabled',
          false);
      })
    }

    function closePopup() {
      $('.overlay-bg').fadeOut(200);
      $('body').removeClass('active-body');
    };
    $('.show-popup').click(function (event) {
      event.preventDefault();
      var selectedPopup = $(this).data('showpopup');
      showPopup(selectedPopup);
    });
    $('.close-btn, .overlay, .term-agree-btn').click(function () {
      closePopup();
      $('body').removeClass('active-body');
    });
    $(document).keyup(function (e) {
      if (e.keyCode == 27) {
        closePopup();
        $('body').removeClass('active-body');
      }
    });
  })
</script>


<style scoped>
  /* 客製化樣式 */
  .l-modals--message.textLeft {
    text-align: left;
  }

  .l-modals--message.textCenter,
  .l-modals--message.additional,
  .l-modals--message.notice {
    text-align: center;
  }

  .l-modals--message.textCenter .btnGroup,
  .l-modals--message.additional .btnGroup,
  .l-modals--message.notice .btnGroup {
    justify-content: center;
  }

  .l-modals--message.notice .l-modals--title {
    color: #EF7800;
  }

  .l-modals--terms .l-modals--title {
    color: #1c1c1c;
    margin: 0px;
  }

  /* 共用樣式 */
  .l-modals .show-popup {
    font-size: 16px;
    color: #00a19b;
    text-decoration: underline;
    display: inline-block;
  }

  .l-modals--title {
    color: #00a19b;
    font-size: 20px;
    font-weight: bold;
    width: 96%;
    margin: 0 auto;
    margin-left: 0;
  }

  .l-modals--icon {
    width: 64px;
    height: 64px;
    margin: 0 auto;
    display: block;
    margin-bottom: 12px;
  }

  .active-body {
    overflow: hidden;
  }

  .overlay-bg {
    display: none;
    position: fixed;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    z-index: 1000;
  }

  .overlay {
    position: absolute;
    top: 0;
    left: 0;
    height: 100%;
    width: 100%;
    cursor: pointer;
    z-index: 1001;
    /* fallback */
    background: rgba(0, 0, 0, 0.7);
  }

  .popup {
    display: block;
    background: #fff;
    position: absolute;
    -webkit-box-sizing: border-box;
    box-sizing: border-box;
    max-width: 1000px;
    top: 50%;
    left: 50%;
    width: 92%;
    padding: 20px;
    max-height: 100vh;
    height: auto;
    word-break: break-all;
    -webkit-transform: translate(-50%, -50%);
    transform: translate(-50%, -50%);
    cursor: default;
    z-index: 10001;
    border-radius: 4px;
    -webkit-box-shadow: 0 0 5px rgba(0, 0, 0, 0.9);
    box-shadow: 0 0 5px rgba(0, 0, 0, 0.9);
  }

  .popup .scrollAreaWrapper {
    max-height: 70vh;
    background-color: transparent;
    padding: 20px;
    padding-left: 0px;
    padding-bottom: 0px;
    padding-top: 0px;
    margin-top: 24px;
    overflow-y: auto;
    overflow-x: hidden;
    scrollbar-width: thin;
    scrollbar-color: #acacac #f0f0f0;
  }

  .popup .scrollAreaWrapper::-webkit-scrollbar {
    width: 6px;
  }

  .popup .scrollAreaWrapper::-webkit-scrollbar-track {
    background: #f0f0f0;
  }

  .popup .scrollAreaWrapper::-webkit-scrollbar-thumb {
    background: #acacac;
    border-radius: 20px;
  }

  .popup .scrollAreaWrapper p {
    margin: 0px;
  }

  .popup .scrollAreaWrapper ul {
    list-style: none;
    margin-left: -14px;
    font-size: 16px;
    margin-top: 0;
  }

  .popup .scrollAreaWrapper ul li::before {
    content: "•";
    padding-right: 8px;
  }

  .popup .scrollAreaWrapper ul ol {
    padding-left: 22px;
  }

  .popup .scrollAreaWrapper ul ol li {
    text-indent: 0px;
  }

  .popup .scrollAreaWrapper ul>li {
    padding-top: 2px;
    text-indent: -18px;
  }

  .btnGroup {
    display: flex;
    justify-content: center;
  }

  .btn {
    background-color: #00a19b;
    border-radius: 4px;
    width: 200px;
    height: 65px;
    box-sizing: border-box;
    color: #fff;
    display: flex;
    align-items: center;
    justify-content: center;
    margin: 24px 6px;
    margin-bottom: 0px;
  }

  .btnLine {
    background-color: #fff;
    color: #00a19b !important;
  }

  .close-btn {
    position: absolute;
    top: 10px;
    cursor: pointer;
    right: 10px;
  }

  .popup .scrollDown_btn {
    position: absolute;
    bottom: 20px;
    left: 50%;
    -webkit-transform: translateX(-50%);
    transform: translateX(-50%);
    background-color: #fff;
    -webkit-box-shadow: 0px 0px 4px 2px #d9d9d9;
    box-shadow: 0px 0px 4px 2px #d9d9d9;
    color: #00a19b;
    border-radius: 30px;
    font-weight: bold;
    padding: 10px 15px;
    margin-bottom: 8px;
    cursor: pointer;
    width: 80%;
    max-width: 250px;
    text-align: center;
    font-size: 14px;
    line-height: 1.5;
  }

  .popup .scrollDown_btn svg {
    margin: 0 auto;
    display: block;
  }

  @media (prefers-color-scheme: dark) {
    .popup {
      background: #e6e6e6;
    }
  }

  @media (min-width: 768px) {
    .popup {
      width: 80%;
      padding: 20px 40px;
    }

    .popup .scrollAreaWrapper {
      margin-top: 32px;
    }

    .l-modals--title {
      font-size: 24px;
      margin: 0 auto;
    }

    .btnGroup {
      justify-content: left;
    }

    .btn {
      margin: 32px 6px;
      margin-bottom: 0px;
    }

    .l-modals--message.textLeft .btnGroup .btn:nth-child(1) {
      margin-left: 0px;
    }

    .l-modals--message.textLeft .l-modals--title {
      margin-left: 0px;
    }

  }
</style>