<template>
    <div>
        <div class="col-6 col-xs-6 col-sm-6 col-md-6 col-lg-6">
          <div class="row">
            <div class="container-fluid">
              <div class="left">
                <p class="white lato">View Bookings</p>
              </div>
            </div>
          </div>
        </div>
        <div class="col-6 col-xs-6 col-sm-6 col-md-6 col-lg-6">
          <div class="row">
            <div class="container-fluid">
              <div class="right">
                <p class="lato white">Book</p>
              </div>
            </div>
          </div>
        </div>
    </div>
</template>

<script>
export default {
  name: 'Welcome',
  data () {
    return {}
  }
}
</script>

<style scoped>
p{
  position: relative;
  vertical-align: middle;
  text-align: center;
  top: 45%;
}

.container-fluid{
  margin-left: -15px;
  margin-right: -15px;
}
.lato{
  font-family: 'Lato', sans-serif;
  font-weight: 300;
  font-size: 30px;
}

.mad-full-height{
  height: 100vh;
  widows: 100vw;
  display: block;
}

.white{
  color: white;
  vertical-align: middle;
  text-align: center;
}

.left{
  height: 100vh;
  background-color: #3b2577;
  display: block;
  cursor: pointer;
  transition: all 0.6s ease;
}

.left > p {
  transition: all 0.6s ease;
}

.left:hover
{
  background-color: #ffcc00;
}
.left:hover > p {
  color: #3b2577;
}

.right{
  height: 100vh;
  background-color: #3b2577;
  display: block;
  cursor: pointer;
  transition: all 0.6s ease;
}
.right:hover {
  background-color: #ffcc00;
}
.right > p {
  transition: all 0.6s ease;
}
.right:hover > p {
  color: #3b2577;
}

</style>