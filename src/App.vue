<template>
  <div id="app">
    <div class="card-delivery">
      <div class="delivery-header">
        <div class="wrapper">
          <img class="header-logo" src="../src/assets/logo-tas.svg" alt="logo">
        </div>
      </div>

      <div class="delivery-body">
        <div class="progress">
          <h1 class="main-title">Доставка карт на руки</h1>

          <div class="progress-items">
            <div class="item active">
              <p class="title">Введение данных</p>
              <div class="icon">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30">
                  <path class="svg-item" fill="#BBB" fill-rule="evenodd" d="M2.93 20.45a.586.586 0 1 1 0 1.172.586.586 0 0 1 0-1.173zm22.968-6.036c.324 0 .586.262.586.586v4.863a.586.586 0 0 1-1.172 0V15c0-.324.263-.586.586-.586zm3.587-9.036c.332.332.515.774.515 1.243v6.035a1.76 1.76 0 0 1-1.172 1.657v8.994a5.257 5.257 0 0 1-.886 2.925l-1.453 2.18-.005 1.005a.586.586 0 0 1-.586.583h-.002a.586.586 0 0 1-.584-.589l.005-.985-1.462-2.194a5.256 5.256 0 0 1-.886-2.925V5.45c0-.764.49-1.415 1.172-1.657V1.758a1.76 1.76 0 0 1 3-1.243c.332.332.515.773.515 1.243v2.034c.523.186.934.612 1.096 1.146.274.083.525.232.733.44zm-4.172-3.62V3.69h1.171V1.758a.582.582 0 0 0-.171-.414.587.587 0 0 0-1 .414zM24.14 5.449v.586h2.444c.156-.44.482-.8.9-1a.584.584 0 0 0-.415-.172h-2.343a.587.587 0 0 0-.586.586zm0 1.758v1.348h2.343V7.207h-2.343zm3.515 16.1v-.338h-3.515v.338c0 .812.238 1.599.689 2.275l1.068 1.604 1.07-1.604c.45-.676.688-1.463.688-2.275zm0-1.51v-7.484a1.76 1.76 0 0 1-1.172-1.657v-2.93h-2.343v12.07h3.515zm1.172-9.14v-.587h-1.172v.586a.587.587 0 0 0 1.172 0zm0-1.759V6.621a.582.582 0 0 0-.172-.414.587.587 0 0 0-1 .414v4.277h1.172zM20.04 2.52c.97 0 1.758.788 1.758 1.757v21.621a1.76 1.76 0 0 1-1.758 1.758h-.762v.657A1.69 1.69 0 0 1 17.59 30H2.904c-1.102 0-2.106-.588-2.557-1.497a3.193 3.193 0 0 1-.346-1.472L0 27.011V4.278c0-.782.305-1.517.858-2.071a2.927 2.927 0 0 1 4.414.314h14.767zM1.172 4.277v20.45a2.91 2.91 0 0 1 1.758-.586c.659 0 1.267.218 1.757.587V4.278a1.76 1.76 0 0 0-3-1.243 1.746 1.746 0 0 0-.515 1.242zm16.933 24.035v-.656H5.273a.586.586 0 0 1-.585-.586 1.76 1.76 0 0 0-1.758-1.758c-.945 0-1.734.769-1.758 1.713-.008.318.068.64.225.957.255.514.847.846 1.507.846H17.59a.516.516 0 0 0 .515-.515zm2.52-2.414V4.278a.587.587 0 0 0-.586-.587H5.86v22.793h14.18a.587.587 0 0 0 .586-.586zM2.93 8.555c.323 0 .586.262.586.586v9.55a.586.586 0 0 1-1.172 0v-9.55c0-.324.262-.586.586-.586zm15.761 0c.324 0 .586.262.586.586v7.03a.586.586 0 0 1-.586.587H7.617a.586.586 0 0 1-.586-.586V9.14c0-.324.263-.586.586-.586h11.074zm-.586 7.03V9.728H8.203v5.859h9.902zm-1.757-9.55a.586.586 0 0 1 0 1.172h-6.211a.586.586 0 0 1 0-1.172h6.21zm-5.625 6.035c.323 0 .586.263.586.586v1.172a.586.586 0 0 1-1.172 0v-1.172c0-.323.262-.586.586-.586zm2.52-.659c.323 0 .585.263.585.586v1.831a.586.586 0 0 1-1.172 0v-1.83c0-.324.263-.587.586-.587zm2.343-.513c.324 0 .586.263.586.586v2.344a.586.586 0 0 1-1.172 0v-2.344c0-.323.262-.586.586-.586zm3.105 8.38a.586.586 0 0 1 0 1.171H7.617a.586.586 0 0 1 0-1.172h11.074zm0 3.69a.586.586 0 0 1 0 1.173H7.617a.586.586 0 0 1 0-1.172h11.074z"/>
                </svg>
              </div>
            </div>

            <div class="item">
              <p class="title">Добавление паспортных данных</p>
              <div class="icon">
                <svg xmlns="http://www.w3.org/2000/svg" width="30" height="30" viewBox="0 0 30 30">
                  <path class="svg-item" fill="#BBB" fill-rule="evenodd" d="M8.79 11.074a.586.586 0 1 1-.001 1.173.586.586 0 0 1 0-1.173zm20.624 14.239c.324 0 .586.262.586.585v1.172A2.933 2.933 0 0 1 27.07 30H7.617a2.933 2.933 0 0 1-2.93-2.93V5.86H.587A.586.586 0 0 1 0 5.272V2.93A2.933 2.933 0 0 1 2.93 0h21.445a2.933 2.933 0 0 1 2.93 2.93v22.383h2.11zM4.687 4.688V2.93c0-.47-.182-.91-.515-1.243a1.76 1.76 0 0 0-3 1.243v1.758h3.516zm4.688 21.21c0-.323.262-.585.586-.585h9.14v-2.07a3.545 3.545 0 0 1-.329-.334.583.583 0 0 1-.256.06H8.789a.586.586 0 0 1 0-1.172h9.34a3.53 3.53 0 0 1 .002-2.344H8.79a.586.586 0 0 1 0-1.172h10.039a3.507 3.507 0 0 1 2.617-1.172 3.52 3.52 0 0 1 3.516 3.516 3.481 3.481 0 0 1-1.172 2.618v2.07h2.344V2.93a1.76 1.76 0 0 0-1.758-1.758H5.273c.38.504.586 1.115.586 1.758v24.14c0 .97.789 1.758 1.758 1.758a1.76 1.76 0 0 0 1.758-1.758v-1.172zm12.07-2.93a2.32 2.32 0 0 0 1.406-.468c.596-.448.938-1.131.938-1.875a2.346 2.346 0 0 0-2.344-2.344 2.346 2.346 0 0 0-2.343 2.344 2.325 2.325 0 0 0 .939 1.876 2.32 2.32 0 0 0 1.404.468zm1.172.972c-.372.132-.766.2-1.172.2-.405 0-.8-.068-1.172-.2v2.69l.847-.564a.586.586 0 0 1 .65 0l.847.565v-2.69zm6.211 3.13v-.586H23.79v1.241a.586.586 0 0 1-.91.488l-1.434-.955-1.432.955a.586.586 0 0 1-.911-.488v-1.24h-8.555v.585c0 .66-.219 1.268-.588 1.758H27.07a1.76 1.76 0 0 0 1.758-1.758zM18.516 3.516a.586.586 0 0 1 0 1.171h-6.211a.586.586 0 0 1 0-1.171h6.21zm4.687 7.558a.586.586 0 0 1 0 1.172h-12.07a.586.586 0 0 1 0-1.172h12.07zm0 3.692a.586.586 0 0 1 0 1.171H8.79a.586.586 0 0 1 0-1.171h14.414zm0-7.559a.586.586 0 0 1 0 1.172H8.79a.586.586 0 0 1 0-1.172h14.414z"/>
                </svg>
              </div>
            </div>

            <div class="item">
              <p class="title">Ожидание звонка</p>
              <div class="icon">
                <svg xmlns="http://www.w3.org/2000/svg" width="20" height="30" viewBox="0 0 20 30">
                  <path class="svg-item" fill="#BBB" fill-rule="evenodd" d="M6.494 20.856a.561.561 0 1 1 0 1.122.561.561 0 0 1 0-1.122zm4.488-8.023c.928 0 1.683.755 1.683 1.683v1.122c0 .928-.755 1.683-1.683 1.683h-.561v.561a.561.561 0 0 1-1.122 0v-.56h-.561a1.685 1.685 0 0 1-1.683-1.684.561.561 0 0 1 1.122 0c0 .31.252.561.56.561H9.3v-2.244h-.561a1.685 1.685 0 0 1-1.683-1.683V11.15c0-.928.755-1.683 1.683-1.683h.561v-.56a.561.561 0 0 1 1.122 0v.56h.561c.928 0 1.683.755 1.683 1.683a.561.561 0 0 1-1.122 0 .562.562 0 0 0-.561-.56h-.561v2.243h.561zm-1.683 0V10.59h-.561a.562.562 0 0 0-.561.561v1.122c0 .31.252.561.56.561H9.3zm2.244 2.805v-1.122a.562.562 0 0 0-.561-.56h-.561v2.243h.561c.31 0 .561-.251.561-.56zm8.345 11.55c0 1.017-.866 1.845-1.93 1.845H1.93C.866 29.033 0 28.205 0 27.187V1.845C0 .828.866 0 1.93 0h16.027c1.065 0 1.931.828 1.931 1.845v25.342zm-1.276-1.115V2.96c0-.928-.755-1.683-1.683-1.683H2.959c-.927 0-1.682.755-1.682 1.683v23.113c0 .928.755 1.683 1.683 1.683h13.969c.928 0 1.683-.755 1.683-1.683zM16.76 3.689c.31 0 .561.251.561.56v19.412c0 .31-.25.56-.56.56H2.96a.561.561 0 0 1-.561-.56V4.25c0-.31.25-.561.56-.561H16.76zm-.56 19.41V4.812H3.52V23.1H16.2zm-5.218 2.245a.561.561 0 0 1 0 1.122H8.738a.561.561 0 0 1 0-1.122h2.244zm2.435-4.488a.561.561 0 0 1 0 1.122h-4.68a.561.561 0 0 1 0-1.122h4.68z"/>
                </svg>
              </div>
            </div>
          </div>
        </div>
        <div class="form">
          <div class="form-wrapper">
            <ul class="material-tabs">
              <li class="tab active">Паспорт</li>
              <li class="tab">ID  карта</li>
            </ul>
            <input class="default-input number" type="text" placeholder="Тел">
            <input class="default-input name" type="text" placeholder="ФИО/имя">
            <button class="action-btn">Дальше</button>
          </div>
        </div>
      </div>

      <div class="delivery-footer">
        <div class="wrapper">
          <div class="logo-column">
            <img class="header-logo" src="../src/assets/logo-tas.svg" alt="logo">
            <p class="license">© АО “ТАСКОМБАНК” Лицензия НБУ №84 от 25 октября 2011 г</p>
          </div>

          <div class="contacts-column">
            <a class="facebook" href="#">
              <img class="facebook-logo" src="../src/assets/facebook.svg" alt="logo">
              Facebook
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
import { Component, Vue } from 'vue-property-decorator';
// import HelloWorld from './components/HelloWorld.vue';

