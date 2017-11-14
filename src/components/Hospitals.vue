<template>
    <div>
        
            <div class="container-fluid fluidblock">
                <div class="row imp-padding">
                    <form>
                        <div class="col-12 col-xs-12 col-sm-12 col-md-12 col-lg-12">
                            <FormInput v-bind:type="textOne" v-bind:name="nameOne" v-bind:text="text"></FormInput>
                            <div class="mb">
                                <MadButton v-bind:msg="Msg"></MadButton>
                            </div>
                        </div>
                    </form>
                </div>
            </div>
        

    </div>
</template>

<script>
import MadButton from '@/components/MadButton'
import FormInput from '@/components/FormInputJump'
export default {
  name: 'Hospital',
  components: {
    MadButton,
    FormInput
  },
  data () {
    return {
      textOne: 'text',
      nameOne: 'search',
      Msg: 'Search',
      text: 'Enter Hospital\'s name or Doctor\'s name'
    }
  }
}
</script>

<style scoped>

.fluidblock{
    display: block;
    margin-left: auto;
    margin-right: auto;
}
.imp-padding{
    padding-top: 25px;
    
}

.mb {
    display: inline-block;
    position: absolute;
    right: 15px;
    top: 20px;
}

</style>