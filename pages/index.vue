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
                    src="/english-landing/img/course.png"
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
                  <v-btn
                    depressed
                    class="blue white--text"
                  >Купить</v-btn>

                  <div class="subtitle-1 ml-4">
                    <span>3900 грн.</span>
                    <span class="old-cost">4500 грн.</span>
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
                    src="/english-landing/img/course.png"
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
                  <v-btn
                    depressed
                    class="blue white--text"
                  >Купить</v-btn>

                  <div class="subtitle-1 ml-4">
                    <span>7900 грн.</span>
                    <span class="old-cost">8900 грн.</span>
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
                    src="/english-landing/img/course.png"
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
                  <v-btn
                    depressed
                    class="blue white--text"
                  >Купить</v-btn>

                  <div class="subtitle-1 ml-4">
                    <span>16900 грн.</span>
                    <span class="old-cost">17500 грн.</span>
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
        <li>Даем вам доступ на платформу и личного куратора - для пакета "Вместе со всеми"</li>
      </ul>
    </v-alert>
  </div>
</template>

<style>
.card-content {
  height: 100%;
}
.old-cost {
  text-decoration: line-through;
  color: #999;
}
</style>