<template>
  <div id="jumbotron">
    <div id="jumbo-text">
      <h2>Lorem ipsum dolor sit amet.</h2>
      <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Quidem quo atque ex soluta excepturi, assumenda eos cumque numquam dicta aperiam modi! Aspernatur est earum in ex nihil maxime ipsa aut.</p>
    </div>
  </div>
</template>

<script>
export default {
  name: 'BestHero',
};
</script>

<style>
#jumbotron {
  height: 700px;
  margin-top: 20px;
  background-image: url(https://sm.ign.com/ign_it/screenshot/default/511658-iron-man-3-movies-robert-downey-jr-tony-stark_sk5b.jpg);
  background-size: cover;
  background-position: center;
  position: relative;
}

#jumbo-text {
  position: absolute;
  width: 300px;
  bottom: 30px;
  left: 20px;
  background-color: none;
  text-align: left;
}
</style>