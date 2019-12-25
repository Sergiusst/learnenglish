<template>
  <div>
    <v-row>
      <v-col md4>
        <v-card
          hover
          height="500"
        >
          <v-card-text class="card-content">
            <v-layout
              justify-space-between
              fill-height
              column
            >
              <div>
                <v-layout justify-center>
                  <v-img
                    width="140"
                    aspect-ratio="2"
                    contain
                    src="/learnenglish/img/course.png"
                  ></v-img>
                </v-layout>

                <div class="title my-4 grey--text text--darken-3">Пакет "Я сам"</div>

                <ul>
                  <li>Самостоятельное изучение языка</li>
                  <li>Пожизненный доступ ко всем видео на канале YouTube</li>
                  <li>Обновления курса</li>
                  <li>Доступ к чату школы</li>
                </ul>
              </div>

              <div>
                <v-layout align-center>
                  <v-menu
                    offset-y
                    :eager="true"
                  >
                    <template v-slot:activator="{ on }">
                      <v-btn
                        v-on="on"
                        depressed
                        class="blue white--text"
                      >Купить
                        <v-icon>mdi-chevron-down</v-icon>
                      </v-btn>
                    </template>
                    <v-list>
                      <v-list-item>
                        <v-list-item-title class="mb-1 mr-2">Карта</v-list-item-title>
                        <iframe
                          :src="course1.bank"
                          width="184"
                          height="36"
                          frameborder="0"
                          allowtransparency="true"
                          scrolling="no"
                        ></iframe>
                      </v-list-item>
                      <v-list-item>
                        <v-list-item-title class="mb-1 mr-2">Yandex.деньги</v-list-item-title>

                        <iframe
                          :src="course1.yandex"
                          width="184"
                          height="36"
                          frameborder="0"
                          allowtransparency="true"
                          scrolling="no"
                        ></iframe>
                      </v-list-item>
                    </v-list>
                  </v-menu>

                  <div class="subtitle-1 ml-4">
                    <span>2020 руб.</span>
                  </div>
                </v-layout>
              </div>
            </v-layout>
          </v-card-text>
        </v-card>
      </v-col>

      <v-col md4>
        <v-card
          hover
          height="500"
        >
          <v-card-text class="card-content">
            <v-layout
              justify-space-between
              fill-height
              column
            >
              <div>
                <v-layout justify-center>
                  <v-img
                    width="140"
                    aspect-ratio="2"
                    contain
                    src="/learnenglish/img/course.png"
                  ></v-img>
                </v-layout>

                <div class="title my-4 grey--text text--darken-3">Пакет "Вместе со всеми"</div>

                <ul>
                  <li>Пошаговое обучение на платформе</li>
                  <li>Поддержка преподавателя</li>
                  <li>Пожизненный доступ ко всем видео на канале YouTube</li>
                  <li>Обновления курса</li>
                  <li>Доступ к чату школы</li>
                </ul>
              </div>

              <div>
                <v-layout align-center>
                  <v-menu
                    offset-y
                    :eager="true"
                  >
                    <template v-slot:activator="{ on }">
                      <v-btn
                        v-on="on"
                        depressed
                        class="blue white--text"
                      >Купить
                        <v-icon>mdi-chevron-down</v-icon>
                      </v-btn>
                    </template>
                    <v-list>
                      <v-list-item>
                        <v-list-item-title class="mb-1 mr-2">Карта</v-list-item-title>
                        <iframe
                          :src="course2.bank"
                          width="184"
                          height="36"
                          frameborder="0"
                          allowtransparency="true"
                          scrolling="no"
                        ></iframe>
                      </v-list-item>
                      <v-list-item>
                        <v-list-item-title class="mb-1 mr-2">Yandex.деньги</v-list-item-title>

                        <iframe
                          :src="course2.yandex"
                          width="184"
                          height="36"
                          frameborder="0"
                          allowtransparency="true"
                          scrolling="no"
                        ></iframe>
                      </v-list-item>
                    </v-list>
                  </v-menu>

                  <div class="subtitle-1 ml-4">
                    <span>4040 руб.</span>
                  </div>
                </v-layout>
              </div>
            </v-layout>
          </v-card-text>
        </v-card>
      </v-col>

      <v-col md4>
        <v-card
          hover
          height="500"
        >
          <v-card-text class="card-content">
            <v-layout
              justify-space-between
              fill-height
              column
            >
              <div>
                <v-layout justify-center>
                  <v-img
                    width="140"
                    aspect-ratio="2"
                    contain
                    src="/learnenglish/img/course.png"
                  ></v-img>
                </v-layout>

                <div class="title my-4 grey--text text--darken-3">Пакет "Дайте мне лучшее"</div>

                <ul>
                  <li>Индивидуальные занятия с куратором</li>
                  <li>Пошаговое обучение на платформе</li>
                  <li>Поддержка куратора 24/7</li>
                  <li>Пожизненный доступ ко всем видео на канале YouTube</li>
                  <li>Обновления курса</li>
                  <li>Доступ к чату школы</li>
                </ul>
              </div>

              <div>
                <v-layout align-center>
                  <v-menu
                    offset-y
                    :eager="true"
                  >
                    <template v-slot:activator="{ on }">
                      <v-btn
                        v-on="on"
                        depressed
                        class="blue white--text"
                      >Купить
                        <v-icon>mdi-chevron-down</v-icon>
                      </v-btn>
                    </template>
                    <v-list>
                      <v-list-item>
                        <v-list-item-title class="mb-1 mr-2">Карта</v-list-item-title>
                        <iframe
                          :src="course3.bank"
                          width="184"
                          height="36"
                          frameborder="0"
                          allowtransparency="true"
                          scrolling="no"
                        ></iframe>
                      </v-list-item>
                      <v-list-item>
                        <v-list-item-title class="mb-1 mr-2">Yandex.деньги</v-list-item-title>

                        <iframe
                          :src="course3.yandex"
                          width="184"
                          height="36"
                          frameborder="0"
                          allowtransparency="true"
                          scrolling="no"
                        ></iframe>
                      </v-list-item>
                    </v-list>
                  </v-menu>

                  <div class="subtitle-1 ml-4">
                    <span>8080 руб.</span>
                  </div>
                </v-layout>
              </div>
            </v-layout>
          </v-card-text>
        </v-card>
      </v-col>
    </v-row>

    <v-alert
      icon="mdi-check-all"
      prominent
      text
      type="success"
    >
      <div class="title">После оплаты курса мы проверяем платеж и:</div>
      <ul>
        <li>Высылаем вам ссылку на скачивание курса на ваш email: - для пакета "Я сам”</li>
        <li>Даем вам доступ на платформу и связь с преподавателем - для пакета "Вместе со всеми"</li>
        <li>Даем вам доступ на платформу и личного куратора - для пакета "Дайте мне лучшее"</li>
      </ul>
    </v-alert>
  </div>
