<template>
  <div class="wrapper-map card-c p-4 my-5 pe-5">
    <div class="row">
      <div class="col-12 col-md-5 col-xl-4 d-flex justify-content-center">
        <div>
          <div class="title-map">
            <h2>Наш адрес:</h2>
            <p>Адрес: Геленджик, ул.Ленина 14, центр города</p>
          </div>
          <p>
            Независимо от ваших целей - работа, учеба или отдых - наше уютное
            пространство открыто для вас. Мы стремимся создать атмосферу
            дружелюбия и удовольствия, где каждый посетитель чувствует себя как
            дома.
          </p>
        </div>
      </div>
      <div class="col-1 col-md-1 col-xl-2"></div>
      <div class="col-12 col-md-6 col-xl-6">
        <div class="w-100">
            <YandexMap />
        </div>
      </div>
    </div>
  </div>
</template>

<script scope>
import YandexMap from "./YandexMap.vue";

export default {
  name: "AreaWD-project",
  data() {
    return {};
  },
  components: {
    YandexMap,
  },
};
</script>

<style scoped></style>
