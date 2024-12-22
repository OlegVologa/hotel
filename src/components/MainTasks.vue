<template>
  <div class="flex flex-col">
    <h3 class="title-h3"><span class="capitalize">основные</span> задачи</h3>
    <div class="tasks-wrapper flex flex-row justify-between">
      <div class="tasks  flex flex-row ">
        <span class="tasks_span">1</span>
        <div class="text_task1">
          <p>Создание комфортных условий и повышение качества обслуживания клиентов</p>
        </div>
      </div>
      <div class="tasks  flex flex-row ">
        <span class="tasks_span">2</span>
        <div class="text_task2">
          <p>
            Постоянно совершенствовать качество предоставляемых услуг путем обучения персонала,
            закупки нового оборудования и усиленной рекламы на рынке
          </p>
        </div>
      </div>
    </div>
  </div>
</template>

<style scoped>
.title-h3 {
  margin-bottom: 60px;
}

.tasks-wrapper {
  margin-bottom: 120px;
}

.tasks_span {
  font-family: "SFProDisplay-Bold";
  font-size: 200px;
  line-height: 140px;
  color: #f2f2f2;
  margin-right: 30px;
}

.text_task1,.text_task2 {
  font-family: "TTHoves-400";
  font-size: 22px;
  line-height: 36px;
  color: #333333;
}

.text_task1 {
  width: 279px;
}

.text_task2 {
  width: 420px;
}
</style>
