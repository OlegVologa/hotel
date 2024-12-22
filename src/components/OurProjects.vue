<script setup>
import ProjectArrow from './ProjectArrow.vue'
import BlackButton from './BlackButton.vue';
</script>
<template>
  <div class="projects_wrapper flex flex-col">
    <h3 class="title-h3"><span class="capitalize">наши</span> проекты</h3>
    <div class="projects">
      <div class="first_line flex flex-row">
        <a class="project relative" href="#">
          <img src="../assets/images/project1.png" alt="project" />
          <div class="cover absolute z-0"></div>
          <div class="project_text absolute z-10">
            досуговый центр
            <ProjectArrow />
          </div>
        </a>
        <a class="project relative" href="#">
          <img src="../assets/images/project2.png" alt="project" />
          <div class="cover absolute z-0"></div>
          <div class="project_text absolute z-10">
            ракушка
            <ProjectArrow />
          </div>
        </a>
      </div>
      <div class="second_line flex flex-row">
        <a class="project relative" href="#">
          <img src="../assets/images/project3.png" alt="project" />
          <div class="cover absolute z-0"></div>
          <div class="project_text absolute z-10">
            плац
            <ProjectArrow />
          </div>
        </a>
        <a class="project relative" href="#">
          <img src="../assets/images/project4.png" alt="project" />
          <div class="cover absolute z-0"></div>
          <div class="project_text absolute z-10">
            жилой район
            <ProjectArrow />
          </div>
        </a>
        <a class="project relative" href="#">
          <img src="../assets/images/project5.png" alt="project" />
          <div class="cover absolute z-0"></div>
          <div class="project_text absolute z-10">
            парк
            <ProjectArrow />
          </div>
        </a>
      </div>
    </div>
    <div class="self-end">
      <BlackButton text="все проекты" />
    </div>
  </div>
</template>

<style scoped>
.projects_wrapper {
  margin-bottom: 120px;
}

.title-h3 {
  margin-bottom: 60px;
}

.projects {
  max-width: 1170px;
}

.first_line,
.second_line {
  gap: 30px;
  margin-bottom: 30px;
}

.project:hover .cover {
  display: block;
}

.project:hover .project_text {
  display: block;
}

.cover {
  background-color: #333333;
  opacity: 80%;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  display: none;
}

.project_text {
  background-color: inherit;
  padding: 48px 78px 47px 79px;
  font-family: 'TTHoves-700';
  font-size: 64px;
  line-height: 64px;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  color: #fff;
  display: none;
}
</style>
