<template>
  <div
    class="main pt-60 pt-md-150 pb-50 pb-lg-150 mb-100 mb-lg-181 bg--white  main__border"
  >
    <div class="container">
      <h2 class="text--green main__h2  mb-40 mb-lg-60 w-100 w-md-55">
        Deation & Evaluation - Best Way to Kick off Your Product Idea
      </h2>
      <div class="d-flex justify-content-between flex-wrap">
        <div
          v-for="evaluation in evaluations"
          :key="evaluation.id"
          class="d-flex flex-column justify-content-between w-45 w-md-25 bg--whites px-5 px-sm-30 px-md-15 px-lg-30 pb-15 pb-md-36 pt-15 pt-md-27"
          :class="evaluation.class"
        >
          <div>
            <h3 class="main__evalution--h3 ">
              {{ evaluation.title }}
            </h3>
            <p class="main__text text--lg-14 mb-20 mb-md-40 mb-lg-55">
              {{ evaluation.text }}
            </p>
          </div>
          <div>
            <a :href="evaluation.url" class="link link--yellow">Read More</a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      evaluations: [
        {
          title: 'Product Design Sprint',
          text:
            '"A five-day workshop that will help you answer crucial business questions"',
          url: '#1',
          class: 'main__evalution--marginb'
        },
        {
          title: 'Scoping Session',
          text:
            '"A workshop aimed at shaping your business idea, answering questions regarding project planning"',
          url: '#2',
          class: 'main__evalution--marginb'
        },
        {
          title: 'UX Review',
          text:
            '"An evaluation which will help you radically improve your product."',
          url: '#3'
        },
        {
          title: 'Code Review',
          text:
            '"Do you know what one of the key secrets of success is what makes people successful in business"',
          url: '#4'
        }
      ]
    }
  }
}
</script>
