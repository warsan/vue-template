<template>
  <div class="hello">
    <h1>{{ msg }}</h1>
    <h3>Установленные плагины CLI</h3>
    <ul><li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-babel"
               target="_blank"
               rel="noopener">babel</a>
        </li>
        <li><a href="https://github.com/vuejs/vue-cli/tree/dev/packages/%40vue/cli-plugin-eslint"
               target="_blank"
               rel="noopener">eslint</a>
        </li>
    </ul>
    <h3>Основные ссылки</h3>
    <ul><li><a href="https://ru.vuejs.org/index.html" 
               target="_blank" 
               rel="noopener">Основные документы</a>
        </li>
        <li><a href="https://forum.vuejs.org" 
               target="_blank" 
               rel="noopener">Форум</a>
        </li>
        <li><a href="https://chat.vuejs.org" 
               target="_blank" 
               rel="noopener">Чат сообщества</a>
        </li>
        <li><a href="https://twitter.com/vuejs" 
               target="_blank" rel="noopener"
          >Твиттер</a>
        </li>
        <li><a href="https://news.vuejs.org" 
               target="_blank" 
               rel="noopener">Новости</a>
        </li>
    </ul>
    <h3>Экосистема</h3>
    <ul><li><a href="https://router.vuejs.org/ru/" 
               target="_blank" 
               rel="noopener">vue-router</a>
        </li>
        <li><a href="https://vuex.vuejs.org/ru/" 
               target="_blank" 
               rel="noopener">vuex</a>
        </li>
        <li><a href="https://github.com/vuejs/vue-devtools#vue-devtools"
               target="_blank"
               rel="noopener">vue-devtools</a>
        </li>
        <li><a href="https://vue-loader.vuejs.org/ru/" 
               target="_blank" 
               rel="noopener">vue-loader</a>
        </li>
        <li><a href="https://github.com/vuejs/awesome-vue"
               target="_blank"
               rel="noopener">awesome-vue</a>
        </li>
    </ul>
  </div>
</template>

<script>
export default {
  name: "Hello",
  props: { msg: String }
};
</script>

<!-- Добавьте атрибут "scoped", чтобы ограничить CSS только этим компонентом -->
<style scoped>
  h3 { margin: 20px 0 0; }
  a { color: #42b983; }
  ul { padding: 0;
     list-style-type: none;
     }
  li { margin: 0 5px;
     display: inline-block;
     }
</style>