@Component({
  components: {
    // HelloWorld,
  },
  methods: {

  }
})
export default class App extends Vue {}
</script>

<style lang="less">
  body {
    margin: 0;
  }

#app {
  .default-input {
    border-radius: 100px;
    border: solid 1px #d8d8d8;
    padding: 15px;
    font-size: 14px;
    color: rgba(0, 0, 0, 0.87);
    background-color: #ffffff;
    outline: none;

    &::placeholder {
      color: rgba(0, 0, 0, 0.2);
    }
  }

  .material-tabs {
    width: 100%;
    display: flex;
    justify-content: space-between;
    margin: 0;
    padding: 0;
    list-style: none;
    border-radius: 100px;
    box-shadow: inset 0 1px 9px 0 rgba(0, 0, 0, 0.07);
    border: solid 1px #f2f2f2;
    background-color: #ffffff;

    .tab {
      width: 50%;
      margin: 5px;
      padding: 11px 0;
      text-align: center;
      font-size: 15px;
      font-weight: 500;
      letter-spacing: -0.15px;
      border-radius: 100px;
      color: rgba(45, 45, 45, 0.3);
      cursor: pointer;
    }

    .tab.active {
      background-color: #0648b8;
      color: #fff;
      box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.24), 0 0 2px 0 rgba(0, 0, 0, 0.12);
    }
  }

  .action-btn {
    padding: 15px;
    font-size: 17px;
    font-weight: 500;
    letter-spacing: 0.61px;
    text-align: center;
    border-radius: 100px;
    box-shadow: 0 2px 2px 0 rgba(0, 0, 0, 0.24), 0 0 2px 0 rgba(0, 0, 0, 0.12);
    background-color: #d0021b;
    border: none;
    color: #fff;
    cursor: pointer;
    outline: none;

    &:hover {
      background-color: #e2021f;
    }

    &:active {
      box-shadow: inset 0 0 8px 1px rgba(0, 0, 0, 0.24), 0 0 2px 0 rgba(0, 0, 0, 0.12);
      background-color: #b10018;
    }
  }

  .card-delivery {
    font-family: 'Roboto', sans-serif;
    display: flex;
    flex-direction: column;

    .wrapper {
      width: 100%;
      max-width: 1000px;
      margin: 0 auto;
      display: flex;
    }

    .delivery-header {
      .header-logo {
        margin: 46px 0 9px 0;
        width: 140px;
      }
    }

    .delivery-body {
      display: flex;
      align-items: center;
      flex-direction: column;

      .main-title {
        margin: 0 0 85px 0;
        text-align: center;
        font-size: 45px;
        font-weight: bold;
        color: #2d2d2d;
      }

      .progress-items {
        display: flex;
        align-items: center;
        justify-content: space-between;
        margin: 0 0 39px 0;
        width: 600px;

        .item {
          display: flex;
          flex-direction: column;
          align-items: center;
          justify-content: center;

          .title {
            margin: 0 0 23px 0;
            font-size: 12px;
            color: #2d2d2d;
          }

          .icon {
            position: relative;
            display: flex;
            align-items: center;
            justify-content: center;
            width: 60px;
            height: 60px;
            background-color: #f8f8f8;
            border-radius: 100%;
          }
        }

        .item + .item {
          .icon {
            &:before {
              content: "";
              position: absolute;
              right: 0;
              z-index: -1;
              width: 276px;
              border: 1px solid #f8f8f8;
            }
          }
        }

        .item.active + .item {
          .icon {
            &:before {
              content: "";
              position: absolute;
              right: 0;
              z-index: -1;
              width: 276px;
              border: 1px solid #0648b8;
            }
          }
        }

        .item.active {
          .title {
            color: #0648b8;
          }

          .icon {
            background-color: #0648b8;

            .svg-item {
              fill: #ffffff;
            }
          }
        }
      }

      .form {
        height: 639px;
        width: 100%;
        background: url(../src/assets/background@2x.png) 0% 50% no-repeat #f8f8f8;
        background-size: 400px;

        .form-wrapper {
          display: flex;
          flex-direction: column;
          align-items: center;
          margin: 60px auto 0 auto;
          max-width: 300px;

          .material-tabs {
            margin: 0 0 30px 0;
          }

          .number {
            width: 268px;
            margin: 0 0 30px 0;
          }

          .name {
            width: 268px;
            margin: 0 0 60px 0;
          }

          .action-btn {
            width: 300px;
          }
        }
      }
    }

    .delivery-footer {
      display: flex;
      height: 80px;
      padding: 20px 0;
      border-top: solid 1px #d7d7d7;

      .wrapper {
        display: flex;
        justify-content: space-between;
      }

      .logo-column {
        display: flex;
        flex-direction: column;
        justify-content: center;
        align-items: flex-start;

        .header-logo {
          margin: 0 0 10px 0;
          width: 100px;
        }

        .license {
          margin: 0;
          font-size: 14px;
          color: rgba(0, 0, 0, 0.37);
        }
      }

      .contacts-column {
        display: flex;
        flex-direction: column;
        justify-content: flex-end;

        .facebook {
          display: flex;
          align-content: center;
          font-size: 16px;
          color: rgba(0, 0, 0, 0.37);
          text-decoration: none;
        }

        .facebook-logo {
          margin: 0 7px 0 0;
        }
      }
    }
  }
}



  .tab-content{
    display: flex;
    width: 100%;
    height: 400px;
    background-color: #ddd;
    overflow: hidden;
  }

  .tab-items{
    position: relative;
    width: 100%;
    height: 100%;
    z-index: 1;
    display: -webkit-box;
    display: -ms-flexbox;
    display: flex;
    box-sizing: content-box;
    transition: transform .2s ease-in-out;
    transfom: translate3d(0, 0, 0);
  }

  .tab-item{
    -ms-flex-negative: 0;
    flex-shrink: 0;
    width: 100%;
    height: 100%;
    position: relative;
  }

  .is-green{
    background-color: green;
  }

  .is-pink{
    background-color: hotpink;
  }

  .is-blue{
    background-color: cadetblue;
  }
</style>