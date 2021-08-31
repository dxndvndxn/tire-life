<template>
  <nav>
    <ul>
      <li v-for="(item, i) in menu" :key="i">
        {{ item }}
      </li>
    </ul>
  </nav>
</template>

<script>
export default {
  name: 'header',
  data: () => ({
    menu: [
      {
        view: 'Шины',
        link: 'Tires'
      },
      {
        view: 'Диски',
        link: 'Disks'
      },
      {
        view: 'Шиномонтаж',
        link: 'TireFitting'
      },
      {
        view: 'Хранение',
        link: 'Storage'
      },
      {
        view: 'Доставка',
        link: 'Delivery'
      },
      {
        view: 'Акции',
        link: 'Sale'
      },
      {
        view: 'Контакты',
        link: 'Contacts'
      }
    ]
  })
}
</script>

<style scoped>

</style>