</template>

<script>
export default {
  data() {
    return {
      course1: {
        bank:
          "https://money.yandex.ru/quickpay/button-widget?targets=%22%D0%90%D0%BD%D0%B3%D0%BB%D0%B8%D0%B9%D1%81%D0%BA%D0%B8%D0%B9%20%D0%BA%D0%B0%D0%BA%20%D0%BA%D0%BE%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D0%BE%D1%80%22&default-sum=3900&button-text=11&any-card-payment-type=on&button-size=m&button-color=black&fio=on&phone=on&mail=on&successURL=&quickpay=small&account=410012624923404&",
        yandex:
          "https://money.yandex.ru/quickpay/button-widget?targets=%22%D0%90%D0%BD%D0%B3%D0%BB%D0%B8%D0%B9%D1%81%D0%BA%D0%B8%D0%B9%20%D0%BA%D0%B0%D0%BA%20%D0%BA%D0%BE%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D0%BE%D1%80%22&default-sum=3900&button-text=11&yamoney-payment-type=on&button-size=m&button-color=black&fio=on&phone=on&mail=on&successURL=&quickpay=small&account=410012624923404&"
      },
      course2: {
        bank:
          "https://money.yandex.ru/quickpay/button-widget?targets=%22%D0%90%D0%BD%D0%B3%D0%BB%D0%B8%D0%B9%D1%81%D0%BA%D0%B8%D0%B9%20%D0%BA%D0%B0%D0%BA%20%D0%BA%D0%BE%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D0%BE%D1%80%22&default-sum=7900&button-text=11&any-card-payment-type=on&button-size=m&button-color=black&fio=on&phone=on&mail=on&successURL=&quickpay=small&account=410012624923404&",
        yandex:
          "https://money.yandex.ru/quickpay/button-widget?targets=%22%D0%90%D0%BD%D0%B3%D0%BB%D0%B8%D0%B9%D1%81%D0%BA%D0%B8%D0%B9%20%D0%BA%D0%B0%D0%BA%20%D0%BA%D0%BE%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D0%BE%D1%80%22&default-sum=7900&button-text=11&yamoney-payment-type=on&button-size=m&button-color=black&fio=on&phone=on&mail=on&successURL=&quickpay=small&account=410012624923404&"
      },
      course3: {
        bank:
          "https://money.yandex.ru/quickpay/button-widget?targets=%22%D0%90%D0%BD%D0%B3%D0%BB%D0%B8%D0%B9%D1%81%D0%BA%D0%B8%D0%B9%20%D0%BA%D0%B0%D0%BA%20%D0%BA%D0%BE%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D0%BE%D1%80%22&default-sum=14900&button-text=11&any-card-payment-type=on&button-size=m&button-color=black&fio=on&phone=on&mail=on&successURL=&quickpay=small&account=410012624923404&",
        yandex:
          "https://money.yandex.ru/quickpay/button-widget?targets=%22%D0%90%D0%BD%D0%B3%D0%BB%D0%B8%D0%B9%D1%81%D0%BA%D0%B8%D0%B9%20%D0%BA%D0%B0%D0%BA%20%D0%BA%D0%BE%D0%BD%D1%81%D1%82%D1%80%D1%83%D0%BA%D1%82%D0%BE%D1%80%22&default-sum=14900&button-text=11&yamoney-payment-type=on&button-size=m&button-color=black&fio=on&phone=on&mail=on&successURL=&quickpay=small&account=410012624923404&"
      }
    };
  }
};
</script>

<style>
.card-content {
  height: 100%;
}
.old-cost {
  text-decoration: line-through;
  color: #999;
}
</style>