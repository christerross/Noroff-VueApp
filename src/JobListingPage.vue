<template>
  <div class="[ row ]">
    <JobListingComponent></JobListingComponent>
  </div>
</template>

<script>
import JobListingComponent from './components/JoblistingComponent.vue'
export default {
  name: 'JobListing',
  components:{
    JobListingComponent 
  }
}
</script>
