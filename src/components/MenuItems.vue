<template lang="pug">
.menu-items(v-t9n.deep)
  Submenu(name="learn")
    span(slot="title") Изучение
    MenuItem(name="docs", to="/docs") Документация
    MenuItem(name="examples", to="/examples") Примеры
  Submenu(name="ecosystem")
    span(slot="title") Экосистема
    MenuItem(name="components", to="/components") Компоненты
    MenuItem(name="issues", to="/issues") Проблемы
    MenuItem(name="cli", to="/cli") Rete CLI
  MenuItem(name="support", to="/support") Поддержать
</template>

<style lang="sass" scoped>
.menu-items
  white-space: nowrap
</style>
