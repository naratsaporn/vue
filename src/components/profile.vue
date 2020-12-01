
<template>

  <b-card no-body class="card-profile" alt="Image placeholder" img-top>

    <b-card-body class="pt-0">
      
      <div class="text-center">
    
        <h1>Profile</h1>
     
       <div class="card-profile-image">
          <a href="#">
            <b-img src="https://lh3.googleusercontent.com/ogw/ADGmqu98MaxtQVnWHBvcR5kDVCEzvMt9qpefU7rlB93fDQ=s83-c-mo" rounded="circle" />
          </a>
        </div>
        <h5 class="h3">
          <p> Naratsaporn Heamra<span class="font-weight-light">, 25</span></p> 
        </h5>
        <div class="h5 font-weight-300">
            <p> Nonthaburi, Thailand</p> 
        </div>
        <div class="h5 mt-4">
          EDUCATION
        </div>
        <div>
            <p> Maejo University - Bachelor of Science | 28 May 2013 - 04 Aug 2017 | (Computer science) GPA : 2.69</p>
        </div>
        <div class="h5 mt-4">
          EXPERIENCES
        </div>
        <div>
            <p>
                Junior Full Stack Developer
                Aug 2017 - July 2018 | Ideal Co., Ltd. | Chiang Mai | Programming of
                web application by mainly using code of php codeindenter
                framework.
            </p>
            <p>
                Research associate
                July 2018 - April 2020 | Maejo University | Chiang Mai | Research
                associate of modeling for educational development by using data
                mining techniques.
            </p>
            <p>
                 Junior Full Stack Develope - April 2020 - Present | Avengosoft Co., Ltd. | Nonthaburi | Creating
                and modifying website features with Vue js , Laravel 5 and using
                code versioning tools by git control.
            </p>
        </div>
      </div>
    </b-card-body>
  </b-card>
</template>

<script>

import 'bootstrap/dist/css/bootstrap.css'
import 'bootstrap-vue/dist/bootstrap-vue.css'
import toolsmenu from '@/components/top'


export default {
  components: {
     'toolsmenu': toolsmenu
  }
}
</script>

<style scoped>

</style>